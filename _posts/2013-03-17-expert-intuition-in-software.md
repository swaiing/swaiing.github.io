---
layout: post
title: Expert Intuition in Software
date: '2013-03-17T22:38:00-04:00'
tags:
- behavioral
- software
tumblr_url: http://stephenwai.com/post/45643833443/expert-intuition-in-software
---
In Thinking, Fast and Slow, Nobel-prize winning behavioral economist Daniel Kahneman argues self-confident professionals who claim to have an expert intuition in a certain area should not be trusted, and that only in a controlled environment can a judgment reflect true expertise. He states that two conditions must be present while acquiring a skill:


an environment that is sufficiently regular to be predictable
an opportunity to learn these regularities through prolonged practice
When both these conditions are satisfied, intuitions are likely to be skilled. Chess is an extreme example of a regular environment, but bridge and poker also provide robust statistical regularities that can support skill. Physicians, nurses, athletes, and firefighters also face complex but fundamentally orderly situations. The accurate intuitions that Gary Klein has described are due to highly valid cues that the expert’s System 1 has learned to use, even if System 2 has not learned to name them. In contrast, stock pickers and political scientists who make long-term forecasts operate in a zero-validity environment. Their failures reflect the basic unpredictability of the events that they try to forecast.

I see this no more relevant than in the world of programming, where the valid form of a program is defined by a syntax, a set of rules surrounding the acceptable symbols allowed in a language.  Clearly, at the language-level it is a very predictable environment, but even at a more macro-level, when assembling software components, this still holds true.  Most developers opt to use common frameworks and libraries, all of which are built on the same ubiquitous design patterns and architecture.  For instance, an experienced developer new to the Ruby on Rails framework might still be able to debug an application error on account of her prior experience with the model-view-controller (MVC) architecture.
These repeatable patterns seen in all levels of coding, make for an environment conducive for building skill and expertise over time.  This is great for those seeking expert advice from coders, because their claims can be trusted.  Signals such as Stack Overflow rep or GitHub activity can be used to support them.
However, as we continue to zoom further out, it is clear that this environment of predictability ends.  After assembling some bits together to serve a purpose, one cannot predict whether a startup will prosper or fail.  Any venture capitalist who claims to be following “intuition” on the potential for the hottest new photo sharing app is probably being affected by an illusion of validity (any early investor of Facebook is probably affected by this) and will be no more accurate than my dartboard.
