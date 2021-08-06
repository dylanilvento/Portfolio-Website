---
title: Commonwealth Data Point
layout: project
subtitle: A government transparency portal site made for the <a href="http://www.apa.virginia.gov/">Virginia Auditor of Public Accounts</a>. The site houses both financial and demographic data collected by the APA for the state of Virginia.
date: 2017-09-07 12:00:00
tags: [dev, project, design, web]
thumbnail_image: data-point-screenshot-background.png
portfolio_background_image: data-point-screenshot-portfolio-background.png
screenshot_1: data-point-screenshot-1.png
screenshot_2: data-point-screenshot-2.png
screenshot_3: data-point-screenshot-3.png
secondary_button_text: virginia.gov
secondary_button_link: https://datapoint.apa.virginia.gov
background_rgb: rgb(255,255,255
made_using: [angular, chart-js, sass, php, bootstrap, sql]
---
Originally constructed in 2017, Commonwealth Data Point is my ongoing project for the [Virginia Auditor of Public Accounts](http://www.apa.virginia.gov/). As a state-mandated transparency portal for the Commonwealth of Virginia, Commonwealth Data Point allows citizens and government stakeholders to view important financial and demographic data about the state, including expenditures, revenues, population, public school enrollment rates, registered vehicle figures, and more.

Data Point’s dashboard pages are built as single-page applications, dynamically querying and loading different data sets depending on what the user wishes to view. Financial data is viewed via a drilldown system, where more general groupings of data are viewable at the very top — such as the different government branches — with more and more specific grouping viewable as you drill down — such as financials for distinct government agencies or specific line-item transactions.

The frontend logic of Data Point is built via [AngularJS](https://angularjs.org/) and an implementation of [Chart.js](https://www.chartjs.org/) for data visualizations and [DataMaps](https://datamaps.github.io/) for mapping visualizations. Data sets are constructed using programmatically assembled SQL queries that are then sent to our backend via PHP scripts. The data sets are then saved in JSON files which we use to populate the data on the frontend. Commonwealth Data Point is updated on a regular basis to add dashboards for new types of financial and demographic data.