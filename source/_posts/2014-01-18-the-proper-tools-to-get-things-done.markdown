---
layout: post
title: "The proper tools to get things done"
date: 2014-01-18 22:57:25 +0100
comments: true
categories:
---

“ What is a good tool ? ” one might wonder. Here is a definition from [Wikipedia](http://en.wikipedia.org/) :

> “Human factors and ergonomics (HF&E) is a multidisciplinary field incorporating contributions from psychology, engineering, biomechanics, mechanobiology, industrial design, graphic design, statistics, operations research and anthropometry. In essence it is the study of designing equipment and devices that fit the human body and its cognitive abilities.”

In short terms, one can say that a good tool is one that both enhances your productivity and increases your comfort.

In this article, I will cover the main tools I use on a daily basis. My intent is not to say that there are no others. Those float my boat, period.

<!-- more -->

# Tmux / Vim

OK. This has been spoken of like a zillion time. Let's talk about it a zillion-and-one-th time.

## What are we talking about?
### Vim

Vim is a modal text editor. It means that it distinguishes several modes in the process of writing text. Among many modes, Vim lets you choose between :

* normal mode
* insert mode
* command mode

Those are the three most basics on which others are built. *Normal* mode is the mode where you can explore and apply transformation (we'll come to that in a minute) to you're file through keyboard shortcuts (single-key or multi-key). *Insert* mode is your average text editor mode, where you boringly write text down. *Command* mode is the mode where you can unleash the full power of Vim and use some built-in (or plugged-in) functions.

There is one single statement the sums up best what Vim is all about : the thing you do the most while developing softwares is **editing code**, not **writing** new one. Why not use an editor that focuses on the first aspect?

I could spend a lifetime (almost literally) speaking about Vim. What made me realize what was the true power of Vim though, is the concept of *text objects*.
Text objects are  groups of characters that have a semantic connection. For instance, a letter is a text object. A word is a text object too. A sentence is a text object as well. A paragraph is a text object. A... Well, you get the idea.
The purpose of those text objects is for you to apply transformations on it : basically you can delete , replace or copy a text object. In fact, anything you can think of when it comes to editing text, you can do it quicker, better and in a more logical (yes, logical, you read correctly) way than with your average text editor.

If you want to learn more about this wonderful text editor, I recommend consulting the following resources :

* [Vimcast](http://vimcast.org)
* [Practical Vim](http://pragprog.com/book/dnvim/practical-vim)
* [Ben Orenstein's Write Code Faster : Expert Level Vim](http://www.youtube.com/watch?v=SkdrYWhh-8s)

Those are on top of my head, don't be shy and explore the whole interwebz for yourself.

### Tmux
Tmux is a **T**erminal **Mu**ltiple**X**er. In short, it means that it transforms your boring single windowed terminal into a rich, split-and-window-ful terminal. But it has more. It can broadcast your current session to any other terminal reachable through your computer. It can be any other opened terminal or an ssh session. It also can save your current session for you to come back later. Finally, you can script it's behaviour to automate certain tasks that you do on a daily basis.

Once you get to know it, you can not live without it!

Here is a 30-ish minutes [talk](http://www.youtube.com/watch?v=9jzWDr24UHQ) about how to achieve better productivity using both Vim and Tmux (it is aimed at Ruby developers but you can get some benefits viewing it nonetheless).

# Fish shell

I do not have much to say about it other than CHECK THIS OUT : [Fish Shell](http://fishshell.com/).
If you still are not convinced after looking at all this beauty, there is nothing left I can do for you.
Seriously : GIVE. IT. A. TRY.

# Keyboards
## Layout

As you may know or may not know, QWERTY — like AZERTY and all the derivative — is a crappy keyboard layout. It has been specifically designed to make you type slower, in order to overcome technical deficiencies of early typewriters. As of now, in a time when we do not need this twist anymore, there is no reason in the world to keep using it. In fact, you have all the reasons to not use it. The earlier you make the switch, the better.
I will not lie to you. This will be hard and it might take time before you can even reach half of your current typing fluency. But I promise you will not regret the switch.
As I am French, I decided to go with BÉPO. This is a french oriented keyboard layout, inspired by projects like dvorak and colemak.

If you want to know more about alternative keyboard layouts, please follow those links :

* [Dvorak](http://en.wikipedia.org/wiki/Dvorak_Simplified_Keyboard)
* [Colemak](http://colemak.com/)
* [Bépo](http://bepo.fr/wiki/Accueil)

Those are not the only ones, but they are the most known.

## Device

Last, but not least in any way, we are going to speak about physical keyboards. Most of you are certainly writing on a "standard" [rubber dome](http://en.wikipedia.org/wiki/Keyboard_technology#Dome-switch_keyboard) keyboard (or on a [scissors switch](http://en.wikipedia.org/wiki/Keyboard_technology#Scissor-switch_keyboard) keyboard for those of you who use a laptop). Let's be honest : those are not the best. If you are looking for higher end keyboards, you should look out for either a mechanical keyboard or a capacitive keyboard. First, they last longer. Then, they have a waaaay better feel. Of course, they do come in a higher price as well. But when you are spending something like eight hours a day typing stuff, would not you like to have a comfortable experience ? I definitely do.

Here are a few resources on that specific topic :

* [Deskthority](http://deskthority.net/)
* [Geekhack](http://geekhack.org/)

You might also want to look into what are called “ergonomic keyboards”. I personally do not like them, but you might.

And for those who wonder, here is my keyboard :

![keyboard](http://i.imgur.com/pN772Dz.jpg)

This is a Poker II (ANSI layout) and yeah, the space bar is upside down — as the two modifiers beside it.
