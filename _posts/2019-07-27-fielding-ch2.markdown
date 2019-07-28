---
layout: post
title:  "Fielding REST Dissertation - Chapter 2"
date:   2019-07-27 14:18:22 -0500
categories: Paper analysis
---

We've been talking about Fielding's purpose of understanding, proposing, and evaluating the architectural design of network-based application software. We've also been talking about the different players to consider in an architectural design. In this post, I'll be diving a little bit deeper into what exactly we are trying to design, and what exactly we want our design to accomplish.

More specifically, we will:
  1. Discuss what he means by "network-based"
  2. Discuss what he mans by "application" software
  3. Discuss the importance of context in both creating and evaluating an architectural design
  4. Discuss what it is an architectural design creates

Fielding limits the scope of his dissertation by qualifying the type of software he examines to "network-based" and "application". It is important then to understand what type of software we are looking at. The primary characteristic of a "network-based" system is that communication between components is restricted to `message-passing`. This is a type of communication where computer A sends a message to computer B so that computer B can run some specific piece of code. These "messages" are what drive the flow of information and computing, instead of other forms of communication such as one process calling the other specifically. Having this protocol of communication creates a shared space where computers can have the ability to collaborate with each other. It creates a space that other systems such as "distributed" systems can leverage to create a shared purpose with multiple computers. The difference between a "network-based" system and other systems such as a "distributed" system is that the "network-based" system creates a shared space, while a "distributed" system creates a shared purpose. The "network-based" system does not really care what the computers do with their ability to communicate and network with the other computers. In a way, we are concerned with **how** computers should communicate, rather than how computers can use their ability to communicate.

Within this context of a "network-based" system, Fielding is concerned with the application level, instead of other levels such as the networking level. He cares about **why** we want computers to communicate. It is with this viewpoint that we can successfully design an architecture. We have to know the demand and what users want in order to supply them with the appropriate software. We also have to know what the users value...this will help our design and help us decide what to sacrifice and trade-off.

This understanding of rationale is important when evaluating architectural designs. With rationale, we can see if the properties created from the architectural constraints achieve the desired system objectives. These properties include performance, scalability, simplicity, modifiability, visibility, portability, and reliability. Different use cases raise needs for different properties, but we must create our design with the end in mind.
