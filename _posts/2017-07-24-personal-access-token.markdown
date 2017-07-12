---
slug: 'personal-access-token'
title: 'Get A Github Personal Access Token'
link-1-label: 'Personal Access Tokens'
link-1-url: 'https://github.com/settings/tokens'
link-2-label: ''
link-2-url: ''
image: 'https://s3.amazonaws.com/kinlane-productions/lessons/personal-access-token.png'
video: ''
audio: ''
issue: 'https://github.com/contrafabulists-lessons/google-sheet-to-github-website/issues/8'
date: '117-6-24T01:01:00-01:00'
---
Our Google Sheet is ready, and web have a Github repository that operates as a website. Before we can update our YAML with data from the spreadsheet we need get a Github Personal Access Token. These tokens are the key to the update script being able to access the Github API, and take the data from the Google Sheet and update the file in the project's Github repository.

Github makes it easy to generate personal tokens under your account settings, which you can find under the dropdown in the top corner of your Github account next to your profile picture. Under the developer settings section you will find an option to work with your personal access tokens. You will need to give the token a name and some permission. For this project we just need to select public_repo to access public repositories, and read:user to read all user profile data--then generate token.

On the next screen you will be given an opportunity copy your personal access token, which you should copy and paste somewhere for safe keeping--you will need it later. You don't want to ever publish this key to any repository, or share publicly. We will be only passing it in the URL when we are updating the website from the spreadsheet. If you ever think your key has been compromised make sure you delete it from your personal access token list, and generate a new one.
