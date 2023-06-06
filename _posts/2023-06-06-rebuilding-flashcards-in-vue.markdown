---
layout: post
title:  "Flashcards Extension Rebuilt with Vue and Vite"
date:   2023-06-06
categories: portfolio flashcards chrome-extension Vue Vite TypeScript
---

I have just finished rebuilding my previous flashcards project using Vue. I also used several other new tools such as Vite, TypeScript.

Have a look on github here and find instructions to install the project:
- [https://github.com/JJJUhlar/flashcards-vue-extension](https://github.com/JJJUhlar/flashcards-vue-extension)

The back-end repo is available here too:
- [https://github.com/JJJUhlar/flashcards-server](https://github.com/JJJUhlar/flashcards-server)

I attempted to build the previous version of this project in vanilla javascript, just to see what it was like, and to kick the idea off. Even though I knew I'd eventually have to move it into a framework, I wanted to see how far I could get without one. 
I feel like I have a better appreciation of the DX problems that frameworks solve, and on the other hand, how a framework might over-engineer some of those problems.

There's an argument that starting in vanilla JS was particularly appropriate for this project, as chrome-extensions have a range of restrictions on apis that can be used and how files/modules are able to communicate with one another. This was a key challenge throughout, and beginning with a tested idea of how the application should function was very helpful.

I still have many ideas for this app following the [brief I created]({% post_url 2023-05-22-auto-flashcards %}) but it's exciting to have a solid, maintainable foundation to build on going forward and to start investigating some user feedback.
