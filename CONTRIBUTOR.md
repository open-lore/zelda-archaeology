# How to contribute to *Zelda Archaeology*

## A Big Welcome

We're *so* glad you're here!
*Zelda Archaeology* is a large ongoing project that is trying to do the work of many full-time employees, without the employees.
For that to be possible, we thrive off of contributions from awesome people like you.

If this is your first time contributing to an open source project, then read on!
We have detailed instructions so you won't get overwhelmed by it all.
There *is* some technical jargon you'll need to pick up on, but it's not too bad once it's explained.

If you're a hardened open source veteran, then you'll find that contributing to a non-software open source project is a tad different than contributing to its software counterparts.
It's not *dramatically* different, but the purposes and organization are more fluid.
Expect more discussion and soft opinions here.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
1. [Join the Conversation](#join-the-conversation)
1. [How to Use GitHub](#how-to-use-github)
1. [Formatting and Styling](#formatting-and-styling)
1. [File Naming](#file-naming)
1. [Getting Help](#getting-help)

## Code of Conduct

Before we get to the nuts and bolts, we need to set some ground rules.
We're all part of a larger community here, and we all want the same end goal - to take our love of *Zelda* way too seriously, and do so in a productive way.
However, sometimes we have different opinions about the steps to get there, and tensions can get high.
So we've put together some ground rules to make sure that everyone works together amicably.

Before going further, take some time to read through the [**Code of Conduct**](/CODE_OF_CONDUCT.md).
Let's all do our part to make sure *ZA* is an awesome, safe, inclusive and kind place to share our thoughts and feels about the games we love.

> **Please note that this project is released with a Contributor Code of Conduct.
By participating in this project you agree to abide by its terms.**

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)

## Join the Conversation

Now that we've covered the ground rules, it's time for us to get to know each other.
We have two official places set up to talk. Both places are great for getting to know other *Zelda* fans.

1. The first is in the [Issues](https://github.com/open-lore/zelda-archaeology/issues)  section of GitHub.
When you have an idea of something you want to contribute, open up an Issue and start a conversation.
1. For less formal conversations, jump into the [*Zelda Archaeology* Discord channel](https://discord.gg/PgebRQw).
We're always happy to see new faces and learn what brought you our way.

## How to Use GitHub

There's a lot of jargon around GitHub that takes some time to get used to if you're not familiar with it.
In this section we'll go over some of the common terms and how we use them at *ZA*.

> ### If you already know how to use GitHub (TL;DR):
>
> *ZA* uses [**Issues**](https://github.com/open-lore/zelda-archaeology/issues) as the place for permanent discussion, as well as for making suggestions for updates, requests and typo fixes.
> They're organized by tags to keep things orderly.
> Broadly, you can think of Issues as the *ZA* forums.
>
> [**Pull Requests**](https://github.com/open-lore/zelda-archaeology/pulls) are where we keep all new written content for publishing.
> The first step when working on something new is to Fork the *ZA* repo and open a 'Draft Pull Request'.
> This makes reviewing and collaborating so much easier.

For everyone else - that is, you're new to using GitHub - a brief explanation is in order.
GitHub is complicated.
There's no denying that.
It's a complicated bit of software, originally made for software developers.

And while the learning curve is still steep, we don't use *most* of what GitHub can do.

In fact, we really only use three main GitHub features:

1. Publicly Tracked Collaboration
1. Version Control
1. Issues/Pull Requests

Starting with point ①, *ZA* is an open source project.
Which means that similar to a Wiki, anyone who wants to contribute to the project, can.
GitHub was developed to support open sourced projects of all sizes, and so the tools and workflows make it easy for massive projects like this one to thrive.

Point ②: version control.
Basically, this means that from the very beginning of the project, you can see every change that's been made to the repository.
In fact, you can even see who has made edits at a line-by-line level in every single document.
This level of transparency is important for two reasons.
First, it makes it clear who contributed what so that proper attribution is documented for when things get published or used under our Creative Commons license.
Second, it means that if someone ever accidentally (or maliciously) deletes or messes up anything in the repository, we can *very* easily and selectively roll back to when things were working well.

And number ③ is the process in place to have conversations and go through reviews of drafts for submission.
More about Issues and Pull requests in the next section.

### Start conversations by creating an 'Issue'

Don't let the name fool you, the [Issues](https://github.com/open-lore/zelda-archaeology/issues) section of GitHub is the most powerful comment and discussion tool ever made.
The name comes from its original purpose - to keep track of software bugs - so the tool has lots of built-in capabilities for expressing that level of detail.

Which is lucky for us, because even though we're not discussing software changes, we *are* discussing detailed concepts that sometimes need more than mere words.
So even though they're called Issues, know that Issues are a place to have conversations related to *ZA*.

If you have an idea, do a quick search in the [Issues](https://github.com/open-lore/zelda-archaeology/issues).
The search feature is very powerful, and the tags assigned to different threads are there to help sort through everything.

If you find something already there, go ahead and add your voice to the conversation.
If you don't find what you're looking for, go ahead and start a new thread by clicking the big '**New Issue**' button.

Some open source projects lock down the Issues for very specific kinds of discussions.
Here at *ZA* though, we feel that Issues are a fantastic place to have more general conversations.
And if there are specific things to note, like typos or feature requests, those can easily be highlighted and filtered via tags.

What I'm saying is, don't shy away from creating [Issues](https://github.com/open-lore/zelda-archaeology/issues).
They're there to keep conversations organized and focused, not to limit the amount or kinds of communication.

> **Come introduce yourself in the [official Introductions thread](https://github.com/open-lore/zelda-archaeology/issues/1)!**

### Work In Progress (WIP) goes in a 'Pull Request'

If Issues are for discussions, then [Pull Requests](https://github.com/open-lore/zelda-archaeology/pulls) are where we keep track of our actual work that's in progress.
Transparency is key in an open source project, and keeping drafts visible for review is a great way to embrace that idea.

Once your drafts are ready for submission, a simple change in a dropdown menu tells contributors that you're ready to have your contribution reviewed and merged into the rest of the project.

We'll go into workflows in the next section, so I won't get more detailed here.
Just know that a [Pull Request](https://github.com/open-lore/zelda-archaeology/pulls) is where you request that someone pulls your draft into the public repository.

Typically, new content starts as a discussion in an Issue (though not always).
Once everyone's clear about the work that needs to be done, and someone decides to actually work on it, a draft Pull Request is opened.

### GitHub workflow

We understand the differences between an Issue and a Pull Request.
Now we need to know how to actually open Issues and Pull Requests.

You'll create a Pull Request any time you write brand new content, fix someone else's typo, make a canonical correction or add an image. Literally any change to the content of the site will go through this Pull Request process.

> Fair warning, this is probably the most complicated part of GitHub.
> I'm not going to sugar coat it.
> However, this is a process that doesn't change, so once you've gone through it a couple of times - while shamelessly following this guide step-by-step, of course - you'll be a GitHub pro.

#### Step 1 - Create a Fork

First, you need to create a working copy of the *ZA* repository - called a Fork - to make your changes and contributions.

You create a Fork by clicking the button at the top of the screen.

When you contribute to an open source project on GitHub, you're not actually making direct edits to the repository like you would on Wikipedia, for example.
What you're doing is making a copy of the entire *ZA* repository and saving it to your own personal GitHub account.

You make all the changes to your own copy, and merge only the differences *back* into the official *ZA* repository once you're happy with your changes.
This is great because it allows you to do whatever you want without fear of messing anything up for anyone else.

> Think of a Fork as an alternate dimension where anything can happen.
> In fact, because of the Creative Common license we use, you could Fork it and go start your own *Zelda* theory project if you wanted.
> That's what the Creative Commons license is for.
> Though, my hope is that you'll stick around and get through to the 'Merge' section below.

#### Step 2 - Write your piece

Yay!
You now get to work on crafting the most beautiful piece of content you've ever written.
(Or most beautiful typo fix ever written? I'm not here to judge.)

You can do this a few different ways, but I'll focus on the most basic.
If you want to go become a GitHub pro, by all means have at it.
But for our needs, you really only need to be able to edit some text in some files.

You do this by either creating a new document by clicking the '**Create New File**' on the landing page, or you edit an existing page by clicking on the little **pencil icon** in the top right corner of the page you want to edit.

You can type directly into GitHub's built-in editor, or you can use an external Markdown editor like [Dillinger](https://dillinger.io/) and copy/paste the text into the GitHub editor.

> I'm a GitHub pro, so I personally use [Obsidian](https://obsidian.md/) or [vsCode](https://code.visualstudio.com) to edit my files, and merge them back in using the command line terminal.
> I like my text editors complicated, I guess.
> What ever floats your boat, yeah?

For quick changes, like typo fixes, I'd recommend just using the built in editor.
For everything else, it's nice to see what your formatting will look like rendered as you type it, so a third party editor can be convenient.

#### Step 3 - Committing and creating a Pull Request

Once you get to a place where you want to save your work or have someone else take a look at it, you're going to ① create a commit, and ② open a Pull Request.

To make a commit, you're going to scroll to the bottom of the page you're editing.
You'll see a box with two fields, only the first is required.
You'll type a little description of what you changed into the first box - something short and descriptive - and then click the button labeled '**Commit Changes**'.
The default settings are fine.

> **Example commit message:** 
> 
> "adds a link to the Zonai chapter"

You've now saved your edits to your own personal Fork.
Next you need to open up a **'Pull Request'**, literally requesting us to pull the edits you made in your Fork back into the main repository.

To create a **Pull Request**, you're going to click on the tab at the top of your screen labeled '**Pull Requests**'.
Once there, there will be a big green button labeled '**New pull request**'.
Click that, and it will have a bunch of default settings.
The defaults are mostly fine.

The only default setting you need to change is to click the dropdown arrow on the right side of the '**Create pull request**' button and change that to create a *draft* pull request.

Make sure you add a summary of the changes you've made, and then create that pull request!

#### Step 4 - Get it reviewed

At this point, the maintiners over here are notified and we'll all come looking at your submission.
We can have conversations about your submission, make suggestions, or request styling changes.

If there's any back and forth that needs to happen, take this opportunity to make those changes.
To be honest, most everything you submit will probably get through the review process without a hitch.
We're only here to maintain quality standards, not necessarily to filter content.
So have no fear.

Unless you're trying to merge in some harassment or NSFW matierial.
In which, case you should have fear.

And read the [**Code of Conduct**](/CODE_OF_CONDUCT.md), of course.

#### Step 5 - Merge your Pull Request

And then you're done!
Once everything has been reviewed and approved by at least one maintainer, your contribution will be merged into the `beta-draft` staging branch.
Periodically, those changes all get pushed live to the public master branch in coordination with other releases.

Tada!
You've contributed to an open source project!
You can put it on your resume, and look real cool to hiring managers.

## Formatting and Styling

Everything on *ZA* is written in plain-text using Markdown for formatting.
This may take a bit of getting used to at first, but we've got you covered.

If you're a software developer, there are some fantastic Markdown tools built into your IDE.
If you're not comfortable using the dev tools, I recommend checking out free Markdown editors like [Dillinger](https://dillinger.io/) or [Obsidian](https://obsidian.md/).

### Brief overview of Markdown

Modern word processors like Microsoft Word or Libre Office have a ton of options for styling text with different fonts, colors and layouts.
For our purposes at *ZA*, most of those features only cause problems.
Markdown simplifies the process by removing all but the essential styling options, and asks you to type them out manually in plain text.
When first using Markdown, it feels a little messy, especially when you don't remeber what the different symbols mean.
But a day of practice solves that problem.

There is a ton of really helpful documentation of how Markdown works.
Rather than trying to reinvent the wheel here, I recommend you go check out these two links:

Start with the [Markdown Basic Syntax](https://www.markdownguide.org/basic-syntax/), and graduate up to only needing the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/) once you get the hang of it.

Here's an example.
I can write this:

```markdown
**Welcome to *ZA*!**

This is a [link to Google](https://www.google.com).

- And here's a list

1. And a numbered list
1. A second number
```

And the output is:

> **Welcome to *ZA*!**
>
> This is a [link to Google](www.google.com).
>
> - And here's a list
>
> 1. And a numbered list
> 1. A second number

From a programming and publishing perspective, the main reason we use Markdown is because it plays very nicely with the internet, eBooks and traditional publishing.
No additional formatting and style changes need to be made before submitting a document for final presentation.
Since we're a community of volunteers, less work before presentation means more visibility (and therefore hopefully adoption).

### *ZA* Styling Conventions

Now that you've got an idea of what Markdown is, and the simplified styling it provides, let's take a look at how we use the different styling options.

| **Markdown** | **Name** | ***ZA* Usage** |
|-----------------|--------------------|-----------------------------------------------------------------------------------------------------------------------|
| `#` | Main Header | There is only one of these in the entire document. It's pulled by the backend to generate the title of the article. |
| `##` - `######` | Additional Headers | All additional header levels are automatically pulled for generating a 'Table of Contents' for easier navigation |
| `*text*` | Italic and Bold | We use the `*` symbol to surround words for italics and bold. Not the `_` symbol. |
| `-` | List | Lists are started with the `-` symbol. |
| `⮐` | Line Break | This is a weird one, but still important. We make a new line after every single sentence. Markdown will render the text as one large paragraph, but the data is stored on multiple lines. This convention helps track changes to articles over time. |

GitHub tracks changes to all documents across time, along with the person that made those changes.
But it can only keep track of that on a line by line basis.
So by breaking paragraphs into individual lines, we allow GitHub to track changes on a sentence by sentence basis, rather than a paragraph basis.

A double line break is used instead of a single line break to create new paragraphs.

And in case you were wondering, the above two paragraphs look like this behind the scenes. Note how the first paragraph is on three separate lines:

```markdown
GitHub tracks changes to all documents across time, along with the person that made those changes.
But it can only keep track of that on a line by line basis.
So by breaking paragraphs into individual lines, we allow GitHub to track changes on a sentence by sentence basis, rather than a paragraph basis.

A double line break is used instead of a single line break to create new paragraphs.
```

## File Naming

### Filenames

Because *ZA* has a lot of files across many different kinds of discussions, we use a simple but strict naming convention to make sure everything is accounted for.

Here are a few examples of possible filenames:

- `202002041148-dekuTreeAnalysis.md`
- `201912312013-responseToChartDependencies.md`
- `202106131347-botwMenu.jpg`

There are three required elements to each filename.

- Unique ID timestamp followed by a hyphen
  - Every filename starts with a timestamp following the convention `YYYYMMDDhhmm`, using the 24hr convention for the hours.
  For convenience sake, use the current time displayed on your computer's clock.
  For example, If I were to create a timestamp for right now it would be `202002041144` which is the year 2020, month 02, day 04, hour 11, minute 44 - **11:44 am, February 4th, 2020**.
  This is a simple way to create meaningful and consistently lengthed unique IDs for each file without needing to use a third party tool.
  - The timestamp is to make the file computer readable.
  Even if the description is the same, the computer can differentiate between the files because of the unique ID.
- Camel case file description
  - The actual description is to make the filename human readable.
  Something short and descriptive is best.
  - Camel case naming is a programming convention that removes the need to add spaces between words when it's part of a filename or variable.
  The first word is lower-case, and each word following is capitalized.
  For example, if I analyzed the Deku Tree from *Ocarina of Time*, I might want to call it '*Deku Tree Analysis*'.
  To convert it to camel case, I would remove the spaces and lower-case the first word - `dekuTreeAnalysis`.
- The file extension
  - Because modern operating systems default to automatically adding filenames to the end of your files, it's easy to forget to add it manually.
  Specifically be careful to always remember the `.md` extension for Markdown text files.
  The computer uses the `.md` extension to format the text correctly.
  
  ## Getting Help
  
  Okay, I know that was a lot to take in.
  But never fear, I wrote this as a continuing reference, not as a one-off page for you to read and memorize.
  
  Also, when you open a Pull Request, the maintainer (such as myself) are there to catch any formatting or style errors.
  Try to catch it yourself, but don't stress too hard.
  The worst thing that could happen is that we ask you to rename a file or two before approving the Pull Request.
  
  If you need any additional help, remember you can always jump into the [Issues](https://github.com/open-lore/zelda-archaeology/issues) section (either by searching or asking yourself). Or you can drop your questions over on [Discord](https://discord.gg/PgebRQw) if that's more your speed.