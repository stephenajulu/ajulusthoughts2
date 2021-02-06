+++
authors = ["Stephen Ajulu"]
date = 2021-02-06T13:05:00Z
draft = true
excerpt = "Here we explain how The Noesis was built, why we made the choices we made during building and how you too can build a JAMstack website with ease"
hero = "/static/images/generative-social-image.png"
title = "How The Noesis Magazine Was Built"

+++
Hi, there? Today I'd like to show you how we built this magazine and how you build your own blog too.

### Problem: Platform

We didn't want to use WordPress due to it's complex nature and how hard it is to maintain. So we searched the web for a fast platform with a CMS and we landed upon Hugo. It was a fast and simple platform with support for [Headless CMS](https://blog.stephenajulu.com/post/building-a-beautiful-progressive-jamstack-blog-part-1-day-1-to-3/). So we set out to learn it. 

Our founder dabbled in it for 1 year for good measure bringing [_Ajulu's Thoughts v2_](https://blog.stephenajulu.com) into the JAMstack world. You can it here: [new blog](https://blog.stephenajulu.com)  and the [old one](https://ajulusthoughts.wordpress.com) here. Feel free to compare the difference in terms of UI, Speed and other factors.

After a year, we decided we had found our "ONE".

Immediately we started working on it. Tried a few iterations which failed miserably because they didn't met our standards and then we decided to use the same design as our founder's new [gem(blog)](https://blog.stephenajulu.com). After trying different designs(of the same base), we decided [this ](https://thenoesiske.netlify.app)would be it.

Since then we have added a lot of things that weren't in [Ajulu's Thoughts](https://blog.stephenajulu.com).

If you would like this same design use either Hugo's Port or The Original from Gatsby. The theme we use is called Novela by Narative.

### Solution: Hugo using Novela

### Problem: Writing and Editing

We now had our platform. We modified it and deployed it to [Netlify](https://netlify.com).

Now came another problem. Would we keep using code editors and git just to post and edit? What about the non dev writers? So we decided to we needed a better writing solution. Turns out the base we used had some code ready for us to use a CMS known as [Forestry](https://forestry.io). We quickly set it up and everything worked fine except that we weren't allowed to add more than 3 users in their free section and this is a non profit organization. We found a work around though and now have 6 writers in our midst.

### Solution: [Forestry CMS]()