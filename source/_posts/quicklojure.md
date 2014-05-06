---
layout: post
title: "Quicklojure: Yet Another Clojure Distribution"
date: 2013-08-19 22:51
comments: true
tags: clojure
---

The truth is that there is no *really* something called the clojure distribution. In fact clojure is just a java library packaged as a jar file.

What is quicklojure then? It is just a packaging of the clojure core library as well as several nice libraries for a new clojure learner and a entry command clj.

I did it just for the sake of several principles I like:

* Easy: a beginner should write ```(println "Hello World!")``` in hello.clj and run ```clj hello.clj``` to get "Hello World!" immediately.
* Fast: the command clj should be perceived as fast even due to jvm slow start characteristic.
* Intuitive: it is a more straight way to install a new library by using ```clj install ring 1.1.8``` rather than writing a project.clj and run ```clj deps```.

These above are what *quick* means.


