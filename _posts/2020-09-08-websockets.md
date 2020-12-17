---
layout: post
title: "So my project development begins..."
author: "Shrinidhi"
categories: blog
---

### Websockets

The issue is not so much about the actual protocol but about the technologies implementing them. I began with AWS Lambda and got stuck at basically every turn due to the limited library support and god its so confusing for my usecase.

Now I changed gears and moved on to asp.net core on an EC2 instance under free tier. Having one place is much easier to manage all the dependencies. 

But that is not without its issues thought. Microsoft documentations are difficult to follow at times and there are no good code examples for this.

My best bet is finding and going through one tutorial and see where that brings me.

### Domains live!

All that said, I am quite excited with the current progress that has been made along the architectural lines. I purchased my first ever domain for the cloud manager so all graffers can use one specific URL. But later figured I can use this to publish an entire website showcasing the IoT access hub. It is named after my dad. 

Stub name of the psudeo company :: "Svasa Technologies"

URL :: [https://svasa.tech/](https://svasa.tech/)

And yes it has SSL too. Thanks letsencrypt.

### Will be right back

Will complete the sockets thingy today. After that I have to implement the graffer to test. Then the APIs for agent to access them. And also think about how to link agents with graffers.
