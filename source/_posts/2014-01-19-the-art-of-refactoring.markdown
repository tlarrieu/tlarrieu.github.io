---
published: false
layout: post
title: "The Art of Refactoring"
date: 2014-01-19 13:06:33 +0100
comments: true
categories: 
---

Refactoring, eventhough many agree upon the fact this is good practice, can get delicate to work with. Since refactoring does not add any feature to the current codebase, and because you often have “better things to do”, this phase can be postponed forever. The real question is “when is a good time to start refactoring things?”. A commonly accepted maxim states the following :

> “If it ain't broken, don't fix it.”

<!-- more -->

Well, that's a start at least. But that's certainly not enough as well : you can not let your development be error-driven — or [can you](http://kriswager.blogspot.fr/2009/01/error-driven-software-development.html)? In the previous [article](/blog/2014/01/18/the-proper-tools-to-get-things-done), I was talking about ergonomics. Refactoring is kind of related to that. In fact, any time you feel your are striving with the codebase might be a good time to refactor. I most certainly would add the following sentence :

> “If your code smells, now is a good time to refactor.”

In my opinion, refactoring serves two purposes :

* It enhances your code quality
* It forces you to see the code from a higher level, leaving you with a better understanding of the codebase.

