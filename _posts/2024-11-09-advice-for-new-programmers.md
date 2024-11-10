---
layout: post
author: Douglas Krouth
title: "Advice for new programmers"
categories: ["Unsolicited Advice"]
original_publish_date: 11-09-2024
---
*Bits of advice that I wish someone had told me when I first started out.*

**TL;DR**:<br>
* New programmers should seek general programming knowledge instead of trying to just learn a language or framework
* Be wary of "programming content"
* Find a cheap computer
* Give Linux a shot

***
## Seek to be a good carpenter, not a good hammer-er
Programming and carpentry share a common thread in that they involve a person (you) using tools to complete a task. A carpenter will use a hammer to complete some task (framing a wall, building a deck, etc.) and while they might be proficient in hammering, they probably don't define themselves solely as a "Hammer Expert".

When starting to learn programming-or computer science in general-it's common to try to master a language or framework as quickly as possible. This might lead to a lackluster understanding of fundamentals if you don't take the time to learn the underlying concepts of basic data structures, control flow, basic algorithms, etc. I don't say this to disparage people who are trying to learn something quickly to change careers, pass a class, \<insert circumstance\>. Instead, I think it's important to understand that many of the basic ideas that you can learn in a language like C will also apply to other languages like Python or Java (albeit with different implementations and creator's opinions).

It's better to see a language or a framework as a tool rather than the total scope of things that you need to learn to be a "good developer". Don't see yourself as a "Python developer", "React developer", "\<framework/language\>" developer-instead focus on learning the underlying concepts and try to understand how they're used all over the place.

**Caveat** : Proficiency and mastery of languages, tools, and frameworks is extremely valuable and I don't intend to discourage anyone from pursuing it. In the past I've gotten frustrated when trying learn something without understanding how some of it's underlying components worked.
* A personal example was trying to understand Scala's `map()` function without knowing what a monad was.

***

## Online "programming content" can be a waste of time (how meta!)
For new programmers, I think it's critical to turn off sites like *YouTube*, *Reddit*, *HackerNews*, etc. when looking for programming and/or professional information. I'm not arguing that there aren't valuable resources on those sites (YouTube has excellent lectures from MIT OCW for example) but I do think it reaches a point of diminishing returns pretty quickly. It's easy to lull yourself into believing that reading programming content like Medium articles without actually writing code will foster learning. I advise against this in general, but especially for people just starting out.

As someone who has fallen down a couple of programming content rabbit holes (the lamest confession in human history), I've found myself thinking that I was learning when I actually wasn't. It's easy to say "I want to learn about X" and then watch or consume content related to it for large amounts of time because it's less work compared to working on a problem, book, etc. I've done that pseudo-lecture/video essay binge before on concepts like compilers and I know other colleagues who've said similar things. That's not to say that you can't learn things from this style of presentation; however, I believe that it's inefficient and can be a foot-gun for people starting out.

Content that's released on social media platforms is far less likely to be impactful because it's built and provided on the premise that it needs to maintain your attention for ad revenue. That's not to say that there aren't outliers ([3Blue1Brown](https://www.youtube.com/c/3blue1brown), [Kevin Powell](https://www.youtube.com/@KevinPowell), [MIT OCW](https://ocw.mit.edu/), [Harvard CS50](https://www.youtube.com/watch?v=IDDmrzzB14M)) but I'm inclined to recommend looking at documentation, reading textbooks, whitepapers, etc. over content on streaming/social media platforms.

The backstep that I will take is in regard to educational entertainment content ([edutainment?](https://www.merriam-webster.com/dictionary/edutainment)). Channels like [Computerphile](https://www.youtube.com/Computerphile) are extremely fun to watch and they scratch the surface-level itch for learning that I think is difficult to get outside of university open lectures, brown bag talks, etc.

#### Suggestions
* Use sites like Reddit or HackerNews to get recommendations to sources, books, articles, papers, etc. An example was when I was initially interested in learning about compilers, I checked Reddit and was recommended *Crafting Interpreters* by Robert Nystrom (which is awesome).
* Programming books (not formal textbooks) are the gold standard to learning introductory programming concepts if you're just starting out. Copying code snippets verbatim from introductory books is how I taught myself languages like Java and Python: it lays a foundation of knowledge that can be built off of. A couple of my favorite introductory sources are listed below:
    * [*Automate the Boring Stuff* by Al Sweigart](https://automatetheboringstuff.com/) : Recommended everywhere, it is a gentle and fun introduction to all sorts of programming concepts using Python. Work through the examples and complete all of the exercises.
    * [*Eloquent Javascript* by Marijn Haverbeke](https://eloquentjavascript.net/) : Introductory book that teaches a ton of fundamental concepts, useful to beginners even if you don't end up using JavaScript.

**Caveat** : Neurodivergence, learning disabilities, life circumstances, and access to educational materials can influence what you have access to at a given time. I don't intend to make fun of people that like watching YouTube to learn how to code.

***

## Buy or use a cheap computer for learning to code
If you don't already have a computer that you can use for programming or want a dedicated computer that you don't have to worry about "messing up", I recommend finding a cheap laptop. Ebay is chock-full of affordable used computers that can serve as a great platform for experimentation, trying out new operating systems, etc.

I'm partial to Lenovo ThinkPad's as they provide an excellent refurbished system for a few hundred dollars (as of writing). Corporate liquidators often sell them for peanuts online and they have comparable specs (albeit a few years out-of-date) to many of the laptops that you could purchase for 2-3 times the price.

**Caveat 0** : I'm a dork who informally collects Lenovo ThinkPads.<br>

**Caveat 1** : Do not buy a dedicated programming computer if you are struggling financially. This advice is meant to dispel the idea that you need a brand new $1,500 MacBook Pro to write code.

***

## Try Linux
If you have any interest whatsoever in systems programming, cloud computing, machine learning, data science, and software development at a professional or industrial scale: you will almost certainly need to know the fundamentals of POSIX-compliant operating systems (i.e. Unix and Linux).

To build familiarity with POSIX commands, I highly recommend using a Linux-based operating system on a regular (daily if possible) basis. Related to the point above, I found this process to be much simpler when I set up an old, cheap T430 with Ubuntu and used it as regularly. Use a computer with Linux installed on it regularly and start messing around with running commands in the terminal. Virtual machines (VMs) also provide a phenomenal option to access Linux without needing a dedicated machine.

If you don't want to set up a dedicated computer to learn Linux/Unix system concepts and commands, you can absolutely use WSL (Windows Subsystem for Linux) or a machine with MacOS installed.


**Links and resources to learn Linux/Unix/POSIX:**
<ins>Tutorials and docs</ins>
* [Linux Journey](https://linuxjourney.com/) - Small, structured learning tracks to learn Linux concepts
* [Basic Unix commands](https://mally.stanford.edu/~sr/computing/basic-unix.html) - Not super useful day-to-day, but it gives you a grasp on terminal commands

<ins>Fun historical stuff</ins>
* [Unix vs. Linux](https://www.linuxjournal.com/content/unix-vs-linux-what-is-the-difference)
* [What is POSIX? Richard Stallman explains](https://opensource.com/article/19/7/what-posix-richard-stallman-explains)
* [Ken Thompson interviewed by Brian Kernighan](https://www.youtube.com/watch?v=EY6q5dv_B-o) - Inspiration for Unix , some history on operating systems

**Caveat** : I work with Linux systems and I am a Linux fan-boy. POSIX-compliant operating systems are numerous and far-reaching, MacOS and other Unix-like implementations provide similar interfaces to learn POSIX concepts. Take my advice with a grain of salt.
