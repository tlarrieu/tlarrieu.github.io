---
layout: post
title: "Diving into code"
date: 2014-01-25 00:10:51 +0100
comments: true
published: false
categories:
---
After a month here at [Shopmium](http://www.shopmium.com), I can say I've been
through a pretty huge load of codelines.  At first, this might seem to be very
discouraging : you do not understand what is what, you do not know if your are
going to break anything.

In this article I'll try to share with you some “techniques” I've used to get
through with it and start to be more efficient with this kind of situation.

<!-- more -->

## Use your toolkit

First of all, trust your VCS, be it Git, Mercurial or even SVN. If your are
not very comfortable with it, now is a good time to learn how to properly use
it. Maybe not in depth, but at least just enough to be able to revert changes
you will make. This way, you won't feel bad about breaking anything at least.
By the way, if this is not already a good practice in your company, always
work on your own branch, to isolate your work and thus providing yourself with
extra confidence regarding modifications. And if your company does not use any
kind of VCS, **get yourself out of there** and find a new one!

## Wreak havoc!

Now that you get your tools ready to repair any potential mistake, we can
start breaking things apart. I mean, not destroying the whole codebase. Only
some selected pieces so that you can mesure the impact of your modification.
The best way to understand what something does is to watch what happens when
it's not here anymore. This technique won't work hundred percent of the time,
but in most cases, it's a quick way to figure out what is what.

## Feel at home

The final step will be refactoring. Once you're a bit more confident with the
codebase, start to moves things and reorganise it. You will most likely stumble
upon pieces of code that are not well factored. Tweak them to enhance both the
code and your [knowledge about it](/blog/2014/01/19/the-art-of-refactoring/).

## Bonus stage

I should add that testing is also a great way to get informations about code.
First, by reading it, you can start to comprehend what it is supposed to do and
how it should behave. Then, it is also a good way to detect when you have
broken things around. Using tests during both the “wreak havoc” and the “feel
at home” phases is pretty useful.
