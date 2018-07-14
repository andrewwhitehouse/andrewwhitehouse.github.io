---
title:  "Ethics in Technology, Part 1"
---

On 13th July I attended the [Coed:Ethics](https://www.coedethics.org/) conference, organised by [Ann Currie](https://twitter.com/anne_e_currie?lang=en) and her team. This was the first conference of its kind about ethics.

Ann posed these questions to those of us who write software for a living:

* Is there a problem with ethics?
* What can I as a software engineer do about it?
* What might stop me from doing that?
* What might get in my way?
* And how might I get over that?

Ethics was the second-most highly rated [track](https://qconlondon.com/ln2018/london2018/track/tech-ethics-action.html) at QCon London 2018, so this is clearly and area that is reasonating more and more with our community.

The conference will be taped and featured on [InfoQ](https://www.infoq.com/articles/data-ethics).

I'm going to cover the first talk here, which involves the most egregious use of technology.

## Cori Crider: When Data Kills

[Cori](https://twitter.com/cori_crider) is a human rights lawyer, which means she flies to odd places around the world and talk to people about what happened to them. Some of the people she's spoken to have lost loved ones and community friends because of algorithms. 

Cori told us the story of Faisal bin Ali Jaber. In 2012 Faisal’s brother-in-law and nephew were killed, along with 3 others, in a drone strike.

![Faisal bin Ali Jaber]({{site.url}}/assets/faisal-bin-ali-jaber.png)

Salem bin Ali Jabar was Faisal's brother-in-law. He made a name for himself preaching against extremism and Al Qaida. Salem tried to steer young people away from militancy. This [article](https://www.independent.co.uk/news/world/americas/family-of-us-drone-stike-victims-files-lawsuit-demanding-president-obama-apologise-for-killings-10305690.html) elaborates. Salem and Waleed, the village's police officer, were likely killed because of some people they'd met.

![Yemen Drone Strike 2012]({{site.url}}/assets/yemen-drone-strike-2012.png)

This picture is from a hard drive that Faisal gave to Cori, and which he said he was happy for her to share.

President Obama approved not only _personality_ strikes aimed at named, high-value terrorists, but also [_signature_ strikes]((https://www.nytimes.com/2012/05/29/world/obamas-leadership-in-war-on-al-qaeda.html?hp&_r=0&pagewanted=all)) that targeted training camps and suspicious compounds in areas controlled by militants. Those ordering these strikes do not always know who they are killing.

![Michael Hayden]({{site.url}}/assets/michael-hayden.png)

Michael Hayden, former director of the NSA stated on record that "we kill people based on metadata".

In 2012 the NSA used machine learning to find couriers ... people who transmit messages. The number one target was an [Al Jazeera journalist](https://www.theguardian.com/media/greenslade/2015/may/11/nsa-labelled-al-jazeera-journalist-as-suspected-terrorist) ... if he's any good at his job, he's going to be speaking with militants.

In a later review of drone strikes in Syria, CIA briefers explained to Trump that they had waited so that wives and children could move out of the way. Trump's response was to shout and berate them: "[why did you wait](https://www.independent.co.uk/news/world/americas/donald-trump-cia-drone-strike-generals-war-isis-iraq-syria-afghanistan-middle-east-a8291306.html)?".

The focus on killer robots skips over the problem we already have today.

Cori says:
> So when we talk about the impacts of a technology, I think we first need to define the problem correctly. This is partly about code. But I don't think it's all about code. It's about how humans use that code, and why. The CIA and special forces like algorithmic targeting because placing human source in terror networks is slow, it's expensive. And it's risky. But there isn't always a shortcut and there isn't always a neat technical solution to a political problem like terrorism. A CIA officer said something about the drone programme. He said "We're killing these sons of bitches faster than we can grow them". But he was wrong, for the reasons that Stanley McKristol explained. For every one person they've taken out, you have three people to take their place. Al Qaeda in Yemen got bigger by several fold during the drone wars.

**So what can software developers do?**

When deciding what to work, on:

- Know your power, because you're the people building the features
- Negotiate your work, not just your cash
- Ask questions
- Get help; talk to lawyers like Cori, people with ethical backgrounds. 

The issues you work on are a matter for contractual debate.

Ask: Have I been told the whole story? What kind of risks am I running? Some risks are moral. But some are legal too. Programmers at Volkswagen went to prison beause they helped cheat emissions tests.

Ask people who aren't necessarily involved in tech. Find out how their lives are affected.

It only takes a relatively small movement to create change; Google ended its involvement in project Maven (although they've said they'll still contract with the military) after 4% of its employees [signed an open letter](https://www.nytimes.com/2018/04/04/technology/google-letter-ceo-pentagon-project.html) and protested.

Cori ended on a optimistic note:

> It feels to me that tech employees may be starting to recognise that there is a moral and political element to the work that they do. And if that's right, I think the Maven debate is part of a larger trend.

> Developers have way more power than you realise. You're a hot commodity. And I think perhaps once you demand it, companies will come up with a better offer for you. I don't think you can just negotiate for a better salary. I think that the projects you individually or collectively work on are a matter for contractual debate. I also think that you can and should ask questions. What am I really building? Who is in our supply chain? Could this piece of software be used differently from how it seems it will be used?


> With the right approach and people asking the right questions, maybe somebody will be coming up here and addressing you next year about how AI saved some lives in Yemen because of a medical project or somebody used AI to find discrimination and stop it in a bank's lending or hiring practices. I think if we combine all of our technical imaginations with a bit of moral imagination, the sky really is the limit.


_There's another post to follow, covering the remainder of the Coed Ethics conference._











