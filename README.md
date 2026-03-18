# Solar Stirling Generator ☀️

This repository documents my **Solar Stirling Generator** project.

The idea sounds simple on paper and much harder in real life: 
use a reflective satellite dish to focus heat onto a hot cylinder, run a Stirling engine from the temperature difference, and then turn that motion into electrical power.

I did not want to make just another school model.  
What interested me was a more practical question:

**Could a compact concentrated-solar setup make more sense than a small solar panel in awkward places like a balcony, where panel angle, limited space, and side sunlight can become a real problem?**

This repository is **not pretending to be a polished success story**.  
It is an honest project log with a partially built mechanical core, unfinished subsystems, concept work, and notes from the point where the idea ran into real tools, real time limits, and real workshop conditions.

---

## Current status 🚧

This project was **partially built, but not fully completed**.

### What I physically built or explored
- early work on the **piston**
- early work on the **cylinders**
- first mechanical fitting attempts
- basic concept validation of the core mechanical side

### What did not get fully built
- full crank and flywheel system
- full hot/cold mechanical integration
- final generator coupling
- rectification and power electronics stage
- a complete end-to-end working prototype

So this repository should be treated as:

- a **build log**
- a **concept archive**
- a **technical notes space**
- a record of what was built, what stayed at the planning stage, and what I would do differently next time

---

## Why I started this project

A big part of this project came from a very practical frustration.

When I was younger, I tested powerbanks with small solar panels and quickly noticed how painfully slow and inefficient they were in real use. That pushed me to think more seriously about solar energy and about alternatives that might use limited space better.

Instead of collecting light directly with a photovoltaic panel, I wanted to explore a different chain:

**light -> heat -> Stirling cycle -> rotation -> electricity**

What interested me most was whether a system like this could make sense in small, inconvenient spaces, especially where a regular panel setup is far from ideal.

---

## Project concept

The planned system looked roughly like this:

1. A **satellite dish** acts as the main concentrator structure.
2. The dish is covered with **reflective film**.
3. Focused radiation heats a **black hot cylinder**.
4. The temperature difference drives a **Stirling engine cycle**.
5. Mechanical motion is transferred to a **BLDC motor used as a generator**.
6. The output is rectified, measured, and passed into a **power management stage**.
7. In the full concept, that energy would eventually feed an **off-grid storage or load system**.

---

## What was explored in practice

Even though the full machine was never finished, this project was not just a sketch or a thought experiment.

The practical work focused mostly on the hardest low-level part first: the **mechanical core**.

That meant thinking about and testing things like:

- piston and cylinder geometry
- material choice
- surface finish
- friction
- fit quality
- what is realistically possible without full machining access

This ended up being one of the most valuable parts of the whole project, because Stirling engines often look deceptively simple in diagrams and much less simple once tolerances, sealing, heat, and workshop limitations show up.

---

## What stayed at the concept stage

A large part of the system remained at the concept or planning stage.

That includes mainly:

- the full rotating mechanism
- the complete thermal side
- generator coupling details
- the rectifier and voltage smoothing stage
- boost / charging / MPPT-side power handling
- full test methodology
- real performance verification

I am leaving those parts here on purpose, because unfinished engineering work is still worth documenting when the reasoning behind it is real.

---

## What went wrong

The main problem was not lack of motivation. It was **scope versus time**.

I aimed wider than the available workshop time and tools realistically allowed. Some tool choices and process decisions also took much more time than expected. In practice, a project like this can easily consume huge amounts of time before the first real run ever happens, especially when mechanical precision matters.

So no, I did not end up with a polished machine working perfectly from A to Z.

But I also do not see that as wasted work.

---

## What I learned 💡

This project taught me a lot of things that are difficult to learn from theory alone:

- workshop reality changes design decisions very quickly
- tool choice matters more than it seems at first
- mechanical projects absorb time fast
- safety around rotating tools is never optional
- even a partial prototype can still be valuable if it is documented honestly

It also pushed me to think more seriously about the full path from concept, through buildability, to actual testability.

---

## Future work

If I return to this project, the next steps would most likely be:

- improve piston and cylinder fit
- finish the crank, flywheel, and shaft side
- finalize the hot and cold section connection
- couple the mechanical side to the generator properly
- build the first real rectification and measurement stage
- run controlled tests first on artificial heat, then in sunlight
- compare the real output against the original assumptions

---

## Versioning

This repository follows my shared versioning note:

[Versioning note](https://github.com/Artisfera#versioning-note)

Have a nice day 😊
