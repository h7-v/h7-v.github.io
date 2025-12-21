---
layout: post
title: "The elephant in the room"
author: halcyon7
email: h7-v@proton.me
date: 2025-12-21 18:13:01 -0000
---

The genie is out of the bottle and takes the form of a huge, unstoppable AI-generated elephant. As much as I wish it would still make sense to continue to create and build things with our own two hands, the case is that we're at a serious disadvantage if we don't use the tools available to us.

Hence, I find myself spending *nearly* as much time wrestling with the LLMs as I would just writing code alone. Emphasis on *nearly.*

There is much to be gained in having a deep thinking model implementing device functionality so long as the code is well understood by the user and the underlying architecture of the system is sound. Where I really find value in using these systems is learning from their vast knowledge given a specific context. That is, gaining knowledge myself when the model finds issues with my architectural decisions that I would never have considered before implementing them. Rather paradoxically, however, is that these systems are often awful when it comes to system architecture.

Do some obvious but monotonous code adjustment? Fine. Implement some new functionality without introducing bugs? Mostly fine. Try to build a whole system from scratch that is highly readable, understandable and maintainable? Absolutely not. Not yet anyway. LLMs do not properly refactor as they iterate in the same way that humans do. They do not reorganise or restructure code in a way that makes sense to our slow, low short term memory capacity brains as they increase the complexity of the system.

In addition to all of this, the messages earlier in a conversation seem to have far less impact on what the model generates later in the conversation. It seems to "forget" details about the initial query and ends up deviating from my original design goals on a project. Then, the model will convince itself that this new path is absolute, and convincing it otherwise becomes impossible. At this point, I consider the conversation thread "poisoned" and no longer useful to me. From there it's back to a new conversation, starting with project basics and providing it with the latest source code.

Contrary to my original statement about being at a disadvantage without using the latest tools, I'm in fact still using the site chat interfaces for all my work rather than tools such as Cursor. This is certainly subject to change soon! Perhaps I'm behind the curve here because I've been fairly adamant about not paying for these tools yet, but a one month trial of Gemini 3 Pro has blown me away despite the shortcomings listed above, and I'd like to see what this model as well as Claude Opus 4.5 have to offer when used inside an environment like Cursor.

I'm so very glad that I learnt to write software *before* the vibe code revolution took over, because without having to trawl through my own early spaghetti codebases fixing mistakes and trying to keep my head wrapped around what I'd actually written, I would have never been able to detect and correct the poor decisions that these models make when building larger systems.

Let's make some pasta
