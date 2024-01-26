
## Slowly down before the finish line
Something I personally try to remember is that, nothing is ever quite as urgent as it's made out to be. Regardless of the circumstances, if the code you wrote is bad it only reflects poorly on you. Which is why I wrote this little checklist for myself to go through before merging a pull-request.


## Pull Request Checklist

- [ ] Did you run it end-to-end? (DYaRI)

- [ ] Did you take the time to write unit-tests for new methods you've added?

- [ ] Will this PR address the acceptance-criteria on the work item?

- [ ] Is the overall code in a better state than you found it?

- [ ] Have you thought about and planned for edge-cases related to this piece of work?

- [ ] Have you run a linter? Does the linter return no complaints?

- [ ] Has the documentation related to the change been updated?
	- [ ] Since there likely isn't any docs... have you wrote some?

- [ ] Do all of the original tests pass?

- [ ] Do your new tests pass?


I put together this checklist specifically keeping in mind things that have bit me in the ass before. Hopefully having a simple reminder before clicking that enticing merge button will lead to better, more robust code.
