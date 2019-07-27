---
layout: post
title:  "Fielding REST Dissertation - Chapter 1"
date:   2019-07-27 14:17:22 -0500
categories: Paper analysis
---

Previously, we discussed a little about Fielding's Abstract and Introduction. Today, we'll be going a little more
into detail and discuss 1) a high level view of what exactly it is that we are trying to create and 2) the components in
play that we have to consider, both individually and in relation to one another.

Ultimately, we are trying to create a software architecture, with the goal that the architecture will manifest into a network-based application software. What is a software architecture? It is kind of like a blueprint that will be used to create a building. However, unlike buildings, software isn't a static entity after being built. Software is dynamic, as in it is constantly receiving and outputting new information. Thus, we have to consider the architecture behind the software as also dynamic. More specifically, we can't think of software architecture in a vacuum, we must consider, visualize, and use it while the software is running. If software in use is like a symphony being performed, then the software architecture is the sounds the musicians are playing, and governs the interactions between musicians. The audience will only hear the end result, but it takes an architecture; it takes all these interactions and orchestration between different musicians and their sound. At the highest level then, what we are trying to create is a software architecture...an abstraction of the different elements and their interactions while a software is running.

Let's take a look at the elements that an architecture has to consider. First, is the component. The component is a software element that receives data, process it and makes meaning of it, and then broadcasts its findings to another component. That means a component has several key concepts such as an interface that other software elements can use to communicate with it, logic to process the data, and a way of locating other components and being aware of their interface. In our symphony example, a component is a musician. Like a component, the musician receives information of what to play, and plays the music according to their own interpretation. Second, is the connector. This element helps components communicate. A connector is like a conductor helping orchestrate the musicians. Third, is the datum. This element is the pieces of information that connectors relay to components to process. It is like the note.

The configuration, or architectural relationships between these elements produce a software with several architectural properties, such as scalability, maintainability, or visibility to name a few. An architecture is successful if these created architectural properties form a superset of the desired requirements of the system.

In summary, we are trying to create a software architecture that governs the software elements and the interactions between them. By doing so, we can create a software with the desired properties.
