# WPF Lucene Search Demo

## Purpose

To test how best to migrate to the latest Lucene Search Engine.

We should check out what we actually need from Lucene, how we feed it exactly and MAYBE see if we can improve the search data (no idea how yet, but this demo app is there to try these things when they pop up -- until then it's a test for the Lucene operation as-is.)



---

## Motto

This here is part of the technical storyboarding side of a UI & UX overhaul of Qiqqa.

Before we put it to Qiqqa, it will be tested here.


----

## Obsoleted Project

Reason: we're definitely moving away from .NET and Lucene.NET; in fact we are moving away from Lucene entirely: it is slightly too cumbersome for environments where there won't be any professional administrators on call: while SOLR was a very nice option we've considered, it ultimately ranked lower when we considered the context of non-computer-savvy end-users installing and employing our applications. Raw Lucene wasn't an option as I don't intend to use Java as a second/third/... language, so only 'packaged' Lucene would be an option: Elastic or SOLR. And both do well, but require professional attendance when you want FTS perfroance for large libraries. Here's where manticore-search and/or SQLite-FTS are considered more viable options.

While the subject is still relevant there, we'll be either reviving this project or doing our tests elsewhere while we work with the mentioned technologies.
