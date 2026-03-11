---
title: "What Happens When BI Developers Become the Users They Once Mocked"
subtitle: "A decade of judging vague requests. Then AI arrived — and the boomerang found us."
description: "How a decade of judging vague requests came back to hit us — and what it means for everyone working with AI today."
date: 2026-03-10T11:30:00Z
draft: false
tags:
  - Opinion
  - AI
  - Data Literacy
categories:
  - Data Literacy & Culture
cover:
  image: "/images/IA Karmic Boomerang.png"
  alt: "A split-scene illustration showing the same professional twice — confident and arms-crossed on the left surrounded by data dashboards, and hunched over a laptop on the right with a ghost figure looming behind him, a glowing boomerang arcing between them."
  caption: "The fifteenth iteration. The pause. The uncomfortable recognition."
  relative: false
  hiddenInList: false
  hiddenInSingle: false
toc: true
readingTime: true
featured: true
---

> Forgive me, users, for I have sinned. I once mocked you. But we are the same.

It didn't hit me in one moment.

It crept up slowly — somewhere between the fifteenth iteration on a prompt that still wasn't landing right, and the third time I caught myself thinking _"that's not quite what I meant."_ I paused. And in that pause, something deeply uncomfortable surfaced. I had heard these exact words before. Not from me. From them. The people across the table. The ones I had spent years diplomatically managing while privately rolling my eyes.

Months of working with LLMs do something strange to you. At first it feels like power — the machine is fast, tireless, impressively competent at the scaffolding work that used to eat your afternoons. Then, quietly, the cracks appear. The outputs are close but not right. You refine. Still not right. You write longer and longer instructions trying to explain what you actually mean, growing faintly frustrated that it still isn't getting there — and the whole time, somewhere in the back of your mind, a memory is trying to surface.

The ghost of every person I had ever quietly judged in a requirements meeting.

> _"I'll know it when I see it."_

You dismissed them then. You have been them for months.

That's the moment. Not a blunder, not a bad day — a slow, creeping, deeply inconvenient recognition that the skills you quietly judged in others were the skills you were quietly missing yourself. The AI didn't expose a technical gap. It exposed something older. A blind spot you'd been professionally decorating around for years.

The job had always been two things at once. The brute mechanical work — code, logic, delivery. And something quieter and considerably harder to put on a CV: reading what people actually needed, asking the questions they hadn't thought to ask yet, knowing when the output was confidently routing everyone toward the lake. We were simultaneously the builders and the translators. We just never had a clean name for the difference.

---

# The Five Sins. And the Karma They Brought.

For years, we had a private list. The complaints we kept mostly internal — too professional to say out loud, but very much alive in every dev chat and every standup that ran four minutes too long.

### **"They want everything on one screen."**

Nobody used those exact words. What actually happened was this: someone arrived with genuine purpose. A real problem. A legitimate need. They described it in broad strokes — confidently, fluently — and the request landed on your desk as something vast and shapeless. No priorities. No constraints. No definition of what mattered most. The entire problem space, delivered at once.

Now you sit with an AI tool. You have a real problem to solve. You open the prompt box and describe it — broadly, confidently — and hit send. What returns is vast and shapeless. The AI had no guardrails either. No filter for what actually matters in this specific context, for this specific decision, in this specific moment.

You stare at it. You finally understand that face. The slight blankness. The polite tilted head. The "hmm."

You gave it the entire problem space. It gave you everything back. And everything, as it turns out, is nobody's friend.

_The invisible risk isn't the person typing — it's that the tool gave them no signal anything went wrong._

### **"They don't know what they want."**

The person across the table wasn't being difficult. They had simply skipped the uncomfortable cognitive work of translating a felt business need into a defined, buildable request. The vision existed as an instinct, a direction, a general sense of "better than this." And you, without ever calling it that, were already running therapy.

Now consider the last time you opened a prompt box without having fully defined — to yourself, before typing a single word — what success actually looked like. Not approximately. Precisely.

If you're honest, the thinking often started when the first draft arrived. You didn't know what you wanted either. You just had a faster machine to not know it with.

### **"They change their minds the second they see it."**

You'd spend days building exactly what was specified — what was _said_ to be specified, which is a different thing entirely — demo it, and watch the person tilt their head at something that was suddenly, concretely, not what they thought they wanted. The requirement hadn't changed. It had simply never been real until it existed in front of them.

Abstract things can only be agreed with. Concrete things can be reacted to. You rebuilt. You briefly considered a different career in something peaceful, like cooking.

**The karma is almost poetic in its precision.**

