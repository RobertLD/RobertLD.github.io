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
3. Simple chore management site for families, gamified. Created with the Phoenix framework + Elixir
5. Alternative to Apache NIFI in Elixir taking advantage of it's fault-tolerance
6. Animal Breeding software to keep track of animals, genes, expenses, etc.
7. Resume Screening tool that automatically screens candidates based on search criteria and otherwise.
	- Integration with various job boards to find applicants before they even apply
8. Dog/Parrot training clicker; one button app
9. Feed reminder for animals that are irregularly fed
### AR/VR Applications
1. Simple Pomodoro timer for VisionOS.

### Micro Applications
 1. A simple Phoenix Liveview website that let's you create a poll and send it to your friends
 2. Gmail (Chrome Extension) to help organize your inbox automatically 
 3. Home investment calculator and simulator

### Non-software services
1. Software Development newsletter (very original, I know)
2. Programming course on Cousera or alternatives

### Machine Learning
1. LLM trained specifically on the AST representation of a specific programming language.
2. NSFW Image generation for a small fee


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
9. Modern Terminal multiplexer, with sane defaults. To replace Tmux

### Interesting
1. Workflow engine that supports job dependencies, retries and priority
2. RSS Feed reader that runs as a service and saves the text as blobs in a blob storage mechanism (db?)
3. Write a dataframe library similar to polars or pandas but for a language that doesn't have one
4. Horse Betting (or any other) sports betting with a Machine Learning backend
5. Trading Model built to trade relatively illiquid markets (OTC stocks, Watches, Wine, etc.)
6. Pomodoro timer that sends a server-sent event when time is up. Or potentially using websockets?
7. A terminal  based Tamagotchi like creature that you maintain through terminal based means. It should interact with the user in some fashion when healthy or unhealthy
8. A AWS lambda like service where you can upload elixir functions and set them to run on a timer. They will then get executed on the backend according to your time (basically a cron manager.)
9. Database that is good at one thing; clustered indexes on time-series data

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
3. Detecting Illicit substances in images (OpenCV)

### Programming Languages
1. Extending a compiler that doesn't support Tail-Call optimization... by adding tail call optimization.
2. Create a debugger for a language that currently has terrible tooling.


## Projects suggested to me
---
These are a collection of projects from peers of mine who have suggested an idea to add to this list.

1.  > Training a model on a dental X-ray that can detect what type of implant someone has in
   \- Louis DeRienzo, 2024
