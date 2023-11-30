---
layout: essay
type: essay
title: "Finding the Pattern"
# All dates must be YYYY-MM-DD format!
date: 2023-11-29
published: true
labels:
  - Software Engineering
  - Learning
  - Design Patterns
---

<img class="rounded pe-4" src="../img/designpatterns2_singletonpattern.webp">
Problems are a staple of everyday life. Everyone has them, and everyone's looking for solutions to them. Computer Science has many unsolved problems, like the NP-Problems. However, it also has many problems which are solved, such as searching through an ordered list. While improvements can be made, people are able to implement an algorithm in their code easily. Some problems, however, often have a lot of nuanced situations in which a single algorithm wouldn't be as useful to apply. However, design patterns make this easier. Design patterns are, as it is in their name, patterns. They can be applied to similar-looking situations, but, because they are not algorithms, can be flexible when applying to situations with different nuances, such as a different set of classes that interact in a different way from another project. 

Design patterns have even been very useful in my own code. Splitting up pages into components which hold the meat of the page and the page itself means that if one page uses the same style, say, a card with an image on it, then the component can easily be used in both pages without needing to create a whole new page and duplicate the code between them, which obviously causes problems if there's bugs in the code because they need to be changed twice instead of just once, creating more work. We've even used one of the most basic design patterns, a singleton.

Overall, design patterns are a hard thing to understand because we use them so naturally. In fact, I'd almost equate them to best practices, using code in ways that make it easier to read or transfer. While there is some overlap, best practices don't always involve design and sometimes are just ways to write code to make it easier to read, such as using whitespace effectively.