The AI generates a first draft in seconds. You look at it — and you immediately, viscerally _know_ it's wrong. Not catastrophically. Subtly, specifically wrong in ways that are suddenly completely obvious now that something tangible exists in front of you. The requirement crystallized on contact with the prototype, exactly as it always did, exactly as you always found so frustrating in others.

### **"They can't write a spec to save their lives."**

Translating a felt business need into a precisely documented, buildable specification is a specific, unglamorous skill that most people had never been asked to develop. So instead of specifications there were suggestions. And you — the developer — absorbed the imprecision and converted it into something real. You were the translation layer.

Now consider what sits between your prompt and the AI. Nothing. There is no translation layer. No professional judgment absorbing your imprecision.

There is a model that executes your words with complete, terrifying literalness — filling every implicit assumption, every unfilled gap, every piece of context you forgot to include because it felt obvious, with its best statistical inference.

Prompt engineering is specification writing. Every vague prompt is the spec you spent years wishing someone else would write better. You are now the someone else.

### **"They don't trust the numbers."**

The dashboard is live. The logic is sound. The numbers are correct — verifiably, demonstrably correct — and still there's the raised eyebrow. The request to cross-reference with a spreadsheet that predates half the current team. We found it maddening.

This is where the karma stops being ironic and starts being consequential. It splits into two equally dangerous directions :

- Some of us review AI output briefly, sense-check it lightly, and ship it — until the hallucination is subtle enough to confirm what everyone already believed, and nobody thinks to question it. We became the person who waves the numbers through.
- Others develop a faint instinct that something's off but can't trace it to the source. They sit with the paralysis.

Generating a chart used to require knowing what you were asking. Now it requires knowing what you got. Those are different skills — and most organizations only taught one of them.

---

# The Verdict

Here's what connects all five sins into a single diagnosis. The problem was never intentions or intelligence. **The problem was always the gap between what lived clearly in someone's head and what actually made it into the room**. We spent years bridging that gap — and in doing so, we developed two distinct capabilities that we never thought to name.

Half the job was mechanical execution: the brute force of code, logic, and delivery - **The Boxer**.

The other half was reading the room, running therapy sessions without ever calling them that, asking the question nobody else was asking - **The Chess Player**.

For a decade, the Boxing was the visible credential. Then the ski lift opened.

Executives. Marketing managers. Finance directors typing instincts into prompt boxes with complete professional confidence. All of them, suddenly at the summit, generating outputs and calling them insights.

The production of data got democratized. The ability to verify, not so much.

The gap between someone who truly understands data and someone who simply generates it didn't close — it went underground, masked by the confident fluency of AI output that looks authoritative whether it is precisely right or quietly, expensively wrong. More data. More noise. Fewer people who can tell the difference.

None of us called it a skill at the time. It was just the other part of the job — the part that happened before the code and after the meeting, in the margins nobody measured. The reading of rooms. The asking of questions nobody had thought to ask yet. The knowing when to push back on an output that looked right but isn't.

**Which means the Chess Player part just became harder to replace, not easier. Not because the role got more technical. Because it got more human.**

---

# What Now

Before opening a prompt box, answer this in one sentence: _what specific decision does this output need to support?_ Not approximately. One sentence. If you can't answer it, you're not ready to prompt. **The AI isn't the meeting** — it's what happens after the meeting, when the thinking is already done.

**Treat every prompt like a specification**. Every missing detail is a hallucination waiting to happen. Every assumption left implicit is a gap the model fills with its best guess — fluently, confidently, and occasionally completely wrong. Write it like someone else's credibility depends on getting it right. Increasingly, it does.

Keep your hands on the wheel. The instinct that something feels off is the Chess Player doing its job. Trust it. Investigate it. **Your domain knowledge is the verification layer the machine doesn't have**, and it cannot be automated into existence.

The ski lift carries everyone to the summit now, effortlessly, for free. At the top of the mountain the air is thin, and the view is great. But at the summit, someone still needs to know where to aim the skis.

> **For anyone shaping how these tools reach a wider team:**
>
> The people now using them are in exactly the same gap we were in when we first opened the prompt box. They shouldn't have to build the guardrails alone — validated templates, documented logic, a shared framework for knowing when to trust the output and when to pull the thread. Not as control mechanisms. As quality infrastructure. The same way seatbelts aren't about distrusting drivers.

The boomerang found all of us. That's not a catastrophe. It's an education.

_We spent years asking the hard questions on behalf of the business. The business just got AI. If that questions doesn't have a clear answer in your organization — that's where to start._
