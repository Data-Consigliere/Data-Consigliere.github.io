---
title: "Borrowed Certainty"
description: "Returning to Calculus, Linear Algebra, and Statistics — not as a classroom exercise, but as a formal audit of the math that governs every model in production today."
date: 2026-04-17T16:35:00+01:00
draft: false
tags:
  [
    "mathematics",
    "machine learning",
    "data leadership",
    "AI fundamentals",
    "technical strategy",
  ]
categories: ["Learning in Public"]
cover:
  image: "/images/borrowed-certainty-factory-floor.png"
  alt: "A worker in worn industrial clothing inspecting the internal gears of a large, partially disassembled machine, lit by a single amber work lamp."
  caption: "Not for the diploma. To inspect the raw materials."
  relative: false
  hiddenInList: false
  hiddenInSingle: false
toc: true
readingTime: true
featured: true
ShowShareButtons: true
ShowRelatedPosts: true
---

_The silent debt that accrues when technical leadership outsources its foundations._

**The Audit of the Bedrock**

Moving from the executive layer back to first principles isn't nostalgia. It's due diligence.

After years directing how data should inform a board's decision, returning to the core math feels less like a classroom exercise and more like a return to the factory floor. Not for the diploma. To inspect the raw materials.

Modern data science has made it dangerously easy to be a _library tourist_ — someone who imports PyTorch or scikit-learn without understanding the metallurgy of the blades they're wielding. It works, until it doesn't. In high-stakes analytics, a silent failure is the most expensive kind. If you don't understand the underlying math, you aren't building a system. You are borrowing a result.

When I sat down for the preparatory math work ahead of the Le Wagon bootcamp, I treated it **as a formal audit of my own foundation**.

Most problems that look technical are actually failures of clarity. But in AI, if you lack the mathematical vocabulary, the failure is invisible — a silent debt that accrues in your code until the model meets the real world and breaks.

Returning to these fundamentals — _Calculus, Linear Algebra, Statistics_ — is how a practitioner re-arms. Not to perform expertise. To rebuild it from the ground up, so that when the moment comes to make a strategic recommendation, the position is one of technical certainty, not informed approximation.

---

**Statistics: The Old Guard**

For anyone who has spent years in decision support, Statistics is the most familiar terrain. It's where we've traditionally looked for signal in a sea of noise.

The challenge here wasn't learning the concepts. It was re-engineering the relationship with them.

Experience gives you a calibrated eye for a skewed distribution or a misleading mean — you see the chart and know something is wrong before you can articulate why. But a machine learning pipeline doesn't have a gut. It has a configuration. The transition isn't from ignorance to knowledge; it's from interpretation to architecture. You stop reading the result and start designing the logic that generates it.

That meant revisiting standard deviations, variance, and Bayesian logic — not as academic theory, but as hard engineering filters. If you can't precisely name the probability of an event, you can't tune the model that predicts it.

Statistics is the oldest tool in the kit, and the most misused. The audit wasn't about proving competency. It was about confirming the _"Old Guard"_ was still fit for service before integrating it into something larger and less forgiving.

---

**Linear Algebra: The Infrastructure of Scale**

If Statistics is about the _what_, Linear Algebra is the _how_. It's the **plumbing of the machine**.

Traditional analytics thinks in rows and columns — the spreadsheet mental model. AI thinks in **vector spaces**. That was the first real friction point in the transition. Grasping the concept of a matrix is straightforward. Internalizing how high-dimensional data is rotated, sheared, and transformed inside a neural network is a different order of problem.

I treated this section of the audit like an _infrastructure review_. Every embedding, every similarity metric, every weight in a model is ultimately a product of Linear Algebra. The difficulty in the advanced topics wasn't a lack of ability — it was the friction of shifting from a scalar mindset to a multi-dimensional one. From single numbers to vectors that carry meaning across dozens of dimensions simultaneously.

The inflection point came from a change of frame: a matrix isn't a grid of numbers. It's a way to pack and ship information through a system. Once that clicks, the fog clears. You stop seeing _"math"_ and start seeing **flow**.

---

**The Calculus Wall: The Mechanics of Momentum**

Calculus was the hostile witness of the audit.

Where Statistics felt familiar and Linear Algebra felt like infrastructure, Calculus felt like a system with no entry point. I went through three full iterations of the bootcamp material before anything cohered. Not because the concepts are impenetrable — but because the standard pedagogical approach teaches you to solve calculus before it teaches you what calculus _is_.

> It's the study of how things change. In machine learning, it's how a model learns — by calculating the rate at which its errors decrease. That's the entire job.

The breakthrough didn't come from working harder at the formulas. It came from changing the frame entirely: seeing the **derivative** as a speedometer — the rate of change at a precise moment — and the **integral** as an accumulator — the total value built up over time. Two instruments measuring the same underlying reality from different directions.

