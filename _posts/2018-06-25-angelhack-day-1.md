# Angelhack Day 1

On Saturday and Sunday I attended my first ever hackathon. I've been wondering how I can find other people who are interested in building things to solve problems. Maybe at a hackathon? So I started tracking hackathons a couple of weeks ago and signed up for Angelhack just the day before, once I knew it would fit with family plans.

What distinguishes Angelhack from some other hackathons is that you have to demo a working product. Slide decks are not allowed as an alternative. So it's not just about the idea. You actually have to build something that addresses the problem.

The day started officially at 9am. I was delayed and arrived at 9.50 by which time groups were already established. However I chatted to a few who were looking to do something VR-based. 

At 10am came the opening ceremony, sponsor welcomes, and team building from those looking for team members. 

## Sponsor Welcome

To focus the teams, there were various challenges:

* **AngelHack Challenge**: Challenge yourself and your entrepreneurial spirit. Make something innovative without limits, something that brings positive change to the world, even something that solves a small problem.
* **Code For A Cause Impact Award Challenge**: Build technology that solves a social or environmental problem and positively impacts your local community.
* **IBM Call for Code Challenge**: Get ready for Call for Code with this preliminary challenge to improve logistics based on traffic and weather activity. Create an application that helps build resilient communities, and safeguards the health and well-being of individuals and institutions, specifically in the context of a natural disaster.
* **AWS Challenge**: Challenge: Best Use of AWS Fargate.
* **Agora RTC App Challenge**: Build an app or Website that uses the Agora real-time-communications (RTC) platform. Use RTC to solve a real world problem, re-invent the future, or simply be creative!
* **Fitbit Challenge**: Create an app or clock face using the Fitbit OS SDK or Web APIs to empower and inspire users to live a healthier, more active life.
* **Consensys Challenge**: The Consensys prize will be awarded to the most inspiring project using Blockchain technology.

![Call for Code - Simon Baker]({{site.url}}/assets/call-for-code.png))

## Team Building

Team building involved people with ideas coming up to the front and pitching their ideas. 

The most interesting ideas for me were:

* The VR app (looking for Unity developers)
* An [app](https://helpific.com/) which brings together communities, particularly to help older people living alone
* Protecting children who are vulnerable to human trafficking using Blockchain

The Unity project wasn't a good fit for my experience. Of the other two idea I felt I contribute and learn the most in the team looking at human trafficking; there was a good balance of skills in the team, including previous hackathon experience. Our team was Viv, Van, Stella, Justin and me. 

Stella had pitched the original idea on human trafficking, and we talked about possible solutions. The most robust solution involved capturing biometric information from children in vulnerable villages early on so that they could be checked when travelling. We discussed how this might also apply to reuniting families after a natural disaster.  

The reliance on capturing data beforehand didn't seem practical in the context of our problem. So we began to focus more on a chatbot solution to guide information capture, along with an image matching feature. We also discovered during the day that Consensys had a [project](https://www.un.org/press/en/2018/pi2224.doc.htm) in progress working on this problem.

We settled on tackling the problem of reuniting familites more quickly after a disaster zone, addressing the IBM and Code for a Cause Challenges. 

## Prototyping

Justin had experience with the IBM platform and started building an image recognition service using IBM's Watson. 

Using Indonesia as an example. The population is around 260 million people. With slightly under half having smart phones. After a natural disaster electricity and telecommunications infrastructure will be affected, but [tactical](https://www.bbc.co.uk/news/business-34715962) [solutions](https://eu.usatoday.com/story/tech/columnist/baig/2018/03/16/hurricane-wipes-out-cell-phone-service-here-comes-200-pound-drone/419614002/) do exist.

Our basic journey was:

1. Parent texts relief agency
2. Agency chatbot requests information, such as child's name, village, date of birth and other helpful information, with a photo if possible
3. Photo is received and saved
4. Details are matched against any already saved
5. Chatbot responds to parent with next steps

I had some trial account limitations on IBM Cloud, and we had technical issues with the visual recognition service; my API key didn't work with the latest release of the API. However the IBM team on site helped to resolve that.

Food and drink was supplied throughout the day, and disappeared very quickly after it was put out. 

There were sessions throughout the day on different technologies, and presenting.

While Justin and I worked on the tech away from the hubbub in the main call, Viv and Van continued to explore the problem and possible solutions; we had a few sync-ups during the afternoon to check that we were building the right thing.

We got to the evening not having a completely coherent soltuion to the problem. Should we incorporate Blockchain somehow? Or AWS Fargate? We had the IBM Chatbot set up, and Watson image recognition. Could we add to that?

Recognising I needed to sleep, I left Rise around 11pm. Justin carried on. I had around 6 hours sleep, and was up at 6.30 on Sunday.

**Next**: [Day 2](/2018/06/26/angelhack-day-2.html)
