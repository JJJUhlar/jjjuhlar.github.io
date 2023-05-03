---
layout: post
title:  "Fan Finder group project"
date:   2023-05-2 16:27:10 +0000
categories: portfolio
---


Fan Finder is an app that allows people to find events/gigs near them and fans to go to them with. It includes a map that shows events near the user, and allows them to chat to other fans going to the event.

<img src="{{site.basurl}}/assets/images/posts/ff-splash.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-map-1.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-map-2.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-chat.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-chats.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-forum.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-forum-going.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-gig-going.png" alt="fan finder" />
<img src="{{site.basurl}}/assets/images/posts/ff-gig-going-2.png" alt="fan finder" />


<br>

I worked on this with 3 other people as the last project of our bootcamp. We had no instructions on what to build or how, which was a great opportunity to challenge ourselves. It gave us the chance to work using an agile methodology and practice github workflows that aren't as important in solo projects. 

<br />

- [Front-end repo](https://github.com/Oliver1334/fanfinder-fe)
- [Back-end Repo](https://github.com/JJJUhlar/fanfinder_backend)

<br />

**Tech used:** React Native, Expo, Node.js, Express, MongoDB, Jest, Socket.io

<br />

### How we made it.
The total development time was only 9 days.

<br />

1. Days 1 to 3 were spent coming up with ideas for our project, and considering how we'd design the application and what kind of tech we would use. We spent a day and a half spiking anything we hadn't used before (including for example MongoDB, Firebase, Xcode) splitting the new tech up between us.
2. After settling on our MERN stack, we defined what an MVP could look like for us and set about making some wireframes.
3. A surprising amount of time was spent over the next 2 and a half days figuring out our development environment, and trying to get ahead of problems like how we would deploy Mongo.
4. Suddenly, all the boiler plate was down on the backend and we could start building out end-points.
5. Before we knew it, the basic screens and stacks of the app interface were laid out, meaning we could all work simultaneously on adding features on different branches.
5. We had a couple of days left to add some basic styling to the app to make it look nice.
7. Then we made a video showing what we did.

<br />

### Challenges / What we could have done differently
Mongo is interesting, but we probably shouldn't have used MongoDB.

<br />

Fickle, junior devs that we were, we were magnetically drawn to trying out a fancy sounding new database. Probably, we had seen job postings here and there looking for NoSql, and were more interested in adding another string to the bow than really thinking about designing great software. In theory, NoSQL databases can be useful for storing lots of unstructured, inconsistent data. In reality, we had an ideal situation for Postgres. We already knew that we would have consistent, perfectly rectangular data in every case. We knew that we would have to use location data. There are extensions that would have let us immediately query the db by the location instead of doing lots of awful.