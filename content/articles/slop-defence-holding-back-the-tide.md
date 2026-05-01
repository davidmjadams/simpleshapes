---
title: "Slop Defence: holding back the tide"
date: 2026-05-01
draft: false
tags: ["product", "engineering"]
image: "images/slop-defence.jpg"
---

![Robot friend trying to avoid a slop house](/images/slop-defence.jpg)

There’s an important question about agent coding that's not been answered yet. It’s clear starting software has changed forever... What’s less clear, is what happens next.

It’s impossible to avoid all the talk of people vibe-coding an app over a weekend. Or one-shotting something impressively complex. The chatter is non-stop. At this point, AI coding feels like magic. The speed to MVP is immense.

But it’s not that simple. Starting has always been the easy part.

Writing new software is simple. It’s a blank page. No decision debt, no technical debt, only possibilities.

I’ve found it takes about 18–24 months to truly feel the weight of your past decisions. Up until that point, you can keep adding features, making quick trade-offs, and you won’t get burnt. It’s why more elaborate architectures feel like overkill at first. Often they are. Who needs inversion of control when you’re starting?

Over time, you start to feel the tension of making changes. It’s easy to fall into the trap of “we don’t dare touch that part”.

When that happens, teams start arguing: do we patch around it or rewrite it?

### Speed-run the start, speed-run the… entropy?

Vibe-coded apps speed-run the “easy” phase. They get you from idea to working software faster than ever before.

It’s becoming increasingly clear that this is the future. I don’t see this going back in the box. Most software will eventually be written this way.

### How to fight the tide

I’m bullish that the old best practices become more important than ever. Not to make us feel like we’re important, but to hold off the inevitable decay of the codebase. Best practices are hard-won lessons from past mistakes. They give you guardrails. They make changes feel safe. They keep the humans in touch with the core of the business.

But more than those, DDD becomes essential. By modelling your software to accurately represent the real world and your users’ problems, you keep the connection between the code and the humans.

Tools like Cucumber, where you get human and machine-readable product specs, feel like they’ll matter more than ever. If it were possible to buy shares in a testing framework, I’d go all in.

Too human and you end up with loose instructions and scant guardrails. Too robot and the humans disengage.

### What I’ve seen

I’ve spent a fair amount of time with AI coding in recent months. I’ve experienced everything from the initial “holy-moly, this is going to change the world forever” to “no robot, it didn’t work, try again… NO, try again”.

The pattern is pretty clear: with the right guardrails, you can get far. Without them, you get a lot of convincing-looking code, with nothing working.

By 'guardrails,' I mean proper testing at all levels, well-defined tasks, constraints, and clear scoping.

### The ageing question

How does this all age in a long-lived system? I don’t think we’ve really seen yet.

If vibe-coding speed-runs the creation process, does it also speed-run the natural entropy of software? Do you hit the “no one touches that bit” phase sooner?

And if it does, does that patch-vs-rewrite argument show up earlier, too? Not because the code is worse, but because nobody has enough context to change it safely.

If you build this way for years, at what point does the human fall into a diminished-responsibility trap? When nobody knows why anything is as it is. Do you just point more robots at it and hope for the best?

### Thinking “Only machines need to be able to read it” is dangerous

Asking the AI to explain the code is useful. It can help you get your bearings.

But I’ve heard people suggesting it doesn’t matter if you can’t read the code because only machines need to read it now.

For now, and I suspect for a long time, that’s a nonsense.

Because after all, it doesn’t “know” anything. It can’t “know” anything. It’s just unbelievably good at predicting the next token. But it’s statistics, not knowledge, and that facade of understanding can be dangerous. You do know, so if you’re going to hand off the building to a machine, please ensure you have guardrails that you define. You control. You understand.

By following the old best practices of a well-defined domain, proper architectural patterns and robust, human-readable tests, you give yourself the best chance of building something that lasts.
