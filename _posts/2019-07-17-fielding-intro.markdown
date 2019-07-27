---
layout: post
title:  "Fielding REST Dissertation - Introduction"
date:   2019-07-17 22:17:22 -0500
categories: Paper analysis
---

This post is the start of a series of posts focused on Roy Fielding's [dissertation][fielding-dissertation] on the REST network architecture. My motivation is to gain a deeper understanding of things I'm curious in by conveying my understanding and analysis.

I will begin with covering Fielding's Abstract and Introduction. The main motivation of his dissertation is to:

> Understand, propose, and evaluate the architectural design of network-based application software.

*What does he mean by `network-based application software`?* It's the kind of software that lets you access resources and services, essentially information, from a remote computer. The kind that not only grants you this ability to access this information, but to also convey it to others. The Internet. Of course the Internet is not the only network-based application software, but it's the most prevalent example of one. Imagine a high school classroom, and the teacher has her back to the class while scribbling some notes on the blackboard. Several students are taking notes, several are distracted on their computers, and several still are sleeping. Now imagine several students passing notes between each other. In this scene, these students are communicating...they have formed a network. The "software" necessary for this communication to be possible is a pen, paper, a throw, and a catch. Of course, the teacher turns around, and intercepts the note, but this is also part of the system of communication; it's part of the "software". In short, network-based application software is a means of communicating information. Only in this case, the students are computers, and the teacher is a failure in the system of communications. Of course, for the software to be useful, it must be know what to do for various failures and various scenarios.

*What does he mean by `architectural design`?* Weren't we talking about software, not buildings? Well, just as in architecture there is an adage `"Form follows function"`, he states that to understand and build an architectural design of network-based application software, one must first examine the architectural constraints. These are a set
of rules designed to obtain specific properties of the "network-based application". These properties define the
application, as in they are the unique features of the application as experienced both by the users and the developers.
The constraints help determine:
  1. How an application divides work into components
  2. How components collaborate
  3. How information flows through the application
  4. How components can evolve independently
among many other properties. It is Fielding's philosophy that constraints begets an architectural style, which begets an architectural design and brings the application to life with its properties.

We discussed a little about "network-based application software" and "architectural design". Fielding's goal is firstly understand how to create such designs for such software, and he does this by analyzing the design of existing network-based applications. Secondly, he proposes a new design for network-based application software, and finally applies this design to existing network-based application software such as the modern Web and evaluates the results from that exercise.

[fielding-dissertation]: https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm
