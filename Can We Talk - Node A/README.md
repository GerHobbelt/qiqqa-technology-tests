# Can We Talk - Node A

## Purpose

Check viability of *fast* interprocess communication mechanisms, such as Flatbuffer and ZMQ over pipes and (localhost) sockets, when the messages are exchanged between multiple languages:

- C#/.NET
- C/C++
- TypeScript/JavaScript

This is the C#/.NET node and can be considered a 'client' in the client/server concept.

> Though it's also a 'server' for the TypeScript/JavaScript channel...


---

## Motto

This here is part of the technical storyboarding side of a UI & UX overhaul of Qiqqa.

Before we put it to Qiqqa, it will be tested here.




----

## Obsoleted Project

Reason: we're definitely moving away from .NET, using C/C++ & TypeScript/JavaScript/web technologies for front-end and back-end(s).

While the subject is still relevant there, we'll be either reviving this project or doing our tests elsewhere while we work with the mentioned technologies.

(We'll be interested only in fast comms between C/C++ and TS/JS/other front-ends. As we aim for a less painful cross-platform porting experience, we will **NOT** be using .NET: the available GUI options are horrible to port or very much non-portable, even today (2023AD), for writing large desktop applications. Plus the XAML approach is *cute* but demands too muchtime & effort to produce swift & slick UIs: I DO NOT want to *specialize* in this particular technology, so we'll go with the more mainstream solution: web tech, i.e. electron, neutralino, Chromely & company!)


