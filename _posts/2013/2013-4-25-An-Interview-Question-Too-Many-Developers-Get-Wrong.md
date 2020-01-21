---
layout: post
title: "An Interview Question Too Many Developers Get Wrong"
tags: [data structures, learning]
---
Since we do spend some of our time writing and tweaking data structures, I don't think it's too unbecoming of us to ask applicants some basic questions about them. There's one question that seems to throw almost everyone off, here's how we get to it.

First, we ask how you'd find whether a number was in an array? Most people's first answer is to iterate through the array. (I find it funny that most are embarassed by this answer and we often have to pull it out of them, even though they clearly know it). 

Then we ask for another option. Again, most people will answer that you could sort and do a binary search. (some will suggest putting it into a hashtable, which is fine, but we'll get them to give us the sort+binary search answer anyways).

Next comes the big question: *What factors influence which approach, between a linear scan and a sort+binary search, you should pick for an unsorted array?*

Can you guess what most people answer? What's the correct answer (there's more than 1 factor)?
