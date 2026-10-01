# Notes on Using ChatGPT Dots for Long-Running Projects

These are personal observations from using ChatGPT Dots intensively for long-running creative and development work.

This is **not official OpenAI documentation**. I intentionally omit internal implementation details, identifiers, and any information related to bugs or private reports.

## My mental model of Dots

The easiest way for me to understand Dots is:

```text
Conversation
    ↓
Relevant context & memory
    ↓
Persistent project coordinator
    ↓
Reusable workers
    ↓
Parallel project work
    ↓
Workers become available for later tasks
```

In other words:

> **Dots feels less like a chatbot and more like a conversational front-end for a persistent project team.**

That change in mental model made it much easier for me to use effectively.

## 1. Treat Dots as a project coordinator

For quick one-off questions, a normal chat is often enough.

Dots becomes much more interesting when the task lasts for hours or days:

- building a project
- iterating on a design
- researching several related topics
- maintaining a long-running creative workflow
- coordinating multiple independent tasks

Instead of repeatedly explaining the whole project again, I use the Dot as the stable coordinator.

## 2. Think in reusable workers

One of the most useful patterns I observed is that project workers can behave more like persistent team members than disposable one-shot agents.

After a task is finished, I do not necessarily think of that worker as “gone.”

Instead, I treat it as:

> finished with the current assignment, available for another assignment later.

This makes long projects much easier to organize.

## 3. Give workers stable roles

Rather than treating every task as completely new, I found it useful to give recurring workers recognizable responsibilities.

My version eventually turned into a small **cat team**:

- **Orange Cat** — environment and world-building
- **American Shorthair** — visual assets and presentation
- **British Shorthair** — review and quality checking
- **Calico Cat** — systems and structure
- **Tabby Cat** — detail work and diagnostics
- **Cow Cat** — flexible support for whatever needs attention

The names are just my own organizational layer, but the idea is useful:

> assign stable responsibilities to reusable workers.

Once I started thinking this way, coordinating larger projects became surprisingly intuitive.

## 4. Parallelize independent work

Dots is especially useful when a project naturally contains several independent workstreams.

For example:

```text
Main Dot
├── Visual design
├── Content review
├── Environment work
├── Technical structure
└── Detail refinement
```

Instead of asking one agent to do everything sequentially, I can separate tasks that do not depend heavily on one another.

This is one of the biggest differences between using Dots as “a chatbot” and using it as “a project team.”

## 5. Memory feels retrieval-based

My experience does not feel like Dots simply keeps every old conversation permanently inside one enormous context window.

A better user-level mental model is:

```text
Current conversation
      +
Relevant past conversations
      +
Long-term/project context
      ↓
Current response or task
```

That means an important practical lesson is:

> information can exist in the project history without necessarily becoming the focus of every response.

For long projects, clear naming and consistent project structure still help a lot.

## 6. The visible conversation is only part of the experience

The conversational surface can stay very lightweight.

A Dot may give a short reply such as:

> “I’ll check that.”

while the actual project work continues separately.

That makes Dots feel different from traditional chat-based workflows, where the visible response itself is usually the main product.

With Dots, the conversation increasingly feels like the **control surface** rather than the entire workspace.

## 7. Continuity matters more than raw model intelligence

For this kind of workflow, the strongest model is not automatically the most useful system.

What matters just as much is:

- project continuity
- reliable state
- reusable workers
- clear delegation
- memory retrieval
- the ability to continue work without repeatedly rebuilding context

For long-running work, orchestration quality can matter as much as the intelligence of any single model call.

## My current way of using Dots

I now think of the workflow like this:

```text
Me
 ↓
Dot
 ↓
Small persistent project team
 ↓
Several parallel workstreams
 ↓
Review
 ↓
Next iteration
```

And occasionally:

```text
“Orange Cat, handle this.”
“British Shorthair, review it.”
“Calico Cat, check the structure.”
```

It sounds silly.

It is also surprisingly effective.

## Final thought

Dots makes the most sense to me when I stop asking:

> “How good is this chatbot?”

and start asking:

> “How well can this AI team stay with a project over time?”

That is where the product becomes genuinely interesting.

## A note on responsible sharing

This post was summarized and edited with the help of **GPT-5.6 Sol**.

I specifically asked it to keep this write-up limited to safe, user-level observations and to exclude bug reproduction steps, private identifiers, internal access paths, sensitive implementation details, and anything that could help reproduce unintended behavior.

My intention is simply to share what I have learned as an enthusiastic user so that other people can understand and enjoy Dots more easily.

I have also privately reported unusual behaviors I encountered to OpenAI rather than publishing their reproduction details.

I like Dots and want to keep using it. I definitely do not want a harmless post about my user experience to be interpreted as hostile research or abuse. x_x

If anything here is considered too implementation-specific to share publicly, I am happy to remove or revise it.
