---
layout: essay
type: essay
title: Past essays
date: 2017-01-21
labels:
  - Past
  - Essay
---

## How to ask a smart question

Opinion:

In my opinion as much as I agree on Eric Raymond view on asking smart questions I also believe on smart answers when replying to these smart questions. For example, in this smart question by Deepankar Bajpeyi: http://stackoverflow.com/questions/19316937/how-to-bind-bootstrap-datepicker-element-with-angularjs-ng-model 

the top answer he receives are very thought out and explains the solution in a few short sentences. However, if you were to scroll down you see most the answers to be quite broad and long. So even though I agree with smart questions, if you also give a stupid answer it negates the effort of the person to ask a smart question. 

Observation: Smart question

Going back to Deepankar’s post he asks a simple question for his title post making it clear what he’s asking for. The question isn’t on par with the smarter section but mostly smart section. Here are some of the good points:

1.	It’s a smart question

2.	It’s on topic

3.	The post is written with little or no spelling and grammar errors

4.	Did a google search of the question, had a tough time finding the answer making this question exceptional to the rule “Before You Ask”.

5.	It has a meaningful header

6.	Question is descriptive and using good format with a separate gray box for coding. 

7.	Short and to the point, it’s just one paragraph long with additional brief questions that further explain the question.

Deepanakar asks a smart question and because of this he receives smart intelligent responses that helps him with his program.

Observation: Dumb question

On the other hand, I did find a lot of bad questions in Stack Overflow. For example, these two questions by Bar Shema: http://stackoverflow.com/questions/41784940/google-in-app-purches-policy 

For Bar Shema, some of the bad points are:

1.	A bad header, his header for his post is generic and isn’t even a question at all.

2.	His first statement that he hopes that this is right place to ask, making it a bad post. 

3.	This question could be possibly found using google search.

4.	The question is more suited towards google forums than stack overflow.

5.	Bad spelling errors in the header.

It seems that Bar Shema is confused on where to put this post and it’s about google policy which would work best at a google forum Q & A page than stack overflow. This is also not a coding problem but a policy question. Bar Shema also should’ve stated his header as a question and check for spelling errors. A good tip would’ve been to use Microsoft word to type it in for spelling and grammar. 

Conclusion:

I now recognize the difference between a smart and not smart question. This lesson did help me in improving myself to think twice before posting a question and use the tips given by Eric Raymond on asking questions the smart way. By doing so, I should receive smart answers and avoid being shunned by the internet community. 

Links:
http://stackoverflow.com/questions/19316937/how-to-bind-bootstrap-datepicker-element-with-angularjs-ng-model 

http://stackoverflow.com/questions/41784940/google-in-app-purches-policy
E11: Reflect on smart questions

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

## After Milestone 3

After milestone 3 my opinion on the naming convention changed. I realized that there are bigger issues that can affect the entire program. For example, one issue that I noticed was implementing semantic UI code into my program. Some of the JavaScript had to connect to a specific term that the user inputs. Another issue that I faced was coding the dividers properly
	
For example:

```
<div class="ui huge center aligned sixteen wide column">
				Or
<div class="ui vertical stripe quote segment">
```

Position of the words can be crucial to make the program work. For example, “aligned center” would create problems making the app to not work or the word “large” instead of “huge” can drastically change the size of the image or header. 

---


<img class="ui image" src="../images/meme.jpg">

*It’s a small joke but do you really want your website to look like the guy on the left?*

## What makes you look professional?

In every job that I’ve been too, a uniform was always required. Especially in the military where an ink stain on your uniform meant that you had to go buy a new one if you couldn’t wash it off. Looking back, it does make sense why a manager or boss would be so picky on the appearance of your uniform. Someone wearing casual clothes at formal affair or a dirty uniform at military formation. The same can be said for any websites, a skewed menu or bad resolution of the image on your website can make it look terrible. Which is why uniformity being important and the best thing about them is that they were already made and built and all you had to do was wear it. Which is the purpose of Semantic UI’s to keep your whole website look professional with a uniform that’s built for you. After all you don’t dress like a bum when you talk to your boss or customers. 

## Semantic UI’s vs Raw steak

Which do you prefer cooked steak or raw steak? Now I prefer my steak cooked well done and would prefer to order it since I’m bad at cooking steak. That’s what Semantic UI does for you it gives you the multiple options to how you want your steak vs committing the time to cook that steak and possibly mess it up. 

Example of regular old html:
```
.left {
	  float: left;
	  width: 300px;
	  padding: 1em;
	}
	.right {
	  float: right;
	  width: 300px;
	  padding: 1em;
	}
	.center {
	  margin-left: 300px;
	  margin-right: 300px;
	  padding: 1em;
	  width: 300px;
	}

```
*Seems like a lot of work just to affix some text or image and are you 100% sure it'll be correct?*

However, it’s not all roses and daisies for semantic UI. Time and effort is needed when you’re learning how to use it and not everything turns out perfect. For example, when I first started using Semantic UI I noticed a huge learning curve. So far, it’s the hardest thing I’m learning from this class (and I thought underscore was difficult). But if I do get pass this wall that I’m facing I’m sure that Semantic UI will help make my website look professional something that I’ll even have a harder time doing by myself. After all, you have a harder time cooking that raw steak that you may mess up on. 