From there, the **Chain Rule** stopped being an abstraction and became an engine. It's the logic that takes an error at the output of a neural network and ripples it backward through every layer, adjusting weights as it goes. That process — **backpropagation** — is calculus at work inside every model in production today.

Admitting the difficulty of this climb isn't a disclaimer. It's the point. If you haven't struggled with the _why_ of the math, you're trusting the library to get it right. In high-stakes systems, that trust is a liability you're not accounting for.

---

**The Workshop Inventory: Tools of Translation**

When a technical resource fails to provide clarity, the solution isn't to work harder at a flawed explanation. It's to change the vantage point.

The resources below aren't a reading list. They're a curated toolkit — selected specifically because they prioritize intuition over rote calculation, and mechanics over academic posturing. Each one served a distinct function in the audit.

### For intuition: the visual framework

**3Blue1Brown** — _"Essence of Calculus"_ [^1] and _"Essence of Linear Algebra"_ [^2]. The gold standard for visual logic. Grant Sanderson's work translates abstract matrix operations and rates of change into geometric transformations you can reason about. This is where the speedometer and accumulator mental models first became concrete.

**The Manga Guides** — _"Calculus", "Linear Algebra", "Statistics"_ [^3]. There's a productive irony in a senior practitioner using manga to pressure-test complex systems. These guides strip away academic gatekeeping and focus on narrative logic — the _why_ before the _how_. They were essential during the third iteration of the Calculus audit, providing the clarity that traditional textbooks consistently withheld.

### For execution: closing the gap between concept and calculation

**Khan Academy** — _"Differential Calculus"_ [^4] and _"Linear Algebra"_ [^5]. The practice range. Used to bridge understanding and precision — the point where intuition has to become correct arithmetic.

### For implementation: connecting math to architecture

**TowardsAI / Medium** — specifically the deep dives by _Richard Hightower_ [^6] and _Rasik Suhail_ [^7]. The final translation layer: showing exactly how vectors and derivatives map to modern deep learning architectures. How a derivative becomes a weight adjustment. How an embedding encodes meaning.

---

**The Consigliere's Verdict**

The math was never the problem. The assumption that it didn't matter was.

After years directing how data should inform decisions, returning to the bedrock confirmed something I had been circling without naming: there is a version of data leadership that is fluent in the language of AI without understanding its grammar. It produces confident presentations and fragile systems. It sounds right until it isn't — and when it isn't, the cost is rarely technical. It's reputational, strategic, and permanent.

Most of us in this space have been closer to that version than a LinkedIn post would suggest. It's a temptation that doesn't announce itself. I've given in to it. Which is partly why this audit felt necessary.

The pre-bootcamp audit wasn't a solution. It was a diagnosis — and the beginning of a deliberate correction. The goal is simple to state and slow to reach: to look at a model's architecture and see not an opaque algorithm, but the rate of change, the geometry of the vector space, the statistical probability of the result. To see where it will hold and where it will break — before it does.

That visibility matters most at the moment of highest stakes. When a model goes to production. When a recommendation reaches the board. When the system meets the real world and the library can't save you.

**I'm not there yet. But I know exactly what I'm building toward — and I know the math is not optional equipment.**

_In a world of library tourists, that's the only honest place to start._

---

### **Inventory: Sources & Infrastructure**

[^1]: [3Blue1Brown – The Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Translating abstract matrix operations into geometric transformations. Essential for moving past "rows and columns" into vector space thinking.

[^2]: [3Blue1Brown – The Essence of Calculus](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) - Visualizing the rate of change and the area under the curve. This is where the "speedometer vs. accumulator" mental model originated.

[^3]: [The Manga Guide to Calculus](https://nostarch.com/mg_calculus.htm), [The Manga Guide to Linear Algebra](https://www.google.com/search?q=https://nostarch.com/mg_linearalgebra.htm), [The Manga Guide to Statistics](https://nostarch.com/mg_statistics.htm) - These guides strip away the academic "gatekeeping" of traditional textbooks. They provide the narrative logic of the math, which was critical during the difficult third iteration of the Calculus audit.

[^4]: [Khan Academy – Differential Calculus](https://www.khanacademy.org/math/differential-calculus)

[^5]: [Khan Academy – Linear Algebra](https://www.khanacademy.org/math/linear-algebra) - The "practice range." Used to bridge the gap between understanding a concept and executing the formulas with precision.

[^6]: [The Mathematical Foundation of AI – TowardsAI](https://pub.towardsai.net/the-mathematical-foundation-of-ai-what-everyone-misses-b1eedd27b60b)

[^7]: [Vectors, Embeddings, and Similarity Metrics – Rasik Suhail](https://rasiksuhail.medium.com/mathematical-foundations-for-ai-part-1-vectors-embeddings-and-similarity-metrics-bc96eaa08fbb) - Mapping the bedrock math directly to modern deep learning architectures. These resources explain how a derivative becomes a weight adjustment in a neural network.
