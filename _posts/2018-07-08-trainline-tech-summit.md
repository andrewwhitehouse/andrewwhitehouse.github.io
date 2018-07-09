---
title:  "The Trainline Tech Summit"
---

Friday was the Trainline Tech Summit where those of us working in the engineering team got together to share ideas and learn from one another.

I came away from this with a greater appreciation for the work that has gone into building a strong culture at the Trainline, and was also really pleased to meet colleagues who I wouldn't normally interact with.

**Project Extend**

[Glenn Block](https://twitter.com/gblock?lang=en), of Auth0, flew in to talk about Serverless extensibility. Many services now provide [web hooks](http://progrium.com/blog/2007/05/03/web-hooks-to-revolutionize-the-web/) which give their customers the ability to extend the service. For example, using a Slack commands to run your deployments. 

You give the end user the ability to write small bits of code to customise their product, using events as the hook points for extensibility.

And you can do the customiation inline. Often with JavaScript. (We need to learn JavaScript, people!)

Auth0's Extend is an embedded white-label editor.

You can find out more about project extend [here](https://goextend.io/docs/getting-started).

**Sight Reading Code**

[David Whitney](http://davidwhitney.co.uk/) talked about [literate programming](https://en.wikipedia.org/wiki/Literate_programming) and the signs he looks for when reading code to decide how good it is.

How well does the code communicate its intent?

Code should be optimised for readability.

If you write tests for the Game of Life, it's really helpful if the code look like the thing they're representing.

Being able to read and adapt a codebase on the fly is like sight reading. Good software is inherently consistent, and has consistent naming. 

David has a five minute shit filter for open source.

Bloated files obscure intent. 

Unnecessary abstractions create weight, and are a common issue for coders 5 years into their career.

Likewise, a one-for-one pass (e.g. from one class to another) has the effect of renaming concepts. 

Passing primitives around suggests the author hasn't given enough thought to the concepts in the code.

Excessive constructor overloading brings in unnecessary dependencies and violates the Single Responsibility Principle. 

Find the largest file, then zoom out and look for repetition. If it's there, it shows the author hasn't taken care to refactor. (This is either a sign that the author doesn't care about readability or, as I've seen in previous projects, the code isn't well understood enough and/or has poor test coverage which makes it risky to refactor.)

Dead commented code blocks tell me you don't understand source control. 

If you don't keep your software versions up to date and fresh that tells me about the way you maintain your code. 

Also look for non-obvious changes. Read commit logs. Look at frequent change hot spots. Do you have squashed commits? What are you embarrassed about?

Links:

* [Obvious Architecture](http://retromocha.com/obvious/#intro)
* [12 Factor Apps](https://12factor.net/)
* [Screaming Architecture](https://8thlight.com/blog/uncle-bob/2011/09/30/Screaming-Architecture.html)
* [Innovation Tokens](http://mcfunley.com/choose-boring-technology)
* [Your Code as a Crime Scene](https://pragprog.com/book/atcrime/your-code-as-a-crime-scene)

**Optimal Team Design**

Ian Randolph gave an excellent talk on optimal team design. I was too busy listening to take detailed notes.

Team building happens everywhere.

We live as if assumptions are true, but we don't investigate them. We can look at behavioural goals (e.g. work collaboratively as a team), and contrary behaviours (throwing work over the fence, blaming others then the work they throw over the fence isn't perfect). Then consider worries (looking incompetent of being wrong, or being blamed when failure happens). And consider hidden commitments (looking and feeling competent and right, avoiding blame for failure), leading to big assumptions (If I don't look competent, I'll get fired; my boss doesn't tolerate failure).

Ian talked about the work that Google has done, and the five [keys](https://rework.withgoogle.com/blog/five-keys-to-a-successful-google-team/) to a successful team.

Safety in a team = trust between team members.

Trust = competence x reliabilty x motive.

trust = I honour my word
motive = we value the same thing
competency = my ability to do my job

Links:

* [How to change culture and take your transformation to the next level](https://skillsmatter.com/skillscasts/11931-how-to-change-culture-and-take-your-transformation-to-the-next-level)

**How to Have a Good Day**

I wasn't expecting to see a talk on [Stoic philosophy](https://www.amazon.com/dp/B07464C6CP) but Rob Cooper incorporated this into another excellent talk about how to have a good day.

He covered meditation, gratitude, visualisation and exercise.

The goal of visualisation is to have a really detailed plan of what you want to happen today and prime your brain not to think.
 
You're only in control of your thoughts and actions.

Give yourslef time and space. Rob does quarterly and monthly reviews.

Create a bucket list. Sign up for cool stuff to do, and add to your list. Include a mix of things that are easy and hard to do. For example, go to space, ride an ostrich.

Recommendation: [How to Have a Good Day](https://www.amazon.co.uk/dp/B00ZCCX55I/)

As I had a long talk with Rob about the books he's read I missed the beginning of the next talk ...

**Remote Teams**

Nisha Chaganlal talked about the challenges of remote teams. I've been the only remote worker in a team before, and if the details aren't taken care of it can make doing the job much harder.

How we do sabotage remote teams?

* Hire people that are not a fit
* We use timezones as an excuse
* We have side conversations (excluding the remote workers)
* We are not mindful of our remote colleagues
* We don't capture decisions that impact the entire team
* We forget about team building
* We ignore people on Slack
* We don't add a call/Skype link to all meeting invites
* We only text people
* We don't have areas in the office to connect to remote teams

**Mark Holt - Custodi Detractione**

Mark, Trainline's CTO, talked about his beliefs and values. 

Success is a function of culture, people and processes.

> There is nothing so useless as doing efficiently, that which should not be done at all -- Peter Drucker

The shortest story every written:

> For sale, baby shoes, never worn -- Ernest Hemingway.

It's almost all about the people.

Creativity is a function of diversity.

Mark's philosophy is to hire people who:

* Have great energy and attitude
* Get shit done
* Love what they do
* Abstract and simplify
* Are different / diverse
* Make beautiful things
* See the whole
* Learn; and Teach

> People join a company, and leave a manager.

Celebrate (and talk about) your successes.

Hire great people, facilitate great process, encourage the right culture. And then get the hell out of the way.

Hire people who make up for your shortcomings; and those of your team.




