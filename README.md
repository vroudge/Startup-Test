# Startup-Test
This checklist of important things that tech organisations should be doing in the fields of communication, project management, and programming. I aim to apply this list to other professions in technology, so if people have knowledge of good guidelines for other areas (marketing, art, legal, etc), please don't hesitate to add them.

It is presented as a list of questions, followed by a bigger list of small paragraphs explaining the details for each question. For a quick view of everything, jump to the [questions](#questions-list).

#List of things

Click on links to jump to a section you're interested in.

* [Introduction](#introduction)
* [Questions List](#questions-list)
* [Detailed List](#detailed-list)
* [Tools](#tools) (Apps, websites and other tools related to this guide)
* [Resources](#resources) (Articles, guides, essays, presentations and anything to get more informations on things listed here)

# Introduction
It is inspired by the [Joel Test](http://www.joelonsoftware.com/articles/fog0000000043.html). It's just a way bigger list that is intended to become a definitive, open and collaborative list of good practices, widely accepted by tech companies. This collection of questions are inspired mostly by Agile development and the actual, practical experience that comes with it. There are other ways of successfully developping software, but this way is used widely enough to be considered and industry standard.

This document being open source, it is intended to be refined as much as possible by people's ideas, and new practices that may be discovered, in order to serve as a reliable resource for any tech organisation.

You can see it as a test, checklist or general wishlist.

Also note that this list is neither exhaustive nor binary. You can use only some of these and be fine, as you can use most of these and be fine too. Organisations come in all shape and size not all of these necessarily work for you, which is ok. I'd say try what sounds good, and keep what works. But do try. Seriously.

It is a **work in progress**, many things are yet to be written, but this first draft is accessible for feedback and improvement. Feel free to fork, add things and make a Pull Request if you want to help. You can also open issues here on Github for discussion, questions, or suggestions.

Everything marked as TODO or wip is basically a draft that has not yet been properly written/sourced.

#Questions List

##Project Management

Anything related to how we list, manage and treat tasks goes there.

* Do you break down feature requests in [small chunks of isolated tasks](#breaking-down-tasks) that each require a small amount of time?
* Do you let members of the team participate in [estimating the tasks](#estimating-tasks) duration?
* Do you set your planning for short sessions (few days/weeks) and then refine it at the end of each session?

##Workplace Culture

I just added this section. It may be opinion-based, but I'm trying to pick guidelines that I think would be good everywhere. These are inspired by this [article on programmer culture](http://gamasutra.com/blogs/RichGeldreich/20151203/260874/Opinion_Video_Game_Programmer_Culture_Must_Change.php)

* Do you have a [code of conduct](#code-of-conduct)?
* Do you actively work to hire [diverse people](#diversity)?
* Do you actively try to mitigate pressure and keep [sane working conditions](#sane-working-conditions) for employees?
# Do you encourage a continuous discussion with and between employees to [improve the company's culture](#improve-culture)?


##Communication and general team coordination

This list concerns everything regarding the flow of information between members of a team, general company communication, and how to keep all that productive.

* Do you have a centralized [communication platform](#communication-platform)?
* Do you [avoid meetings](#avoiding-meetings) when possible?
* Do you [keep trace](#storing-information) of things said during meetings?
* Do you have clear [channels of information](#information-channels) that let people know about the various decisions made?
* Do you regularly [discuss as a team](#discussing-success-and-failures) the success and failures of your recent work?
* Do you encourage individuals to suggest new ideas and [give feedback](#team-feedback)?


##Programming

This list is programming specific. Mainly good practices that have been proven to improve the productivity of programming teams and reduce bugs/other kinds of problems.

* Do you use [version control](#vource-control)?
* Does _all_ of your team actually know how to [properly use source control](#properly-using-version-control?)
* Do you have a [branching strategy](#branching-strategy) for your team?
* Do you perform mandatory [code reviews](#code-reviews) before merging any change in production at some point?
* Do you have a [bug database](#bug-database)?
* Can you make a [build in one step](#build-process)?
* Do you have some form of [continuous integration](#continuous-integration) running?
* Do you have [automated tests](#automated-tests) running after each build?
* Do you write [new automated tests](#writing-new-automated-tests) before writing new code or fixing a bug?
* Do you [fix all known bugs](#fixing-bugs-first) before working on new features?
* Do you take the time to [update old code](#update-old-code) to current standards when you need to modify it?
* Do you have a [coding convention](#coding-convention)?
* Do you check that the coding convention [is respected](#respecting-coding-convention)?
* Do you have a [documentation](#documentation) that summarises the project's architecture?
* Do you work with [modular code](#modular-code), split in small, independant files?

#Detailed list

(wip)

##Project Management

### Estimating Tasks

It is very important that when working with a team, the persons estimating the duration for a task are actually the ones that will work on it. Even if the manager knows the work of the people, they might not necessarily know all the details and other things the tasks depends on. So it's way safer to have the people actually working on the project deciding how much time they need. Multiple advices are always good.

So the idea is to take everyone concerned by a task on the team and let them discuss the task, and decide the time they need. A manager (or anyone not directly working on the task) should not have the power to reduce the estimated time.

It's also important to note that on the engineering side, people tend to underestimate the duration of a task, and it is a good idea to multiply the estimated time for some error margin. Better overestimate a task and be faster than expected, than delivering late.

### Breaking Down Tasks

The "standard" allowable times for tasks are: 1, 2, 4 and 8 hour. If you estimate a task, it must be one of these times. If you estimate, say, 3 hours, then pick 4, don't try to fit it in two hours.

These fixed time chunks are there to avoid people trying to fit things in lower, needlessly precise intervals of time, which is often a sign of underestimation. So don't just try to say this task will be 5 and a half hour. Just allow the day to it and do it properly.

If any task is more than 8 hours, then it's too big a task and should be broken down in smaller chunks. A big task during more than one day creates problems. It's not easy to track progress on long tasks, and our brains are not really made for that. We're made for working with small problems. The smaller the better.

Less is more. With restrictive but simple rules on the way you plan, you can make sure that the rules are actually followed properly.

##Workplace

###Code of conduct

A code of conduct may seem pointless, but it's actually important very soon, once a company starts to grow. Toxic people can be found everywhere, and most of the time they're not even aware that they are. A strict, enforced code of conduct can avoid people being hurt by others. We're all humans, and there are things you can't just say to people. Here is an example of a [code of conduct](http://lists.llvm.org/pipermail/llvm-dev/2015-October/091218.html).

###Diversity

> TODO (Hiring diverse people to avoid having a "boy's club" making all the decisions at the top, which often lets a lot people feeling left out, discouraging them in many ways. Diversity brings new ideas and creativity)

###Sane Working Conditions

Check that the workplace is safe for people, both physically and psychologically. Check that people can work productively without being disturbed or harassed, and check that you have good desk setups that won't break people's back if you can afford it. See this great article on [Computer Workstation Ergonomics](http://blog.codinghorror.com/computer-workstation-ergonomics/) by Jeff Atwood

###Improve Culture

> TODO (Communicate with the team to get their feedback/ideas on how to get better in all of this)

##Communication

###Communication Platform

> TODO (Centralized communication platform that avoid spreading on multiple tools. ie. Slack)

###Avoiding Meetings

> TODO (Avoiding useless meetings all the time, always stopping the productivity of people. Learning to have meetings only when necessary)

###Storing Information

> TODO (Keeping trace of important things/data. Taking note of things said during meetings, and having most discussions directly on the public communication platform so they don't need to be transcribed later, allowing new team members do read through the collective knowledge of the team)

###Information Channels

IRC, Slack, Reddit. Possibilities are really endless. One thing's sure: the quality of the product is correlated to the quality of communication in the team. People should know what is going on. Making feedback on the product easily accessible, knowledge of the market available for all to see, there are many reasons that will compel you to use some sort of channel of communication by all the staff. 

###Discussing success and failures

> TODO (Regularly look back on the recent work and discuss as a team what worked and what didn't. Adapt your different processes according to that)

###Team Feedback

It's a good thing to have regular meetings between staff & management to be able to detect issues, get and give feedback about one's work. Sometimes, people can be affected by personnal issues that will affect their time in the workplace or the quality of their work, and the company needs to be aware of it for roadmap purposes. 

Getting and giving feedback from staff can be a way to detect early-on toxic issues that will affect everyone, and by association, the product.

##Programming

###Version Control

If you're here, you probably know what [source control](http://www.git-tower.com/learn/git/ebook/mac/basics/what-is-version-control#start) is. It is the absolute minimum standard for any project involving code. Even if there is only one programmer working alone, source control is required. This one is non-negotiable. Here's [why](http://www.git-tower.com/learn/git/ebook/mac/basics/why-use-version-control), and here's [how to get started](http://www.git-tower.com/learn/git/ebook)

###Properly using version control

Even though most companies use source control, very few of them use them properly. Thing is, for some reasons developers are rarely properly trained for it, and people assume that it should just work out of the box. Especially with the existing graphical interfaces for Git that hide the command-line part for you.

Long story short: If you only use git to commit/pull/push, you're missing a ton of things. Have you ever had to copy/paste lines to cancel a change someone made, or comment tons of line because you were developping a feature and need to temporarily disable it? If those sort of things remind you something, you're probably not using git to its full capacity. Do you [use branches](http://www.git-tower.com/learn/git/ebook/mac/branching-merging/branching-can-change-your-life#start)?

If you want to really understand git and be the person that saves the team with their understanding of git, you should definitely look at [this website](http://think-like-a-git.net/).

###Branching Strategy

Using branches is a good thing, but you should have a clear process for working with branches. People creating branches when they work on something is fine, but it's way better if you have a standardized way of managing those branches.

There are many ways to do that and in the end it depends on how you work and how your team is structured. But basically, you should be clear with your team about:

* Why branches are made
* How they're named
* When and where they are merged/deleted
* Which branches are sensible, permanent branch (like the branch you will use for beta builds, production builds...)

###Code Reviews

Contrary to popular belief, code review need not be hard. And they are [incredibly useful](https://www.atlassian.com/agile/code-reviews). Just by having someone give a look at a commit before puttin it in production, you can avoid horrible bugs later.

There again, there are multiple strategies. But the simplest, which is the model followed by open source development on websites like Github, is code review on Pull Request.

Basically the idea is, when someone wants to merge their changes from a development branch to the production/staging/whatever branch, they open a Pull Request. You then have at least one developer, ideally multiple, read through the code to see if everything is OK before validating the change.

The benefits are multiple: Social pressure makes people write better code, risky code that create bugs can be detected sooner, and people in the project understand more about the code that other persons wrote, which is better for maintenance.

###Bug Database

> TODO: Keep a bug list, sort bugs by priority, keep track of crash and crash logs, etc.

###Build Process

> TODO: Have a simple, one-step build process, as fast as you can make it. If a build is boring/long to make, the developers will avoid it. Less builds mean less test, which means less chances to find bugs before they're deep in the code

###Continuous Integration

> TODO: Continuous Integration — Have a server make automated builds each time a new change in the code is merged. Do it at least in an internal staging version for the company, but if possible do that with production too. See tools like [Jenkins](https://jenkins-ci.org/)

###Automated Tests

> TODO: Write automated unit tests for all your code. Have these tests run ideally each time you launch the app, and at least each time you build it. The more tests you have, the more chances you have to be warned by them if some code you wrote broke your product. Functional tests are also good (automated bots running a pre-recorded scenario of actions in your app, and looking for crashes). See [Unit Testing](https://en.wikipedia.org/wiki/Unit_testing), [Functional Testing](https://en.wikipedia.org/wiki/Functional_testing) or [Test Driven Development](https://en.wikipedia.org/wiki/Test-driven_development)

###Writing New Automated Tests

> TODO: Write new automated tests as you go. Even if you didn't write any when you started on the project, don't take it as an excuse for never writing any. Start writing some for every new piece of code you add. Also, when you fix a bug, write an automated test for that bug, so that it will fail until the bug is resolved.

###Fix All Known Bugs

> TODO: Basically fix known bugs first, write new features later. Not the opposite.

###Update Old Code

> TODO: Most teams struggle with old, horrible code. We don't know what to do with them, and we don't have the time to refactor it. Well here's that simple trick to deal with it: don't try to refactor it in one go. Just update the parts you can when you need to touch it. Even if it's one or two functions, after some time this old code will suddenly be a lot easier to deal with, all without having to take an entire week of refactoring. It's also a good idea to include this continuous refactoring time when you estimate tasks.

###Coding Convention

> TODO: A coding convention is a document that lists every rule of coding style in an organisation. They can include indentation (Tabs? Spaces? How much spaces?), variable/function/class naming, and tons of other things.

###Respecting Coding Convention

> TODO: Don't just send a coding convention to people when they arrive; actually check that it is respected. This can be done in the code reviews, but an easier (although not always possible) way to do that is to setup git hooks that verify the style of the code, and will reject commits that don't pass the tests. Also note that there are standard coding styles widely accepted for most languages, and tools for checking them (ex: [jslint](http://www.jslint.com/) in Javascript).

###Documentation

> TODO: Documentation need not (and should not) be a big 300 pages technical design document listing all classes and their interactions. Big documentation is actually often an excuse for overly complicated code ( "but you can just read the doc" ). You do often need some form of documentation though, if only for outlining the general architecture of your project so that new members can grasp an idea of what is what and where.

###Modular Code

> TODO: Try to organize your code in small independant modules, and make your project use those modules. Avoid as much as possible having big files, or so-called "managers" that are so deeply rooted in all of your code that any trivial modification anywhere is at the risk of breaking everything, everywhere.


#Tools

##Code Quality

### Linters

> TODO: Describe ESLint uses

### Codacy/Code Climate

Allowing you to establish strong analytics of your codebase (dryness/complexity/style), they'll be your best ally for measuring test coverage and quality code, with a grading system. Very easy to set-up and with nice offers for start-ups. If you're writting test for your code, they're a must-have in your fight against technical debt.

##Continuous Integration

### Jenkins

> TODO: Describe Jenkins

### TravisCI

> TODO: Describe Travis

### Codeship

> TODO: Describe Codeship

## Communication

### Slack

[Slack](http://slack.com/) is an awesome communication platform. It centralizes everything and can connect to pretty much any API. A ton of companies have started using it and have been able to stop working with crowded mail inboxes, useless meetings and other problems.

## Project Management

### Jira

[Jira](https://www.atlassian.com/software/jira/)

### Trello

[Trello](https://trello.com/) is a web-based project management application also available on smartphones. You can visualize your tasks and share them with others people in your team. You can use it as a todo list. This tool is inspired by the [Kanban process](https://www.atlassian.com/agile/kanban/)

## Source Control

### Github

[Github](http://github.com)

### Bitbucket

[Bitbucket](http://bitbucket.com)

### GitLab

[GitLab](https://about.gitlab.com/) is a an open source tool that allows you to use git on your own servers. It gives you a total control on your data.

## Others



#Resources

> TODO: This is a list of links to resources related to this guide (not tools, see previous chapter). Feel free to link any relevant article, tutorial, presentation, documentation...

## Workplace

* [How I created a better workplace](http://www.tintup.com/blog/how-our-tech-startup-created-a-better-workplace-feedback-system/) by Tim Sae Koo, about the feedback process they used to keep their workplace sane for employees.
* [Computer Workstation Ergonomics](http://blog.codinghorror.com/computer-workstation-ergonomics/) by Jeff Atwood, describing the correct way you should setup your workstation to avoid health problems. Anyone working behind a desk should read that.

## Source Control

* [Try Git](https://try.github.io/levels/1/challenges/1) The most fast and easiest way to try Git online, by Github.
* [Think Like A Git](http://think-like-a-git.net/) A website for learning more about the theory behind Git and understanding how it work, and how to better use it.