## The review

I just started using semantic UI so I really can’t point out any pros or cons now. However, I did notice some reviews online that caught my attention: 

	CON Very large file size
	Packages are much bigger when comparing to Twitter Bootstrap or Zurb Foundation. 
	– thermoplastics and Mike,
	https://www.slant.co/options/520/~semantic-ui-review#pros 

Which raised the question why don’t we use Twitter Bootstrap or this Zurb Foundation. Looking further into these two frameworks I noticed that they both look very professional. However, after digging even deeper I did find that there are some reasons why semantic UI is better at some parts that Twitter Bootstrap can’t do. For example, per this article: 

Semantic UI is more difficult, making things difficult now won’t make it easier later and it requires more JavaScript which is something we’re all currently learning. The best thing about Semantic UI is that its user friendly when typing in code hence the name semantic. 

- https://www.upwork.com/hiring/development/twitter-bootstrap-vs-semantic-ui/ 

## Key Thoughts

Semantic UI is hard and it should be, nothing is easy in life and down the road things are only going to get difficult. In other words, it’s better to practice the hard stuff first so that if you come across it again it becomes easier. Just like wearing a uniform it can get annoying at first but down the road you begin to get used to it until it becomes a part of you. 

## Resources: 

https://www.slant.co/options/520/~semantic-ui-review#pros

https://www.upwork.com/hiring/development/twitter-bootstrap-vs-semantic-ui/

---


<img class="ui image" src="../images/infographic.png">

*An infographic image on how Meteor works*

### Note: 
I originally wrote this essay while I was on part 3 on digits (the due date was originally sooner) but after completing the WOD review on Thursday my feelings towards Meteor has changed. I have added additional thoughts in the After learning Digits section.

## Space Rock

The average speed of a meteor hitting earth is about 160,000 mph. Which is unsurprisingly the name of the open source platform to build websites. However, for the past two weeks instead of hitting Earth I felt more like a meteor stuck in space missing my target. I’ll admit that I wasn’t really impressed by meteor at first it just seemed like IntelliJ and semantic UI with more steps. However, throughout the week as we learned more about Meteor it became a little bit more interesting as we learned about the benefits of using Meteor such as instant updates, Mongo and how customers have their own little private server to retrieve part of a bigger server. So, I right now I feel like heading towards Earth but at a slow pace and hopefully reach it by next week. 
	
## Issues

Looking back at last week I noticed a lot of people were having issues with meteor and that’s only the portion of folks that had issues just trying to make it start. So, it’s no surprise or embarrassment that I also had some issues using Meteor and this is where I really started to hate Meteor. One of the issues that I faced was having a word misspelled in one of the JavaScript file:
	
```
Changed: 
Template.Add_Contact_Page.events({
                                  
To:
Template.Edit_Contact_Page.events({

``` 

Just one little word from add to edit made my entire code running again. Something that is so elementary and something we should have learned about from the beginner courses but its sometimes the basic problems that can ruin everything. Another issue that I had was some sort of bcrypt warning code that I received while trying to run Meteor on Linux. It was an easy fix but I really hate to fix problems that I don’t know what’s going on.

## Learning Curve

I did notice a huge learning curve to learn Meteor, once you get past one part and know what’s going on you can get a better understanding on how Meteor works. At the Meteor website, it says: “The fastest way to build JavaScript Apps,” right now, I don’t agree with that statement but once I pass that learning curve I think I can appreciate Meteor more. I did enjoy how fast it instantly updates on the localhost website. Also, a lot of the template for the website is pretty much built into Semantic-UI and Meteor. All you really must do is follow instructions and create a JavaScript and HTML file. Unlike how I started out in the beginning with trying to fix the margin of the website heading Semantic-UI and Meteor has relieved some unnecessary steps to creating a website. 

## Conclusion

In conclusion, I can’t say a lot good things about Meteor, this is my first time building a website using Meteor and the first class to make a website in general. I’ll admit it’s hard trying to learn it but at the same time it makes it easy to avoid filtering around the heading, margins, and unnecessary items I must change. I still have a lot to learn so I think I’ll keep my head up high as I go through the wonders (or torturous) path with Meteor. 

## After learning Digits:

I feel a lot more confident on what I'm doing with meteor and I feel like I'm entering the atmosphere of Earth now. I'm haven't exactly hit Earth yet but I'm proud to say that I'm on the right track. I now feel like my previous issue that I had with the JavaScript naming files is something of the past. I now made a checklist to go through those problems and found the issue that I previously found annoying easy. I really didn't have any further issues but what I did find annoying is the number of files that had to be tracked. For instance, creating a Home page meant that you had to keep track of a header, footer, index, etc. If a file didn't point to the correct file then it could create a blank webpage or send meteor crashing. After getting passed that initial learning curve meteor doesn't look so scary now and I can appreciate the efficiency of the automatic updates, publications and MongoDB. I hope by the time I finish up my final project with my group members I'll be a subject matter expert on Meteor. 

<img class="ui image" src="../images/SME.jpg">

*In the Army, we always had to be Subject Matter Experts (SME) in our profession, even if we had to pretend to*

