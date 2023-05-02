---
layout: post
title:  "House of Games Project"
date:   2023-05-2 11:13:10 +0000
categories: portfolio
---
<a href="https://641476fb7b0d4c220c9ce512--house-of-games-uhlar.netlify.app/" target="_blank">
    <img src="{{site.basurl}}/assets/images/posts/hog-logo.png" alt="house of games logo" />
</a>

<br>

House of games is a website forum where users can view, vote, and comment on reviews of board-games. For demo purposes the user is logged in by default and can comment and vote on posts.

<br />

- [Try out the demo here!](https://641476fb7b0d4c220c9ce512--house-of-games-uhlar.netlify.app/)
- [Front-end Repo](https://github.com/JJJUhlar/house-of-games): https://github.com/JJJUhlar/house-of-games
- [Back-end Repo](https://github.com/JJJUhlar/BoardGames): https://github.com/JJJUhlar/BoardGames

<br />

**Front-end:** React


**Back-end:** Node.js, Express, Postgres, Jest, Husky

<br />

House of games was the first full stack application I made during Northcoders' bootcamp. It felt great to be able to put everything I'd learned about coding together. There's an intense satisfaction in having an idea and turning it into reality from nothing. 

<br />

<img src="{{site.basurl}}/assets/images/posts/hog-1.png" alt="house of games screenshot" />

<img src="{{site.basurl}}/assets/images/posts/hog-detail.png" alt="house of games ui detail" />
<img src="{{site.basurl}}/assets/images/posts/hog-post.png" alt="house of games post ui" />
<img src="{{site.basurl}}/assets/images/posts/hog-mobile.png" alt="house of games mobile / responsive ui" />


### How I made it.

I made the backend first with Express and implemented an MVC pattern (this turned out to be very useful!)
I hosted the database on Elephant SQL and the REST api on Render.
Then I made the front end with React and hosted it on Netlify.

<br />

### Challenges and how I overcame them.

Render makes it possible to setup CI/CD with github flow. This was very useful when I ran into a problem as I was making the front end. I needed to re-factor one of the endpoints I'd created so that it would correctly return data in an edge-case query. Because I used the MVC pattern, it was easy to find the code I needed to fix the issue, even though I couldn't remember everything single detail of what I'd written and why. 

<br/>

CI/CD meant that once I'd fixed the problem, I didn't have to mess around restarting the server or reseeding the database. This saved a lot of time. 

<br/>


At this point, the biggest danger was that my update accidentally broke a different functionality. However, because I was using Husky, I knew that I wouldn't be able to deploy if any of my other tests had failed.
 

<br />

### Learning / Reflection: Why CSS is surprisingly difficult

On the one hand, CSS is an essential part of web development. It's often the second thing that beginners learn for good reason... It's also incredibly frustrating

<br/>

Understanding *why* this is frustrating can be useful for learning to develop better software.

<br/>

Like Regex, CSS requires almost complete knowledge of the entire language/system to be able to implement simple ideas and simple changes. Sequence is extremely important and small changes can unpredictably introduce breaking changes elsewhere. It's extremely hard to build on and maintain because of this. The same css which worked perfectly for the current features and layout of a website could be completely redundant with a small layout change, or a new button for example.

<br/>

Trying to add new features to even a moderately complex app highlights how simplicity is the essence of maintainability. Less is more! Naming conventions like BEM help address this, and I've found libraries such as Bootstrap and Tailwind can be useful.

<br/>

Comparing CSS with JavaScript isn't quite apples-to-apples, as one is a markup language and the other is programming language. Nonetheless, it's instructive to notice that React (for all it's flaws) at least shares some fundamental features with other languages which provide a foundation for other tools down the line. CSS is less transferable, despite being essential.