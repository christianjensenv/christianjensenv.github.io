---
layout: project
type: project
image: images/studyup_logo_square.png
title: Shopping Mall Project
permalink: projects/Study UHp
date: 2020-05-14
labels:
  - Website application development
  - Teammwork
summary: A team based sotware development project for a web application that helps students find tutor sessions, and teach others.
---

## Landing Page

This is the landing page for Study UHp which I was responsible for. It presented a new challenge in which I thought it would look nice and make more sense from a secure standpoint, to hide the navbar and footer. This way it has a similar aesthetic to a site like [tumblr.com](https://www.tumblr.com/). It was found that this wasn't as trivial as I thought. Aaron, one of my teammates had great ideas in which allowed us to make this possible. Working in my first team-based project, I usually don't have that kind of help when it comes to figuring out a solution. We also thought we could make the Sign In, Sign Up buttons more inviting and interesting by ditching the bland flat color. So I found out how to use CSS and found many good resources in which I picked for the moving highlight. Also, it stays true to our theme as the mouse hovers over. We also found this cool parallax npm that we applied to the logo and makes more interactivity to the first thing that the user sees. Learning all the quirks when resizing the page helped me make it look more seamless, and overall learned alot from this part of the project.  
![Landing page](images/Landingpage.PNG)

## Forms

I was also responsible for updating the uniforms for the add session, and edit session. However, this presented many issues for me as I learned that uniforms are more complicated when adding custom fields. I wanted to deviate from the simple template everyone was using, and I wanted to use a custom date selector called React DatePicker. The first problem is that it didn't match uniforms format so with some CSS trickery I matched it pretty well. The other problem was formating the date, as it became difficult because at first, I wanted a day, start time, and end time for a session, which I achieved but later learned the site was refactored and it presented a new challenge as I had tried my best to figure out how to format the dates again removing the day field and making uniforms catch the errors. Other teammates had to change things that made my testing a bit more difficult, however, this is how things would be in a real-world environment anyways but before I could finish my issue, I needed to wait on some bug squashing done by my teammates. And I'm not complaining this just opened my eyes to things that I could request to be done differently, and how I could do better as a teammate as well. To be completely honest I was trying my best to get this issue done spending probably upwards to 30 hours trying to learn the intricacies with uniforms but it doesn't have much documentation for custom stuff. So, unfortunately, I could not get this up to the master branch before the due date.   

<img class="ui medium floated center rounded image" src="/images/dayPick.PNG">
<img class="ui medium floated center rounded image" src="/images/timePick.PNG">