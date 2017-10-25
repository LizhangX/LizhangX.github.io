---
layout: post
title:  "Wrapping up the growth project"
date:   2017-10-19 13:55:00
categories: blog
---

I have finished the entire function of my auto-belt-grader project except for checking html indentations. This app is built in Django, instructor can upload the exam zip file from students(any compressed format). The web app can unzip the file and locate the .html and .css file in the folder. Once the app locates the .html file, it will render the file in the headless Chrome browser and take a screenshot of the .html for instructor to review. Then the .html and .css file will be automatically upload to the W3 validator and the headless browser will get the number of errors back. After it runs through both files, a Beautiful-Soup script will be called to parse through the .html file to see if there are unique classes or inline styles, and will also check if there are divs with only single child.

Here is the github link to the project. 
- [https://github.com/LizhangX/auto_belt_grader](https://github.com/LizhangX/auto_belt_grader)