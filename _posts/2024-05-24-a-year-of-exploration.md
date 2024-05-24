---
layout: post
title: "A Year of Exploration"
date: 2024-05-24
---

# A year of exploration

Began on July 1, 2023

> I thought because I’d seen the investor side for a year, that it would be easy to complete the playbook. I was wrong.
> 

## Sustainable Shopping

For the first several months I spun my wheels and went nowhere. I stayed on a bad idea for far too long, was afraid to talk to customers, and didn’t actually commit to any one idea. 

This was the sustainable shopping idea - I unfortunately didn’t document this part of the story well.

The insight I developed from my own experience and from talking to lots of consumers over the years was this: consumers are demanding more on the sustainability front from their vendors, but vendors suck at delivering this information. If I can bridge that gap, I can solve a consumer need. 

Within the first few weeks, I learned everything I needed to kill the idea. Brands were going to capture all the value, virtue signaling and green washing were huge trust headwinds in the industry, and perhaps most importantly, this was a tar pit idea — an idea that a lot of people have tried but failed to do. 

I wasn’t able to move quickly and kill this idea because my own ego got in the way. I was convinced I had a great idea, and wanted to see that idea through to prove that I, too, could start a company with my own idea. I was too attached to the idea of success vs. actual success. The key symptom of that, in hindsight, was a lack of desire to act on information, and instead to spend my time doing more and more research to reinforce my own ideas. 

