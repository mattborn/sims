# Sims

## Introduction

I’ve thought about this and started on this at least a dozen times. There must be some deeper insight as to why I keep coming back to it. To what am I referring?

An efficient, human-friendly way of browsing, comparing, and presenting various interfaces I’ve either designed, borrowed, or worked with.

Named after [my favorite game to hack](https://en.wikipedia.org/wiki/The_Sims) in middle school.

## Philosophy

The fastest path to learning whether a theorized solution actually solves the problem is to achieve an embodied experience for all parties invested.

Though heavily inspired by [Henry Dreyfuss](https://en.wikipedia.org/wiki/Henry_Dreyfuss), [David Kelley](https://www.ideo.com/people/david-kelley), and—most recently—[Tom Chi](https://www.mindtheproduct.com/video-tom-chi-on-rapid-prototyping-product-management/), I’ve been describing this as **The Simulation Ceiling™**. For modern software teams, this ceiling is often low and inhibiting by default but we have the ability to raise it by disruption.

So how do we raise the ceiling? By accelerating the rate at which we can present an embodied experience against the following principles:

1. **Humans first** — no matter your argument, if humans haven’t tried it, we are blind and our work is like smoke
2. **Same day delivery** — if we cannot present an idea while we still care about it, our vehicle is too slow
3. **Everything is temporary** — if we cannot easily change it, it’s not realistic because we cannot know the future

It’s not a question of whether to change because change has already occurred in ways we could not predict—our people, our memory, and our position. Is the system adapting to the needs, knowledge, and skills of those who maintain it? To make anything likely costs less than half the expense to maintain.

You might say we are in the business of profit and growth, but by definition, we are in the business of humaneness and togetherness. (And for many, stubbornness.)

company — _noun_ a commercial business; the fact or condition of being with another or others, especially in a way that provides friendship and enjoyment. _verb_ associate with; keep company with.

So what is keeping us apart?

The real trick is being able to [translate human value into the language of dollars](https://articles.uie.com/the-need-to-think-and-talk-like-an-executive/).

## Requirements

### Once

1. Data (facts)
2. Design (data structures + relationships; thanks Linus)
3. Functions (machine interface — makers, mappers, manipulators)
4. Forms (human interface - access, action, allure)


### Ongoing

1. Author (who)
2. Delta (where & what)
3. Explanation (why)
4. Time (when)


## Targets & Projects

First target. Cycle through states.

1. [ ] First project. Define a set of data objects in series.
2. [ ] Render first object in series.
3. [ ] Build a cycle mechanism.
4. [ ] Ease the transitions between objects.

Second target. Apply distinct configurations.

- [ ] Airtable
- [ ] Artemis (one story to rule them all)
- [ ] Bambu
- [ ] Configurator (CPQ)
- [ ] Hatch (time paradox; chicken + egg; space between)
- [ ] Pulse
- [ ] Salesforce
- [ ] Sheets
- [ ] Sprout
- [ ] Zeus

Third target. Map content extensions starting with card catalogs.

1. [ ] Configurator (CPQ) Object Summary (first 3 cards)
2. [ ] Artemis Story Engine (first 3 cards)
3. [ ] Universal Entry Summary (first 3 cards)

Fourth target. Rework to catalog patterns.

## Schema

Should be self-evident based on data itself, but documenting here to affirm.

After completing the enumeration exercise below, I realize everything is made of the same parts. The Chinese are doing something right by making everything an extension of human conversation by embedding all utility into it. ✌🏼

That said, nothing is validated. The devil is in the details. 😈

And **the design is in the data**—not the other way around. Otherwise it’s a Guess Fest.™

### Javascript

- An Object has many properties
- An Array has many objects


### Universal (relevant to all applications)

- A Presentation has many attributes (start at the end)
- A Presentation has many apps (slides, states, stages)

- An App has many attributes
- An App has one mapped type (structure)
- An App has one architecture payload (AKA index, list, navigation, sitemap, table of contents)
- An App has many pages
- An App has many people
- An App has many customers (groups of people)
- An App has one style
- An App has many states

- A State has many attributes
- A State has one purpose (distinct from Stage)
- A State has one previous (first is null)
- A State has one next (last is null)

- A Customer has many attributes
- A Customer has one mapped type (structure)
- A Customer has many data feeds
- A Customer has many people

- A Data Feed has many attributes
- A Data Feed has one mapped type (structure)
- A Data Feed has one mapped status

- A Process has many attributes (AKA function?)
- A Process has many events
- A Process has one input
- A Process has one output

- A Person has many attributes
- A Person has one mapped type (role)
- A Person has many events
- A Person has many permissions

- An Interface has many attributes
- An Interface has many elements
- An Interface has many states

- An Element has many attributes (AKA component, think HTML element)
- An Element has one mapped type (again, component or symbol)


### Time

- A Sequence has many attributes
- A Sequence has one date (not version)
- A Sequence has many stages

- A Stage has many attributes (AKA phase)
- A Stage has one time (event? — distinct from State)
- A Stage has one previous (first is null)
- A Stage has one next (last is null)


### Content management & consumption (Subscribed feed vs. personal inbox problem)

- for Viewing items (storytelling/blog, products/store, services/marketplace)
- for Conducting transactions (conductors, not executioners)


### Event management & consumption (see Hatch & Paradox of Time Management)

…


### People management & communication (relation, location & message—link)

…


### CPQ — Configurable product management & consumption

- A Product has many items (parts?, steps?)


### ETL — Data management

- A Data Feed has many attributes (inputs, this might be a map)
- A Data Feed has many file feeds
- A Data Feed has many tables (outputs)

- A File Feed has many attributes
- A File Feed has many files

- A Table has many attributes
- A Table has many columns


### SQL UI (Q&A) — Data consumption

- A Person has many questions (AKA queries, selects, lookups)

- A Platform has many topics (AKA library, groups of suggestions and answers)
- A Platform has many suggestions (AKA results)
- A Platform has many facts (AKA answers)


### Analytics — Data consumption (see content management above; full circle)

- A Story has many attributes
- A Story has many sections (shared and unique)
- A Story has many linked topics (shared and unique, need both sections + topics?)
- A Story has one mapped type (structure)
- A Story has one title
- A Story has one purpose

- A Section has many attributes (AKA artefact, chapter, topic?)
- A Section has many rows

- A Row has many attributes (AKA layout)
- A Row has many cards

- A Card has many attributes
- A Card has one mapped type (structure)
- A Card has one title (validate?)
- A Card has one explanation
- A Card has many prime named values (key-value pairs)
- A Card has many comparison named values (alternate population norm, benchmark, target, time—history or projected)
- A Card has one illustration
- A Card has one action


## Enumerated Reference Maps

Types
- …