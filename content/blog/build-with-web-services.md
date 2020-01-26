---
title: "How to use web services to build awesome projects"
description: "Welcome to the world of infinite possibilities!"
author: "Pavle Neskovic"
cover: "https://images.unsplash.com/photo-1563262924-641a8b3d397f?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1350&q=80"
date: "2020-01-26"
type: "post"
---
Cloud computing enables you to use someone else computing services on-demand, over the internet. It has become a 27.5 billion dollar industry, with the big players like Amazon, Microsoft, Google fighting for the biggest piece of that cake. This article will give you an overview of what “the cloud” has to offer if you are building a project from scratch.

To start, let me explain what was there before the cloud.

## Ancient History: Before The Cloud

![](https://cdn-images-1.medium.com/max/800/1*vV8GE07MUkaev4GaRwGS0w.jpeg)

In the early 2000s, everyone had to own and maintain physical data centers and servers. That was fine, but it had its problems. If you had a few servers, when the crowd rushed to your website, it would break. Having too many was expensive and a waste of money if no one is using that capacity. You have to hire a team that is capable to maintain, manage and repair servers. Often, other teams were dedicated to maintaining databases and networks. Also, you wanted to make sure the whole thing is secure, which also costs you a lot of money. Wouldn’t it be great if we could have someone else manage all that and let us worry about the product we are trying to deliver?

_To The Rescue — Cloud Computing_

In 2006, AWS, a subsidiary of Amazon, launched its compute and storage web services, which created the opportunity to transfer all that hassle to them. Back then, most people weren’t comfortable giving their code and data to someone. That idea became more acceptable later, as more and more people started experimenting with it and realizing that it is cheaper and easier to rent someone else’s infrastructure, instead of maintaining it on-premise. Google, Microsoft, and IBM took a year or two, but they responded and created their cloud computing services. The shift started happening. More services appeared. The game was on.

## So, What’s In It For Me

Much has changed since the early 2000s. Cloud service providers are looking to satisfy every possible customer need. You can manage the infrastructure yourself (Infrastructure-as-a-Service, IaaS), or you can write code without worrying about underlying infrastructure (Platform-as-a-Service, Paas), or just use the services that are complete and do the job for you (Software-as-a-Service, Saas). Here is a [big aaS list of as-a-Service offerings](https://www.auvik.com/franklymsp/blog/aas-as-a-service-list/) to give you an idea of what are the possibilities. In the cloud, the prices grow only when you grow. As long as you don’t have a ton of requests, customers, gigabytes of data, most of the services are free. The servers can scale, incoming requests will never overload your servers. And you don’t have to have a bunch of teams to solve your infrastructure problems. That means that you can build complex apps all by yourself or as a part of one small team. Cheap, easy and fast. Let’s see how.

## What’s in store

![](https://cdn-images-1.medium.com/max/800/1*0UeW99Cx3XzE3g3ty53nGA.jpeg)

###   

They are many cloud providers that are providing cloud computing services. The largest ones are Google, Microsoft, and Amazon, but there are many more, competing in different areas of the industry. Many of them are made to be used in enterprise environments, but today we will focus on ones that can help you create an amazing project from scratch.

### Setup storage, authentication, analytics or hosting in minutes

You want to focus on your product, you don’t want to implement authentication again. Try Backend-as-a-Service. You can have all the functionalities of the backend done through simple configuration. [**Google Firebase**](https://firebase.google.com/) and [**AWS Amplify**](https://aws-amplify.github.io/) are examples of such a thing. You can configure storage, authentication, hosting, analytics in minutes and much more.

Firebase is really easy to use. The feature that I recommend the most is [Cloud Firestore](https://firebase.google.com/products/firestore/), because of its real-time data syncing, so you can build collaborative and realtime apps like Google Docs in no time.

A similar product to Firebase is the [AWS Amplify](https://aws-amplify.github.io/). It has the same features as Firebase and it gives you the ability to set up a continuous delivery and be online in couple of minutes. Also, it has UI components that can be easily integrated with Amplify backend.

If you need some custom business logic, both Firebase and Amplify support serverless functions, so you can manipulate your data or integrate with some third-party software. And the best thing about both services is that they are modular. If you need only datastore or only authentication as a service, you can use only that, but the real power comes when you use the most of it.

### Expand the base of the app with cool features

From here, there are so many things you can do. Here are the couple of things that you can integrate into your app:

**Send emails** to your customers or do anything with emails, consider using [Mailchimp](https://mailchimp.com/). You can easily create mail templates and target a large number of people. Or if you want to send SMS messages or make programmable phone calls you can try [Twillio](https://www.twilio.com/).

**Integrate payments** in your workflow, by using [Stripe](https://stripe.com/) or [Braintree](https://www.braintreepayments.com/).

**Public services** like [weather information](https://openweathermap.org/), [currency exchange](https://fixer.io/) or even [nearby asteroid location](https://api.nasa.gov/).

**Artificial Intelligence/Machine Learning** offers us so many cool things that we could do. Here is the list of some services that you will probably find by searching through [Azure](https://azure.microsoft.com/en-us/free/ai/), [Google](https://firebase.google.com/products/ml-kit), [Amazon](https://aws-amplify.github.io/docs/js/predictions), or even [IBM Watson](https://www.ibm.com/watson/products-services) (which is relatively easy to configure, btw):

-   Translating
-   Converting text to speech
-   Text recognition from image
-   Entities recognition
-   Label real-world objects in real-time
-   Interpretation of text
-   Uploading images for automatic training
-   Transcribing text
-   Faces detection
-   Barcode scanning
-   Landmarks recognition
-   Relevant (smart) replies to messages generation
-   Chatbots

**Interact and analyze social media** by integrating with their APIs or SDKs. [LinkedIn](https://www.linkedin.com/developers/), [Instagram](https://developers.facebook.com/products/instagram/), [Facebook](https://developers.facebook.com/), [Twitter](https://developer.twitter.com/), [YouTube](https://developers.google.com/youtube) can give you access to their content. Have in mind that social media is very rigorous when it comes to misusing their services. You may need to go through a review process of your application in order to use their web services.

**Have maps** in your app. Most commonly used maps are Google Maps, but there are other alternatives like [Here](https://developer.here.com/), [MapBox](https://www.mapbox.com/) or [Bing Maps](https://www.microsoft.com/en-us/maps/choose-your-bing-maps-api).

  

## All you need is the idea

There is a huge number of examples online that will show you how to integrate all services that bring your idea to life. I’m hoping this will get you motivated to build something awesome. Good luck on your adventures!