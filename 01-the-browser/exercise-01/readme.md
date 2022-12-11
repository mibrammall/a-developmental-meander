# Lesson 1

## Explanation

This document is written in [markdown](https://en.wikipedia.org/wiki/Markdown). Markdown is ironically named, because it is a [markup language](https://en.wikipedia.org/wiki/Markup_language). One intention in its design is that it should be readable without needing an external program to read it. Most markup languages do not share this design goal.

One of these other markup languages is [HTML](https://en.wikipedia.org/wiki/HTML), and we will get started with manipulating it rather than understanding it deeply. In this set of exercises, we will manipulate a plain HTML document and add to it some [semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantics). Writing HTML semantically is not necessary, but it is polite to do so. [Screen and assistive readers](https://abilitynet.org.uk/factsheets/introduction-screen-readers) are helped by semantic HTML. The presence of semantic HTML also may influence how a search engine ranks a website by aiding decisions into what are the important parts of a webpage are. If everything is important, nothing is important.

## Getting started 

Feel free to use whatever editor and method of displaying things on the screen that you like, but we will recommend that [Visual Studio Code](https://code.visualstudio.com/) is used.

As for extensions, the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). This will allow us to preview a static HTML page and its resources without having to install too much on our system. We will have to install more tools later, but we postpone this discussion until we need it.

## Exercises

We have in `index.html` a rather bare HTML document. We are going to make it a little less bare. If you don't know how to do something, it's encouraged that you use a search engine to find out. Using a search engine effectively is a good skill to have for software development, as is the ability to read information critically. Don't copy and paste from sites like stackoverflow blindly, but understand how the solution you're interested in solves that problem that you have.

The aim of these exercises is to develop an appreciation of semantic HTML. Try and work through them without peeking, but if you get stuck because either you don't follow or the instructions are unclear, there is an example solution [here](example-output.html)

1) Find out how to add a title tag to the `<head>` tag. What do you notice about the tab in the browser?

2) Type something between the `<body>` and `</body>` tag and view the webpage. What do you notice?

3) HTML is formed from nested tags. These are special formatting instructions that the browser understands and can do different things with. What happens to the output of 2) if you surround it with a `<h1>` tag?

4) Wrap the `h1` tag inside a `header` tag. This doesn't do much in terms of what we can see in the browser, but it makes our HTML more semantic.

5) Below this newly added `header` tag, add an `article` tag. Below this, add a `section` tag.

6) In the `section` tag, add a `h2` tag. This indicates that we have a second level heading. As a rule, there should only be one `h1` heading per webpage. 

7) To write a paragraph, we usually use a `p` tag. Create a `p` tag just below the closing `h1` tag.