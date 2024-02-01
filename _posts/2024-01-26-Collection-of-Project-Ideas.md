---
tags: software
format: list
---


I regularly find myself short on project ideas to explore in my free time. I'm making an effort here to keep track of project ideas I've had or discovered online and am considering pursuing.

# Project Ideas
Being a person with restless ADHD, I always need a coding project to work on. This can be challenging when my enthusiasm is short-lived and the web lacks project suggestions for those that aren't beginners. I created this list to compile my project ideas as they occur to me. These are things that I would enjoy implementing, arranged as well as I can.


## Potentially Marketable Projects
---
Out of all the ideas, I think these projects have the most potential to make it to market and become successful products or services.

### Consumer Applications (Apps, etc.)
1. Build a mobile app that reminds users if they've taken their pills today or not
2. Tenet management system for landlords

### Machine Learning
1. LLM trained specifically on the AST representation of a specific programming language.


## Personal Projects
---
These are projects that are useful to me personally or offer some simple functionality that I desire on a day to day basis. Alternatively, it could just me something I'm interested in

### Directly useful for me
1. Remote SQL driver server. Spin up the simple web-server and let it handle the querying and sending the results back. For databases without HTTP support
2. Website that is a decision matrix for which programming language to learn next based on user provided information. Tech: Golang/ HTMX
3.  Personal Finance simulator and decision maker
4. PQL and SQL wrapper around parquet files with a GUI interface similar to datagrip.
5. Bitbucket plugin in clojure to add git-semver to PullRequests
6. VSCode plugin to add Automatic SQL formatting for strings
7. CLI application to read/parse markdown data and fail a build on grammar mistakes, with configurable proof-reading capabilities. Would be used as a github action for github.io pages/blogs.
8. Gmail extension that creates a weekly digest from emails you tell it to listen to. Basically  combine all newsletters into one newsletter

### Interesting
1. Workflow engine that supports job dependencies, retries and priority
2. RSS Feed reader that runs as a service and saves the text as blobs in a blob storage mechanism (db?)

### CLI Applications
1. CLI application called `td` that takes the input and makes a todo item in the daily obsidian note with the timestamp of when it was made
2. OpenAPI client generator. Parse a swagger document and generate a client for interacting with that specific API.
3.  Parquet/CSV file combiner and splitter cli tool

### Pre-commit Hooks
1. Linting commit messages
2. Linting on argocd app-settings to confirm nothing is funny. An interesting technology to use could be Perl 6 or Raku.

## Simulations
1. Evolution simulation game with simple plants and animals (Golang?)
2. Market Trading Simulator using Agents with simple Neural Networks existing as Coroutines. They interact real-time with a global market data-structure
3. Agents that use emails to interact with the world (game over SMTP)

### Pre-commit Hooks
1. Git commit message linting and spell checking. Make assertions about how commit messages should look


## Exercises in Learning
---
Projects whose purpose is to expand my knowledge on a particular topic or series of topics. These projects could fit into other categories as well, but for my purposes they are strictly educational.

### Functional Programming
1. Using elixir/F# to build a simple website with as little dependency on JavaScript as possible


### Machine Learning
1. LLM trained specifically on the AST representation of a specific programming language.
2. Anomaly Detection ML model build on top of Loki logs

### Programming Languages
1. Extending a compiler that doesn't support Tail-Call optimization... by adding tail call optimization.
2. Create a debugger for a language that currently has terrible tooling.


## Projects suggested to me
---
These are a collection of projects from peers of mine who have suggested an idea to add to this list.

1.  > Training a model on a dental X-ray that can detect what type of implant someone has in
   \- Louis DeRienzo, 2024
