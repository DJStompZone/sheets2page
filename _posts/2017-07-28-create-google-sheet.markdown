---
slug: 'create-google-sheet'
title: 'Create Google Sheet'
link-1-label: 'Google Sheets'
link-1-url: 'https://docs.google.com/spreadsheets/'
link-2-label: 'Project Google Sheet'
link-2-url: 'https://docs.google.com/spreadsheets/d/1M_trEXOgzOWVn5YJSWfcXYQ7CXu3F3CS2Y-bKEaDUiE/pubhtml'
image: 'https://s3.amazonaws.com/kinlane-productions/lessons/create-spreadsheet.png'
video: ''
audio: ''
issue: 'https://github.com/contrafabulists-lessons/google-sheet-to-github-website/issues/3'
date: '117-6-28T01:01:00-01:00'
---
For this lesson I am assuming that you have a Google account, and are aware of Google Drive and Sheets, since the datasource for the project will be a Google Sheet. While not as powerful as a database, Google Sheets work just fine as a small data store, perfect for publishing simple data-driven projects. The best part is that it can be used as a data store by anyone, not just developers, making it an ideal vehicle for moving forward small data projects similar to how you would manage code using GitHub. 

This project depends on a specific set of fields, which are set as the first row for each column in the spreadsheet. Here are the fields needed for this project, and for each lesson:

- **slug** - A unique string to describe
- **title** - The title of the step.
- **description**** - The description for the step -- may include HTML.
- **link-1-label** - A label for link one.
- **link-1-url** - A url for link one.
- **link-2-label** - A label for link two.
- **link-2-url** - A url for link two.
- **image** - An images, screenshot, or other graphic for the lesson step.
- **video** - A video or screencast for the lesson step.
- **audio** - A audio file for the lesson step.
- **issues** - A link to the issue setup for this lesson step.

I recommend freezing the first row in the Google Sheet, preventing it from being caught up in any sorting of the steps. The script that takes the data from this spreadsheet depends on all these fields being present to work right. Make sure you do not change the column field names, only the contents of each row.

[While any data project](https://contrafabulists-toolbox.github.io/google-sheet-to-github-website/) developed in this way will run off of whatever data has been published to the GitHub repository, the Google Sheet will always remain the primary source. It provides an easy way to collaborate around any open data project. All you do is share the Google Sheet with anyone you want to help create or manage data, and publish regularly using the process outlined in future steps for this lesson.
