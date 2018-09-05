---
title:  "Ethics in Technology, Part 2"
---

[_I originally started writing this post on 19th July, and didn't complete it before I started on the altMBA. I'm still posting belatedly because it's important that we as software professionals think about these issues. The advantage of completing this now is that the talks have now started appearing on [InfoQ](https://www.infoq.com/coed-ethics)._]

On Friday [13th July] I attended the [CoedEthics](https://www.coedethics.org/#band-section) [conference](https://www.coedethics.org/conference2018), organised by Ann Currie and her team. This was the first conference of its kind about ethics.

To recap, Ann posed these questions to those of us who write software for a living:

* Is there a problem with ethics?
* What can I as a software engineer do about it?
* What might stop me from doing that?
* What might get in my way?
* And how might I get over that?

I wrote about Cori Crider's talk previously [[InfoQ](https://www.infoq.com/presentations/big-data-kills)].

[Caitlin McDonald](https://twitter.com/cmcd_phd) talked about being a **Data Citizen** and the [Data Ethics Canvas](https://theodi.org/article/data-ethics-canvas) that can be injected into the work that we do. Government Digital Services has also released a [Data Science Ethical Framework](https://gds.blog.gov.uk/2017/11/27/updating-the-data-science-ethical-framework/).

Caitlin referenced Cathy O'Neill's book [Weapons of Math Destruction](https://weaponsofmathdestructionbook.com/) which talks about the impact of algorithms that on modern life, which lack transparency.

Caitlin draws parallels between how citizens interact with the law, and how data citizens interact with data science. _How can we as data citizens push for more effective and fair data science, which impacts us?_ A first step might be insisting on the same level of transparency for ethical data practices in data science as there are in law.

You have to [treat data like people](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005399), because most metadata is about people.

Caitlin's talk is [available on InfoQ](https://www.infoq.com/presentations/big-data-ethics).

**Data Science in Action**: Emma Prest and Clare Kiching talked about [Data Kind UK's](https://gds.blog.gov.uk/2017/11/27/updating-the-data-science-ethical-framework/) work. Data Kind is a charity that does pro bono data science work for good.

What can happen when you start off with the best of intentions?

An app to track potholes can lead to potholes being fixed in richer areas only because residents have smartphones. The Samaritans' Radar app was launched with the intention of helping users who were posting tweets that suggested suicidal thoughts; it was [suspended](https://www.theguardian.com/society/2014/nov/07/samaritans-radar-app-suicide-watch-privacy-twitter-users) following privacy concerns.

When starting a project:

1. Embed ethics discussions in your project process: at kick-off, discussing data and results, planning implementation

2. Involve a diverse range of people: client, data scientists, developers, users to get a fuller picture of the context and risks. Data scientists are never experts in the subject matter. And the users ... bring them in earlier.

3. Think about explanability. Will your clients be able to understand the model and explain decisions to end users?

4. Project intent matters. But also consider the unexpected consequences.

[[InfoQ link](https://www.infoq.com/presentations/ethics-data-science)] for Emma and Clare's talk.

[Andrea Dobson](https://twitter.com/andrea_kock?lang=en)'s topic was **Ethics: A psychological perspective**. 

Why do good people make bad decision?

If you have to report an ethical issue would you prefer to conform to the rest of the group?

In less clear situations, levels of conformity increase.

In 1997 a Korean Air flight [crashed](https://news.nationalgeographic.com/news/2013/07/130709-asiana-flight-214-crash-korean-airlines-culture-outliers/), killing 223 people because the co-pilot was afraid to question the poor judgement of the pilot.

Andrea talked about [Milgram's experiment](https://en.wikipedia.org/wiki/Milgram_experiment) and the notion of psychological safety, which allows people to feel able to speak up.

Here's Amy Edmondson on _Building a psychologically safe workplace_.

<iframe width="560" height="315" src="https://www.youtube.com/embed/LhoLuui9gX8" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[Yanqing Cheng](https://twitter.com/YanqingCheng) [(InfoQ)](https://www.infoq.com/profile/Yanqing-Cheng) asked _Why do we care about ethics?_  We care about ethics because we want the world to be a better place. What makes the world a better place?

Many of us create technology with positive impact. 

What makes the world better but doesn't feel morally good?

Human intuitions don't scale ... we can do a huge amount of good but becuase of [scope insensitivity bias](https://www.lesswrong.com/posts/2ftJ38y9SRBCBsCzy/scope-insensitivity) we don't feel good enough about doing it. 

How can we use limited resources to help others most effectively? How can charities use their resources in the most effective way?

The UK's National Institute of Clinical Excellence uses a unit of measurement called the QALY - the "quality-adjusted life year". The NHS is prepared to spend [£20,000 per QALY](https://www.bbc.co.uk/news/health-28983924).

Malaria is no longer the leading killer of people in Afria due to mosquito nets.

The most effective actions are not always the most intuitive.

[No Lean Season](https://www.givewell.org/charities/no-lean-season) provides low interest loans to rural workers in Bangladesh so they can buy a bus ticket, travel to Dhaka and work there as a rickshaw driver.

So how do you maximise the effect of your personal donations? (Look at [Giving What We Can](https://www.givingwhatwecan.org/) and [GiveWell](https://www.givewell.org/).)

Prioritise good actions at scale.

Responsibility means:
- think once, then think twice (on whether your biases are affecting the sitaution) and think hard
- focus on what you (personally) can do
- have courage
- remember that you have the power

**Harry Trimble Power, ethics and design education**

[projectsbyif.com](https://projectsbyif.com/).

It's getting harder to tell design and software developmnt apart.

Richard Pope: _[Software is politics](https://www.fastcompany.com/3066631/software-is-politics) now_. Because software is power.

Today so much power in society lies with designing and building software.

Read Stephen McCarthy's post _[Designers as power brokers](https://medium.com/@loft27design/designers-as-power-brokers-403338d79361)_.

Design is a position of power. Designers need to reconigse the power relationships in the things they build.

Read George Aye [_Design Education's Big Gap: Understanding the Role of Power_](https://medium.com/greater-good-studio/design-educations-big-gap-understanding-the-role-of-power-1ee1756b7f08).

[Open APIs in the telecoms sector](https://medium.com/greater-good-studio/design-educations-big-gap-understanding-the-role-of-power-1ee1756b7f08) could create powerful new services.

The [Data Permissions Catalogue](https://catalogue.projectsbyif.com/) has a number of different patterns for the sharing of data. 

Examples:

* [Verifiable Proof](https://catalogue.projectsbyif.com/patterns/verifiable-proof)
* [Proximity Sharing](https://catalogue.projectsbyif.com/patterns/proximity-sharing)
* [Decision Testing](https://catalogue.projectsbyif.com/patterns/decision-testing)

**A Responsible Development Process**

Adam Sandor of Container Solutions, and [Sam Brown](https://twitter.com/samcatbrown) of [Doteveryone](https://doteveryone.org.uk/) discussed embedding ethics into the development process through the [3C model](https://medium.com/doteveryone/a-model-to-help-tech-companies-make-responsible-technology-a-reality-837c50713c65).

Links:

* [Adam's QCon talks]([QCon talks](https://qconlondon.com/speakers/adam-sandor))
* InfoQ [article](https://www.infoq.com/articles/developers-tech-ethics) featuring Adam and Anne Currie

Developers and product owners have the power. We can create things out of nothing.

_But how do you know what to do?_

Responsible Technology considers the social impact it creates and seeks to understand and minimise its potential unintended consequecnes.

Responsible technologies:

- Do not knowingly create or deepen existing inequalities
- Recohgnise and respect dignity and rights
- Give people confidence and trust in thei use

This is not an ethical bible, but guidelines for responsible use.

**Mitsuku**

[Steve Worswick](https://medium.com/@steve.worswick/ethics-and-chatbots-55ea2a79d1a0) told us about [Mitsuku](https://www.pandorabots.com/mitsuku/), the chatbot he created.

Traffic ranges from 20 visits per day, to 2000 per hour.

He started entering chatbot competitions in 2010, and in the first year placed higher than Siri (which was 14th).

The only places that don't yet interact with Mitsuku are the South Pole and North Korea.

Because it talks to so many people he has to keep it child friendly. It's designed for general chit-chat.

Supervised learning is very time-consuming. But unsupervised learning can produce [poor results](https://www.npr.org/2016/03/27/472067221/internet-trolls-turn-a-computer-into-a-nazi). 

Mitsuku's does have attackers. They try to corrupt it but because of the supervised learning method the haven't succeeded so far.

A weak response from the chatbot encourages a bullying-victim interaction. So find a middle ground. He does this by issuing a warning system. you get 5 strikes and then you're banned (IP address) for 24 hours.

If you're mean to the bot, the bot will be mean to you. This is a fairly human trait.

It Mitsuku learns something she learns it only for the user who's chatting.

Steve looked at a pattern matching bot, which is expensive to maintain but effective and predictable. NLP bots tend to be fairly unpredictable. The bot uses a language called AIML which is derided by others, but he shows them his medals.

We shouldn't personify robots ... they're machines.

Topic-specific bots tend to be more focused - there are roughly 10,000 ways to ask for a pizza. Mitsuku has 350,000 intents.

Links:

* [Pandorabots](https://home.pandorabots.com/en/)
* [Survey on Chatbot Design Techniques](https://thesai.org/Downloads/Volume6No7/Paper_12-Survey_on_Chatbot_Design_Techniques_in_Speech_Conversation_Systems.pdf)


In summing up, Ann reflected how how we can build psychological safety into our workplaces. 

Facebook would like us to believe that its decisions are deliberate, but they probably aren't. 

What do you measure? How can you allow for unpredictable outcomes? And be deliberate about the ethical choices ou make.

There are three aspects to policing ethics in tech:

* The law
* Educating users
* Tech companies - getting Google/Apple to buy in

Additionally, power comes from us techies.

In June 2018, Baroness Buscombe stated that the behaviour of AI and ML systems will be [covered by existing Health and Safety legislation](https://www.parliament.uk/business/publications/written-questions-answers-statements/written-question/Lords/2018-05-23/HL8200/).

For further reading, look at the _Resources_ and _Press_ sections on the [Coed:Ethics home page](https://www.coedethics.org/).









