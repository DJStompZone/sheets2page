---
slug: 'display-data-using-home-page'
title: 'Display Data Using Home Page Listing'
link-1-label: 'Liquid GitHub Page For This Project'
link-1-url: 'https://github.com/contrafabulists-toolbox/google-sheet-to-github-website/blob/master/index.html'
link-2-label: ''
link-2-url: ''
image: 'https://s3.amazonaws.com/kinlane-productions/lessons/liquid-links-example.png'
video: ''
audio: ''
issue: 'https://github.com/contrafabulists-lessons/google-sheet-to-github-website/issues/10'
date: '117-6-22T01:01:00-01:00'
---
Now for the last step in this lesson--displaying the data on the home page of the web site. This project leverages Github Pages which allows you to run [an instance of Jekyll](https://jekyllrb.com/), a static content management system, for any data projects you run on Github.  The home page on the website for this data project has a simple HTML listing generated from the YAML data we published from the Google Sheet, using [Liquid](https://help.shopify.com/themes/liquid/basics).

The home page for the project is just a simple links list, but it shows how to connect to any YAML file in the _data folder, and loop through each item (row). It demonstrates basic field selection and displaying them in the browser, which can easily be modified for any field published from the Google Sheet. You can add as many fields as you need, just make sure and pull the spreadsheet each time you add new fields. Once the YAML is published you will have access to the new fields and values using Liquid.

That concludes the the website publishing pipeline from Google Sheet to static website on Github Pages, leveraging the data features of Jekyll to publish data as dynamic (but static) web pages. The pull spreadsheet script should adjust for any fields, as well as any sheet or worksheet. It is meant to provide a scrappy, but effective way to take spreadsheet data and make available on a website, which actually free--Github public pages are free, and Google Docs for Gmail is free (well, there are hidden costs).
