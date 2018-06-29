---
title:  "Hacking vs Engineering"
---

After [Angelhack](https://andrewwhitehouse.com/2018/06/26/angelhack-day-2.html) I've been reflecting on the different technical skills needed in a hackathon, versus those I use in my day job as a software engineer. So I'm thinking about hacking (meaning experimenting, and combining things) versus engineering.

(My uncle is a chemical engineer, and he would argue that it shouldn't be called software _engineering_ but that's a discussion for another day.)

**Engineering**

Good software engineering teams build software with a focus on creating value for the business. They also put systems in place to minimise the cost of change. This starts with taking care to identify the requirement, then building the simplest thing that meets that requirement. Over-engineering a feature creates more code which is more likely to have bugs, and is more difficult for the team to understand. And the team will change over time, so new hires will have to start again.

Minimising the cost of change means that there must be repeatable (automated) processes to build and test the software. Manual testing by humans is really slow and difficult to replicate.

When consulting/off-shoring companies become involved in software delivery there is tension to create profit while not overcharging the customer. In my experience this can lead to a short-term focus. And the practices that lead to longer term consistency and maintainability receive lower priority. Over time this leads to lower software quality. If the customer paid the consulting party to build and run the production system, that might encourage a greater focus on maintainability.

There are companies who build in the engineering from the start, creating an asset that will be maintainable in the long term. I've worked with a couple of them. It takes clear priorities and experience to minimise entropy as the software changes over time.

Good developers treat what they do as a [craft](https://en.wikipedia.org/wiki/Software_craftsmanship). 

At Chordiant, where I worked in the early 2000s, I was occasionally seconded from the professional services team the pre-sales team. The goal of the pre-sales team is to build demo-able software; so they can show something concrete to a potential client and illustrate how it solves their businesses problem. There is usually limited time to build the demo, and so the result is a constrained set of functionality which may work for only a couple of customers and while the UI looks like a full product only certain features have been enabled.

**Hacking**

This focus on the demo makes pre-sales work much closer to the hackathon, although in the hackathon you don't have the option to co-opt code from your colleagues.

In Angelhack some teams produced narrowly focused apps. Our team chose a problem which required a system. And now I'm thinking about reusable components to build a system. To test a hypotheis with much less effort than a carefully engineering solution. Because what we're doing is identify problems and testing solutions. If we can do it in a way that is sufficiently maintainable for the lifetime of the software then that's a good result. 

Tension comes when you prove your hypothesis, and transition from an early prototype that's cobbled together but isn't easily maintainable. That makes the cost of change expensive. So do you spend time working on that, or delivering new features? Once people know about your product, it's the ability to execute and deliver new features that matters.

I discovered [IBM Code](https://developer.ibm.com/code/) at the hackathon and it's an amazing resource of Open Source code that you can use to kick-start your project. 

Here are the projects on the first page:

* [Create and deploy a blockchain network using Hyperledger Fabric SDK Java](https://developer.ibm.com/code/patterns/create-and-deploy-a-blockchain-network-using-hyperledger-fabric-sdk-java/)
* [Implement asset securitization on a blockchain ledger](https://developer.ibm.com/code/patterns/implement-asset-securitization-on-a-blockchain-ledger/)
* [Retrieve client insights for wealth management companies](Retrieve client insights for wealth management companies) using Jupyter and Python
* Understand customer interests with clickstream analysis
* Create a dynamic indoor map in an iOS app
* Analyze bank marketing data using XGBoost to gain insights into client purchases
* Analyze product reviews and generate a shopping guide
* Interacting with a blockchain network
* Leverage blockchain monitoring
* Use MQTT to stream real-time data
* Create an Android app with Blockchain integration
* Take corrective actions at the edge based on predictive analytics of IoT sensor data
* Create a customer loyalty program with blockchain
* Build an iOS game powered by Core ML and Watson Visual Recognition
* Deliver optimized, personalized search results

If you are a developer, in addition to finding a template project that may meet your need, you can also use these examples to give focus on technologies that are worth learning well enough so that you can customise what's there.

[Smart people should build things](http://www.smartpeopleshouldbuildthings.com/).

Here's Paul Graham's 2003 essay on [Hackers and Painters](http://www.paulgraham.com/hp.html).
