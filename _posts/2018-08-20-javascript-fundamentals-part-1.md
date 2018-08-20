---
layout: post
title: "JavaScript Fundamentals, part 1"
date: 2018-08-20 13:00 -0400
categories: [javaScript, front end development, professional development]
---

I've lost track of the amount of times I've been embarassed by my lack of JavaScript understanding and I've finally resolved to do something about it. I use it all of the time. I'm able to do things with it, particularly using jQuery for DOM manipulation. But I don't understand it a level I need to. That's cost me a lot of headaches and a few heartbreaks too.

I'm working my way through a short course on [The Gymnasium](https://thegymnasium.com/) to brush up on my fundamentals before moving on to a popular framework like Vue or React.

I've resisted learning these and just gotten by on my (impressive) googling ability but it's well past time that I know it well enough to be tested on it. 

Today's lesson was pretty straightforward; we covered what a variable is and how to make them, what numbers are like in JS and some basic operators, as well as booleans and conditionals.  We covered coercion rules which I'd never heard of before and also some interesting things about strings that if you just pick up using JS you don't really learn. Mostly, this lesson (1 of 6), was a review for me, which is good. I know more than I think. Doesn't mean I like coding tests any more than I did yesterday, but at least I'll be able to do better on them if I'm ever asked again. 

Oh!  here's a small sample bit of today's lesson. This script compares term1 and term2; if term 2 contains term 1, it will out put one message to the console, else it will out put a different message:

<code>
	var term1 = "art", 
    	term2 = "earth";

	if(term2.indexOf(term1)!= -1){
	  console.log(term2 + " contains " + term1);
	} else {
	  console.log("There is no" + term2 + "in" + term1);
	}
</code>   

in this case, because term1 is in term2, it would output the first message. There's a lot going on there, and while it isn't particularly complex or useful, shows you that I'm getting there. 
