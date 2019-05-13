# Lolcat-Clock - *app project*
**A JavaScript project with an interactive clock and events.**

## General info

Here is a project of a working Lolcat Clock that incorporates Javascript. It features an active clock with dynamically changing images. 
It will automatically update based on the time of day.The selectors also allow the app to be interactive, with changeable events such as 
setting the *Wake Up Time*, *Lunch Time*, and *Nap Time*. It's interactivity includes a *Party Time* button too, that's ready whenever 
you are!

The purpose of this project was to learn how to code using JavaScript. It helped to teach best practices in writing good JavaScript code 
that is easy to read.  It provided valuable practice in defining variables and how to use `getElementById` to access and interact with 
the app, including interactive buttons. It also allowed practice in creating a working clock, by retreiving the current time and using 
the `setInterval` method.

My motivation in completing this app was to learn how to think through the logic when writing accurate JavaScript code.  It also taught 
me the proper syntax when writing JavaScript, as well as indenting my code properly.  For me, it especially shows the value of 
including JavaScript in my projects.  It can really add tremendous interactivity and life to a site or project!

## Technologies

- HTML (provided)
- CSS (provided)
- JavaScript


## Code Examples

```
    var updateClock = function() {
	var timeEvent = document.getElementById('timeEvent');
	var lolcat = document.getElementById('lolcat');
	var messageText;
	var image = "https://s3.amazonaws.com/media.skillcrush.com/skillcrush/wp-content/uploads/2016/08/normalTime.jpg";

	if (time == partyTime) {
	image = "https://s3.amazonaws.com/media.skillcrush.com/skillcrush/wp-content/uploads/2016/09/cat4.jpg";
        messageText = "IZ PARTY TIME!!";
	} else if (time == napTime) {
	image = "https://s3.amazonaws.com/media.skillcrush.com/skillcrush/wp-content/uploads/2016/09/cat3.jpg";
        messageText = "IZ NAP TIME…";
	} else if (time == lunchTime) {
	image = "https://s3.amazonaws.com/media.skillcrush.com/skillcrush/wp-content/uploads/2016/09/cat2.jpg";
        messageText = "IZ LUNCH TIME!!";
```
    
## Setup

This site was built and added to my [personal portfolio website](http://www.bryanwesleyherbert.com/lolcat-clock/)

## Status

Project is: *finished*

## Sources

This app tutorial was provided by **Skillcrush** - *online course*

## Contact

Created by **Bryan Herbert** [bryanwesleyherbert.com](http://www.bryanwesleyherbert.com) / email: bryan77@twc.com - Feel free to contact me!
  

