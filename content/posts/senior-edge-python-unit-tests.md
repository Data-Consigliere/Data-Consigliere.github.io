---
title: "The Senior’s Edge: Why My First Line of Python Was a Unit Test"
subtitle: "Dismantling three decades of executive certainty to build a foundation in data."
description: "A reflection on the 'Expert’s Paradox'—how professional ego hinders learning, and why a senior leader chose to start with accountability over syntax."
date: 2026-04-06T18:35:00+01:00
draft: false
tags:
  - Career
  - Data Science
  - Python
  - Leadership
categories:
  - Data Literacy & Culture
cover:
  image: "/images/senior-python-field-notebook.png"
  alt: "An open field notebook with handwritten Python logic and rocket doodles resting next to a laptop showing a Traceback error and a cup of black coffee."
  caption: "The intersection of strategic vision and the humbling reality of a syntax error."
  relative: false
  hiddenInList: false
  hiddenInSingle: false
toc: true
readingTime: true
featured: true
ShowShareButtons: true
ShowRelatedPosts: true
---

Most career advice for senior leaders is draped in comfortable lies. We are told that our "soft skills" and "domain expertise" are our ultimate shields.

I believed that, too — right up until I sat down at 9:00 AM facing a blank VS Code editor and realised that thirty years of strategic wins felt remarkably thin.

In three weeks, I start an intensive Data Science bootcamp at Le Wagon [^1] . A deliberate move. The kind that looks like ambition from the outside and feels, from the inside, more like controlled demolition — tearing down a professional identity built on certainty so you can rebuild it on something more durable.

But the dismantling started earlier than I expected.

---

### The Fog Doesn't Care About Your CV

For three decades, my value has been tied to certainty. The job — the actual job, not the title — was to walk into rooms full of ambiguity and make the fog legible for everyone else.

> _Then I encountered `TypeError: 'NoneType' object is not subscriptable`, and suddenly, the fog was mine alone._

This is what I've started calling the **Expert's Paradox**: the very thing that makes you effective in a leadership role — the reflex to project competence — becomes the biggest obstacle when you sit down to learn something genuinely new.

A junior developer expects to fail. For someone who has spent decades being the person who clarifies things for others, failing at a basic loop doesn't just sting. It feels, in some quiet, embarrassing way, like identity collapse.

I spent some time fighting that feeling instead of writing code. I'd read the error message, feel a flicker of something close to shame, and go do something productive instead — answer emails, review a deck, anything. The syntax wasn't the problem. The inner ego was the problem.

The shift I eventually had to make was simple but uncomfortable: I had to give myself permission to be bad at this, on purpose, for a while. Not as a strategy. Just as a fact.

---

### Systems, Not Scripts

Once I stopped performing competence and started actually learning, the first thing I noticed was the difference between what the internet teaches and what I actually needed.

The internet is full of what I've come to think of as _Survival Python_ — the "Hello World" scripts, the basic loops, the snippets that live and die in a single Jupyter Notebook cell. They give you a quick hit of _dopamine_: the code ran, the chart appeared.

But in any professional context, "it works on my machine" is a liability, not an achievement. I know that. I've spent years telling other people that. So I made an early decision to approach this differently — not just learning to write code, but learning to write code the way a professional would.

Borrowing project templates [^2] that impose structure from the start. Using modern tooling like the `uv` package manager [^3] to handle environments cleanly. Asking not just "how do I calculate this average?" but "how do I structure this so someone else could run it tomorrow?"

A career spent recognizing patterns makes one truth clear : technical debt isn't just a cost; it's a tax always collected with heavy interest further down the road. As it happens, learning follows the same logic. What feels like a 'hack' or a productive shortcut today is simply the seed of tomorrow's frustration.

---

### The Safety Harness

The most important thing I've done in this preparation period isn't a framework or a tool. It's writing unit tests.

Most people treat testing as an advanced topic — something you unlock once you've mastered the basics. I came to think that's exactly backwards.

What I'm most afraid of, working in a new space, isn't hard work. It's invisible failure. A silent error in a spreadsheet that propagates through an analysis and surfaces three weeks later in a board presentation — that caution is professionally encoded in me after three decades.

Drawing on practitioners like Eugene Yan [^4] , I've started treating unit tests not as a chore but as an insurance policy for my own logic. Writing a test before or alongside the code does two things.

First, it forces you to define what success actually looks like before you start — something surprisingly hard to do when you're still learning the vocabulary.

Second, it lets you experiment and refactor without the paralyzing fear that you're breaking something that was already working.

> It is a way of saying: _"I may be new to this syntax, but I am not new to accountability."_

Unmanaged complexity is a liability. Testing is the mechanism I use to protect both my time and my professional standing.

---

### Mapping the Journey

The biggest trap I've seen for people with senior backgrounds taking on technical learning is
scope creep. We're trained to see the whole system at once. We want to understand the neural network before we can reliably manipulate a list.

I've forced myself to map the learning into _three distinct layers_, and to respect the sequence.

The **first** — variables, loops, functions, the basic logic of giving unambiguous instructions to a machine — is done. It sounds trivial. It wasn't.

The **second** — Pandas, NumPy, working with datasets as sets rather than rows — is also done, and this is where the payoff starts to become concrete. This is the layer that replaces the expert spreadsheet.

The **third** — PyTorch, scikit-learn, the model-building layer — starts in three weeks.

Most people rush to the last because it's _where the hype lives_. But the models are only as strong as the plumbing beneath them.

By taking the first two layers seriously, I've tried to ensure that when I reach the third, I'm still thinking like a strategist — not just pressing buttons and hoping for outputs.

---

### What This Is Actually About

The value of this transition isn't in the Python scripts I'll write. It's in the shift in judgment that comes from understanding the friction of the data — how hard it actually is to clean, how fragile a pipeline can be, where the assumptions hide.

There's a version of this story where I position all of this as a clever strategic move. An investment in future relevance. And it is that. But it's also something smaller and more honest: I sat down at a blank editor, felt the discomfort of not knowing what I was doing, and kept showing up anyway.

That's not the insight I expected to walk away with. But it might be the most useful one.

The goal isn't mastery. It's literacy. And literacy, it turns out, starts with being willing to look stupid for a while.

---

### The Field Notebook

[^1]: [Le Wagon Data Science](https://www.lewagon.com/data-science-course) - The upcoming intensive phase.

[^2]: [Datalumina Project Template](https://github.com/datalumina/datalumina-project-template) - A practical starting point for structuring Python projects as systems, not scripts.

[^3]: [uv: A Modern Python Package Manager](https://www.youtube.com/watch?v=ygXn5nV5qFc) - Replacing pip and venv with a cleaner, faster unified toolchain.

[^4]: [Eugene Yan on Python project setup](https://eugeneyan.com/writing/setting-up-python-project-for-automation-and-collaboration/) - Why unit tests are the backbone of professional work, not an advanced topic.
