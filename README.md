# How I Use ChatGPT Dots for Long-Running Projects

[简体中文](docs/README.zh-CN.md) · [日本語](docs/README.ja.md)

I’ve been using Dots heavily for projects that need to keep moving over time.

After a while, I realized that treating a Dot as “a stronger chatbot” misses a lot of what makes it useful.

These days I think of my Dot more like a long-running project assistant. I handle direction, judgment, and final approval. The Dot helps keep track of where the project is, hand work off, keep things moving, and split work when several tasks can happen at once.

Here are the habits that have made the biggest difference for me.

## 1. Dots is especially useful for long-running projects

Normal chat is already great for one-off questions.

Dots becomes more interesting when a project lasts for hours or days and goes through many rounds of revision.

A project might involve:

- organizing content
- checking references
- building pages
- fixing details
- reviewing the result

Those things do not always need to happen one after another.

Some work can move forward in parallel while I keep talking with the Dot about new requirements. I do not have to wait for every previous task to finish before discussing what comes next.

That is one of the biggest differences I notice in daily use:

**conversation and project work can keep moving at the same time.**

## 2. Don’t assume every task automatically knows everything you discussed

This matters a lot in longer projects.

After talking with a Dot for a while, it is easy to think:

> We literally talked about this five minutes ago. Surely the task knows.

But different pieces of work do not always seem to carry exactly the same context.

So when a conversation changes the actual deliverable, I usually make it explicit:

> Please apply this decision to the related work that is already in progress.

I do not do this for every casual message.

I mainly do it when something changes:

- the goal
- the audience
- the style
- the delivery standard
- a previously accepted approach
- which version should now be treated as the current one

A short explicit handoff is much more reliable than assuming every running task picked up the change.

## 3. Sometimes “forgetting” just means the relevant context is not in focus

During long projects, I occasionally ask about something we discussed earlier and the Dot does not immediately connect the dots.

At first I treated that as:

> Great, it forgot.

Now I usually try something simpler:

> Review the earlier project context about this, then answer again.

Quite often, the missing context comes back.

Because of that, I no longer expect every past detail to stay at the front of the model’s attention forever.

What matters more is whether the project can recover the information when it becomes relevant again.

For important projects, I also keep a very short current-state note:

- which version is current
- what has already been decided
- what is still unfinished
- what comes next
- where the important files live

That makes returning to the project much easier.

## 4. Reusable roles are surprisingly helpful

As a project becomes more complicated, I find it useful to keep a few recurring work roles.

For example:

- implementation
- review
- research
- final integration

I eventually gave some of these roles cat nicknames because it made the whole thing easier to remember.

Then assigning work became as simple as:

> Let the review cat check this first.  
> Let another one keep working on the edit.  
> Have the integration role collect the result at the end.

The names are just my own organizational trick, but stable roles save a lot of mental overhead.

You do not have to redefine the job every single time.

## 5. Parallel work is great, but only when responsibilities are clear

Running several tasks at once is genuinely useful.

It is also easy to create a mess if multiple workers start changing the same thing.

I prefer parallel work when the tasks are fairly independent.

For example:

- one checks facts
- one reviews visuals
- one edits copy
- one handles implementation

That works well.

Two workers rewriting the same section at the same time usually creates more work later.

Before splitting work, I now try to answer three questions:

1. Who is allowed to make changes?
2. Who is only reviewing?
3. Who will integrate the final result?

Once those are clear, parallelism becomes much more useful.

## 6. Look at the result, not only the activity indicator

With long-running agents, it is easy to stare at statuses like:

- thinking
- working
- processing

Those tell me something is happening.

They do not tell me whether the project actually moved forward.

So I care more about concrete questions:

- Was a new file saved?
- Was the requested change actually made?
- Where is the result?
- What was checked?
- What is still unverified?

At the end of a meaningful stage, I now like to ask:

> What exactly changed in this round, where is the result, and what still needs checking?

That makes the next session much easier.

## 7. Save important stages

This one matters a lot to me now.

A result can look finished in a preview while the actual editable source is still fragile or temporary.

So I treat:

**build → check → save**

as one complete action.

Candidate versions are worth saving too.

I would rather have a known version I can return to than rely on the current task state remembering everything perfectly.

## 8. Before leaving, give the Dot a clear next stop

Dots is useful because work can continue while I am away.

But “keep improving it” is an extremely vague instruction.

I get better results when I leave a concrete stage goal, such as:

> Get the next version to the point where the whole flow can be reviewed.  
> Keep the current version.  
> Check the main problems when you are done.  
> Stop and collect anything that needs my judgment.

This still leaves plenty of room for the Dot to work independently.

It also gives the task a sensible place to stop.

That is especially useful for work that may run for several hours or overnight.

# How I think about Dots now

For a small edit, regular chat is enough.

For a clear one-off question, there is no reason to make the workflow complicated.

Dots becomes most useful to me when a project lasts across many rounds, versions, decisions, and parallel workstreams.

My current mental model is simple:

### The Dot
Talks with me, receives new requirements, and keeps the project direction together.

### A few recurring work roles
Handle different kinds of execution and review.

### Project files and a short state record
Make sure the work can continue tomorrow.

That combination feels very different from ordinary chat.

The part I value most is not one brilliant answer.

It is being able to come back later and say:

> Continue.

…and have the project know what “continue” means.

## A small suggestion for new users

I would not start by designing a huge workflow.

Give Dots one real project that matters to you.

Use it for a few days.

You will naturally start noticing:

- which tasks are worth splitting up
- which decisions need to be written down
- which roles are worth reusing
- which changes need to be explicitly handed off

My version eventually turned into a small cat-themed work team.

It is a little silly.

It also works surprisingly well.

---

### Note

These are personal observations from using ChatGPT Dots, not official OpenAI documentation.

For public sharing, I have kept this write-up at the normal user-workflow level. It does not include private conversations, account information, internal identifiers, unintended access paths, or reproduction details for unresolved issues.

I organized the usage notes myself, with **GPT-5.6 Sol** helping with editing and multilingual versions.

If anything here is considered inappropriate to share publicly, I am happy to revise it.
