---
layout: essay
type: essay
title: "Meteor Gotchas"
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

## Hard problems

  I faced a lot of issues the past week on Meteor Digits. I of the biggest problems that I faced was from Digits, part four where I forgot to change a variable from Add to Edit. Because of this one little issue I had to re-watch the screencast twice and work on part four for nearly three hours. So, the solution that worked for me was to scan every single file in my directories on IntelliJ. I made sure to find any out of place wording which allowed me to find the very small error in my edit-contact-page.js:

```
Changed: 
Template.Add_Contact_Page.events({
                                  
To:
Template.Edit_Contact_Page.events({

```
                                  
This one little error must have caused my program to go through file edit-contact-page.js instead of add-contact-page.js. I've had similar issues like this before where even one word would mess up my code or program but I couldn't even imagine that it would take this long. 
                                  
  The second major issue that I faced was from running meteor from my Linux terminal. Sometimes when I tried to start meteor by using meteor npm start run I would face an error saying that my system is crashing. At first I just thought something was wrong in my code or I had to use meteor reset but when I continued to have problems I decided to look at the slack message board. Apparently other people were facing the same issue and it was surprisingly a quick fix by typing in bcrypt warning code.
