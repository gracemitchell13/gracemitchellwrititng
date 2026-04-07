---
layout: post
title: "Building Groundwork, Part 1: Why I Built This"
date: 2026-04-06
tags:
  - Groundwork
  - AI & Tools
summary: "I'm not a developer. I've been building with Claude anyway. Here's why — and what I'm making."
---

I've spent most of the last 20 years surrounded by computer developers of various types. I am not a developer. I have never been a developer. I want to be upfront about that, because everything that follows is going to involve code, and I *didn't write most of it.* I've been building with Claude, and the reason I'm documenting this project is specifically because of what that collaboration looks like — what it makes possible, where it gets complicated, and what still requires a human being who knows what they're trying to build. (Spoiler: Claude writes HTML really really fast, but Claude has no taste.)

I've had some unstructured time these past few months, and I have used part of it to figure out what I could actually make with AI. First, I learned to talk to it, use it for basic admin stuff, how to use it to research and write. I've written about that before. But then, a couple of months ago, I finally figured out that yes, even I could ask it to write code.

I started small — a job application tracker, a media log, a portfolio site. Each one taught me something. At some point I looked up and realized I was enjoying the building more than I expected, and that I'd been making things for myself, which is fine, but wasn't doing much for anyone else.

That's when I started thinking about what I'd make if the user wasn't me.

I've been volunteering as a strategic advisor to a small nonprofit in rural Oregon. They do important work that helps hold a community together — adult education, environmental stewardship, workforce development, food access. The staff is tiny, and the ED is writing grants with almost no experience. She's learning as she goes, and applying while she figures it out.

I know this organization well; I wrote my master's thesis about it almost twenty years ago. I recently reread that document for the first time since I turned it in. I do not particularly recommend this exercise, but it was clarifying in ways I didn't expect. The resource constraints I was writing about in 2007 are the same ones playing out now. Only now with a global political situation that would have kept my 2007 self up at night and a federal government that hates nonprofit organizations.

One recommendation made by my earnest 2007 graduate student self was that the organization should get more diverse funding. More grants, I prescribed! I then spent a good chunk of the next 20 years writing and managing grants and proposals, and now I know how much 2007 Grace didn't know. But maybe 2026 Grace could help in a way 2007 Grace wouldn't have dreamed?

The grant writing tool market is not small. I mapped it — Grantboost, Grantable, Instrumentl, a dozen others across a wide range of price points. Probably all good products, but every one of them assumes you already know what you're doing. They assume you can evaluate an opportunity, know what sections a proposal requires, have your organizational language ready to deploy. They're built for development professionals. None of them start by asking whether you should even apply. None of them teach.

**That's the gap.** There are thousands of organizations doing serious work with no dedicated development staff, trying to access a funding system that wasn't designed for them.

Groundwork is designed to be the prerequisite to all those other tools. Lightweight. Easy to use. Free. No prior grant writing experience assumed.

I had a name by the end of day one. A working prototype by the end of day two. It looked like this:

![The Groundwork dashboard, showing five modules: Know Your Organization, Evaluate This Opportunity, Prepare Your Application, Build Your Language Library, and Track Your Pipeline.](/assets/groundwork_screenshot.png)

I imagined a well-made field guide. Something that walked you through the process from beginning to end, and allowed you to learn as you went. A toolkit.

I'm documenting the build as it happens — the decisions, the wrong turns, what Claude got right, what needed correction, and what the process of building something real with AI actually looks like. If any of that sounds useful, follow along.

*Next: how the tool works, what it took to get it live, and how much harder I made the whole thing in Section 3.*
