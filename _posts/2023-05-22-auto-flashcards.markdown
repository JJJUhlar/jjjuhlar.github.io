---
layout: post
title:  "Auto Flashcards (on going)"
date:   2023-05-22
categories: portfolio
---

<br>

Autoflashcards is a browser extension which will allow users to automatically generate flashcards from the content of any webpage and use a spaced repetition system to help users remember what they learn.

<br>

## Brief
It's well known that flashcards are one of the most effective methods of learning. However, the traditional way of using flashcards is broken. Computerised Spaced Reptition systems like Anki aimed to fix some of these problems, but there are still common problems for users for example:

<br>

- Time consuming to produce: Even if they know that flashcards are the best system for learning a topic, often users don't use them because they are *so* time consuming to produce (even though they may take very little time afterwards)
- Bias towards simplest to produce uses: Flashcards are underutilised for learning topics outside of language learning, because vocabulary drills are the easiest kind of cards to make.
- Stumbling on old cards: When practicing cards over a long period, forgetting the answer to an old prompt can be challenging because the answer on it's own doesn't provide enough context or reasoning to remind the user *why* the answer is what it is. e.g. you forget what "je m'appelle" means in English, but when you read that the answer is 'My name is', this doesn't explain the grammar rules of why this is the case. This is a big problem because it can make using flashcards for long term recall redundant.

<br>

Autoflashcards aims to address these problems in several ways.
1. Use a large language model to generate flashcards quickly and automatically from any text input.
2. Leverage LLM capabilities to generate a wider variety of prompts and mnemonic devices than was previously feasible in a spaced repetition system. e.g. multiple choice questions, acrostic poems, rhymes, etc.
3. Track the source material of all flashcards, so that it can be easily and immediately revised whenever something is forgotten.

<br>


## Setup

<br>

In it's current form, it is possible to use Autoflashcards by cloning the repos for the chrome extension and server:
- [https://github.com/JJJUhlar/flashcards-server](https://github.com/JJJUhlar/flashcards-server)
- ~~https://github.com/JJJUhlar/auto-flashcards-plugin~~ *The most recent repo is available at: [https://github.com/JJJUhlar/flashcards-vue-extension](https://github.com/JJJUhlar/flashcards-vue-extension)*

<br>

Each repo contains a Readme with setup instructions.