I wrote a lot of documents backing my ideas, like [this](https://docs.google.com/document/d/1MfMtFRTjDGZS6nLP1YFzmGeJNcmTKIjdBUWM3tJZBWo/edit), [this](https://docs.google.com/document/d/1HepxVKHvAYVjoj4mHBEQ91jGeW-5k9Kumc8bqqf0CQE/edit), and [this](https://docs.google.com/document/d/1dnZQc6XYdgoKlRjIF39ZCPJuR9CEOamAv2XHtR3z9-U/edit). Came up with plans, but never executed, like [this](https://docs.google.com/document/d/17DZIl0fHXCJArAL48mKRcLBaMhJLDHOmsb-nhE2cHBA/edit). Wrote down some thoughts as well, mostly [here](https://docs.google.com/document/d/1BbAGFw93XFVh-CcH8qO6znbYi11-z4vKFm9p_wdyJlY/edit). All this info turned into nothing because I wasn’t willing to commit. 

It took me a long time to give up this idea, but I finally did after taking a lot of time off to sail the 5o5 world championships in September, then taking a long vacation in Japan —> Hawaii —> Mexico —> Florida —> Argentina from November to mid Jan 2024, I decided to kill this idea and move on to something that I thought was a deeper level of insight. 

Sustainable shopping was killed because brands capture most of the value, people don’t need discovery tools, and most customers were either already educated, or they didn’t care enough. 

## Reviews Bot

One key insight I carried over from sustainable shopping was this: people *don’t* trust brands, but the *do* trust other consumers. This means reviews are a valuable tool for establishing trust. 

I thought, and I was right, that it would be relatively trivial to snag reviews for products on Amazon, spin up a custom GPT or assistant API, and answer any very specific user questions about the product using the reviews as source material. It turns out, a company was doing basically this already called [Gigabrain](https://www.notion.so/Quantum-Computing-99b18796717f431f8dcc80eedbdc53be?pvs=21). They were using the reddit API. I thought I could compete with them using a whatsapp bot, and I could, I shipped a bot that worked! But nobody wanted to use it. It turns out that despite my correct insight: people trust reviews more than brands — the real insight was: people want to do less work, not more. This is generalized of course. 

I moved faster this time, and killed the idea in three weeks. I built the reviews bot and when nobody used it, I moved on. Scraping all that info is hard, and the value to the consumer was not worth the cost. Circa mid jan, 24.

I did apply with this idea to the SPC Founder Fellowship - here’s the [doc](https://docs.google.com/document/d/1q6TNsovNilxggyAcvR4iBhhbJH67ESAxRbukqCNvH30/edit#heading=h.ft8qz9ru5l30) I prepped with most of the info. I also had created a product that worked using Google Sheets as a backend with a lot of Zapier automations. Pretty cool to see what could be done with no code, but still wasn’t a product. 

## Social Commerce

Not much here, but I did a cofounder sprint with someone helping them build a social commerce tool. I thought social commerce was a bad idea after my friend Avi Fein pivoted away from it. I tried to convince this cofounder to go a different direction instead, but he’s still stuck now in the same old place two months later… anyways, failed team that took 2 weeks of my time away. 

## High Consideration Search

Convinced that I still had valuable insight in the industry, I wanted to stay in commerce. So I started to solve another personal problem of mine: search for complex queries. This time, I asked a lot of other folks what their recent purchasing woes were, and I discovered a collective problem: when the consumer query is complex, index search is no longer an effective tool. Instead, people were trying to use ChatGPT to help them find things like couches, tables, wedding venues, hotels… things that have a high subjective element, and that people have specific tastes for. 

So I went about building this during the month of February. I started with my own problem - finding a wedding venue for Isabelle and I. We wanted to buy out a boutique hotel somewhere abroad that had some specific requirements. Housed x number of people, had y aesthetic, etc. 

I learned a lot about embedding models and about semantic search. It turns out semantic search + LLMs was a really good combo for understanding the ‘vibe’ that a person was looking for in their search. I was able to build an MVP on streamlit using Abhay’s help and show it around to several folks. This time, the response was positive. People were hearing about the tool and asking to use it, when they were using it they gave very engaged feedback and seemed to get value from it. 

Most of the documentation for this project can be found [here](https://www.notion.so/72fb9db7790946c987e8b48d29a381f6?pvs=21), mainly under Zoe, and some writing [here](https://www.notion.so/Consumer-Journey-Tool-Layering-980e6be916dd49c69ea57945ee893233?pvs=21).

It wasn’t on par with what you need from consumer products though. It solved a minor inconvenience, not a huge problem. So in the end, while it was a successful MVP, the value delivered to consumers wasn’t enough to overcome the difficulty and cost of scraping so much broad information. For this reason, I killed high consideration search. 

It was around this time that I started to be much more serious about finding a cofounder. I got introduced to a friend of a friend who has a technical background from the company Weights and Biases. We did a two week sprint to come to the conclusion above, but he wanted to keep working on it by himself. 

## Generative UI for Marketers

I put together a hackathon team to build a generative UI tool for marketers. The idea was to let LLMs do infinite A/B testing by generating UI elements including copy and styling. This idea is pretty self explanatory, we built a very basic MVP during the hackathon which I used to try and get LOIs from marketers. I was actually decently successful, no LOIs but some interest in design partnership. 

I met a team building this in a more focused way called [Keak](http://keak.com). I considered investing in them, or competing with them, but eventually learned that the market for this type of tool really isn’t that large anyways. Despite some interest in design partnership for this product, I couldn’t reach conviction that firms would pay more than $1k per year for the product, which was not enough to make it venture backable.  

Important for the future, the marketers I interviewed primarily reported that their biggest pain was either BI headcount, or attribution. 

Most of the documentation for this product can be found [here](https://www.notion.so/Mal-Mango-0a60b399315347968f1cdb835a6b522f?pvs=21). Which includes a [deck](https://gamma.app/docs/MANGO-qfcnfbkv0nw4w0f), within which there are demo videos. 

While I was looking for LOIs in mid march, I met a team from Stitch Fix that was working on iterative search, and they asked me to spend a few weeks doing a cofounder sprint with them to determine if they wanted to add me as a third cofounder. So, I killed gen UI for marketers to pursue iterative search with this high quality team. Circa April 1st, 24. 

## Iterative Search

This was the most promising direction I’d had since starting my journey at SPC. It felt like the time to put all my eggs in that basket. The team was strong, good background, and they had learned some stuff already in their time together. Long story short, the team was not cohesive and despite having some great ideas and some decent horsepower, the CTO left the group and I was then also out of the company. 

We were building iterative search, a platform that would learn about your preferences and what you do and don’t want in certain searches or in all searches. Different from google because we would have given you a long form search experience in which you could describe the problem that you were facing. We would then package up this preference data and use it to personalize your product oriented web experience, making it easier for the consumer to find the subjects of their complex search queries. 

I can’t share documents here because one of the team members is still working on it and I don’t want to share secrets, but there’s a lot of slides, spreadsheets, and docs that were shared amongst this org. 

I went all out with this team, produced two decks, a gtm plan, ripped apart their assumptions, did 20 customer interviews and created a business plan all in 2.5 weeks. But ultimately it wasn’t meant to be. Iterative search was killed for team failure. 

## Nanotubes

When the CTO of the previous sprint left, I’d hoped he would join me independently and work on some other ideas. He declined and decided to take a job instead. This sent me into a spell of frustration. Why were all these cofounder sprints failing? Why are people so willing to give up and take a job? Why are people so money and lifestyle motivated? 

I decided to try and tackle the absolute largest problem I could get my mind around that nobody else I knew was working on. This ended up being carbon nanotubes production at scale. CNTs are essentially a super material, amazing at a tons of things like semiconducting and making composite materials, but nobody has been able to figure them out at scale. So I did a two week research sprint into production of CNTs at scale to see if I could build a company on this idea. 

Unfortunately, there is probably decades of research left to do, and it’s unclear if this material will ever be mass produced given certain limitations at scale. Nanotubes were killed for science risk. 

More documentation can be found [here.](https://www.notion.so/2D-Carbon-Materials-a5917b9cb7924a69a1d61eee4f297af5?pvs=21)

## Asteroid Mining

In the same bout of frustrated, large idea shopping, I looked into asteroid mining. More here - ultimately, I couldn’t reach conviction that there will ever be a market large enough for this to make sense. Asteroid mining was killed for lack of market. 

More docs [here.](https://www.notion.so/Asteroid-Mining-f0a07591527f4ecb9a27609a5e56dd65?pvs=21)

## BI Employee

Now we’re on to ideas I’m currently thinking about but haven’t made much progress towards. This idea is more b2b, and centered around the pain points I’d heard from the many marketers I spoke when exploring the generative UI tool. 

There are a few examples of this working really well. [Devin](https://www.cognition.ai/introducing-devin) and [Relevance](https://relevanceai.com/function/marketing) both have AI employees for different types of employees, SWEs and SDRs. So it seems like this model can work well. 

Of all the customer research I’ve done, it seems like data visualization and insights is the biggest problem for most companies, across the board, that are consumer facing. Marketers, C suite, Sales, Ops… they all rely a lot on data teams to do SQL queries for them and create dashboards inside their visualization tools (like Looker), and most of those data teams are headcount constrained. 

It’s possible for Looker to build this functionality, and they [are](https://cloud.google.com/blog/products/business-intelligence/looker-roadmap-for-the-generative-ai-era). But people fucking hate using tools, and they’d much rather delegate out to a person if they can. Plus, that person has strategic context which is very useful. So there’s a lot of value in having a “person” embedded in the team, in slack, in meetings, and accessible over email or text. 

To do this technically, would need to integrate at first with Looker, a few types of DBs, Segment probably, slack, email, zoom. This would be a bit to build out at first, but could get away with just slack and Looker, most likely. 

## Networking Agents

Again, this is a new idea as of 5/13/24, so there isn’t much to show yet, but here’s the general idea. Imagining a future where GPT6 is a thing, we have to imagine that models can do much better reasoning out of the box. If this is true, what sorts of blue ocean markets will be much much better because we’ll have essentially unlimited access to reasoning agents? Software will get built quickly, and there will be infrastructure for this, but that’s for someone else to build. 

Instead, I imagine a world where we have lots of agents running around doing stuff for us. I think people will build shopping agents etc. but I don’t think people will build networking agents and/or social network agents. Think about how much can be unlocked by meeting the right person at the right time, well we can facilitate that with agents that represent ourselves, and chat about what each other are working on, who we’re talking to, what we’re reading etc. We want to find people in common who are open to collaboration, mentoring, hiring, investing, teaching, etc. We can do a much better job wrangling society’s resources together (people) with an army of agents learning about each person, their goals etc. and then helping them built the right relationships to facilitate their goals. 

I started to work on the code for this and can do two things: send emails in your voice automatically, and map your social graph against others to see what the network path might look like. 

## **Things I’ve learned**

I’ve learned a lot, but I’ll mention only the main points.

1. Writing is extremely useful for anchoring thoughts in reality. I now try to write for 1 hour every day. 
2. I personally have a hard time committing to stuff. There are so many interesting ideas how there. How to pick just one to work on for a decade?
3. It takes a long time to build great things. And most of that time is used up by making mistakes and “wasting” time going down the wrong path. 

## **What I’m doing now**

As of 5/13/24, I’m working on the networking agents idea and looking yet again for new cofounder candidates. I’m also considering just hiring some contractors and going for it myself.