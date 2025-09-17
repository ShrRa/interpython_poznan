---
title: "Setting the Scene"
start: false
colour: "#FBED65"
teaching: 5
exercises: 0
questions:
- "What are we teaching in this course?"
- "What motivated the selection of topics covered in the course?"
objectives:
- "Setting the scene and expectations"
- "Making sure everyone has all the necessary software installed"
keypoints:
- "This lesson focuses on core tools and practices for keeping your Jupyter Notebooks readable and maintainable."
- "The lesson follows on from the novice Software Carpentry lesson, but this is not a prerequisite for
attending as long as you have some basic Python and command line skills, and you have been using them for a
while writing code to help with your work."
---

## Introduction
So, you have gained basic software development skills either by self-learning or attending,
e.g., a [novice Software Carpentry course][swc-lessons].
You have been applying those skills for a while by writing code to help with your work
and you feel comfortable developing code and troubleshooting problems.
However, your software has now reached a point where it is spread across multiple Notebooks with hundreds of cells
in each.
Perhaps it's involving more researchers (developers) and users,
and more collaborative development effort is needed to add new functionality
while ensuring previous development efforts remain functional and maintainable.

This course provides an intro into skills and practices
to help you restructure existing code and design more robust,
reusable, readable and maintainable code. 

### [Section 1: Setting up Software Environment](../10-section1-intro/index.html)
In the first section we are going to set up our working environment
and familiarise ourselves with various tools and techniques for
software development in a typical collaborative code development cycle:

- **Virtual environments** for **isolating a project** from other projects developed on the same machine
- **Command line** for running code and interacting with the **command line tool Git**, 
- **Integrated Development Environment** for **code development, testing and debugging**, and
- **Python code style guidelines** to make sure our code is
  **documented, readable and consistently formatted**.


## Before We Start

A few notes before we start.

> ## Prerequisite Knowledge
> This is an intermediate-level software development course
> intended for people who have already been developing code in Python (or other languages)
> and applying it to their own problems after gaining basic software development skills.
> So, it is expected for you to have some prerequisite knowledge on the topics covered,
> as outlined at the [beginning of the lesson](../index.html#prerequisites).
{: .callout}

> ## Setup, Common Issues & Fixes
> Have you [setup and installed](../setup.html) all the tools and accounts required for this course?
> Check the list of [common issues, fixes & tips](../common-issues/index.html)
> if you experience any problems running any of the tools you installed -
> your issue may be solved there.
{: .callout}

> ## Compulsory and Optional Exercises
> Exercises are a crucial part of this course and the narrative.
> They are used to reinforce the points taught
> and give you an opportunity to practice things on your own.
> Please do not be tempted to skip exercises
> as that will get your local software project out of sync with the course and break the narrative.
> Exercises that are clearly marked as "optional" can be skipped without breaking things
> but we advise you to go through them too, if time allows.
> All exercises contain solutions but, wherever possible, try and work out a solution on your own.
{: .callout}

> ## Outdated Screenshots
> Throughout this lesson we will make use and show content
> from Graphical User Interface (GUI) tools (Jupyter Lab and GitHub).
> These are evolving tools and platforms, always adding new features and new visual elements.
> Screenshots in the lesson may then become out-of-sync,
> refer to or show content that no longer exists or is different to what you see on your machine.
> If during the lesson you find screenshots that no longer match what you see
> or have a big discrepancy with what you see,
> please [open an issue]({{ site.github.repository_url }}/issues/new) describing what you see
> and how it differs from the lesson content.
> Feel free to add as many screenshots as necessary to clarify the issue.
> 
{: .callout}

> ## Let Us Know About the Issues
> The original materials were adapted specifically for this workshop. They weren't used before,
> and it is possible that they contain typos, code errors, or underexplained or unclear moments.
> Please, let us know about these issues. It will help us to improve the materials and make
> the next workshop better.
> 
{: .testimonial}

{% include links.md %}
