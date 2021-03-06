<!--
  this comment will be posted automatically by Cypress bot whenever someone opens a pull request,
  and it helps the reviewer from Cypress team to ensure the change is solid.
-->
Thanks for the contribution! Below are some guidelines Cypress uses when doing PR reviews.

- Please write \`[WIP]\` in the title of your Pull Request if your PR is not ready for review - someone will review your PR as soon as the \`[WIP]\` is removed.
- Please familiarize yourself with the PR Review Checklist and feel free to make updates on your PR based on these guidelines.

## PR Review Checklist

If any of the following requirements can't be met, leave a comment in the review selecting 'Request changes', otherwise 'Approve'.

### User Experience

- The feature/bugfix is self-documenting from within the product.
- The change provides the end user with a way to fix their problem (no dead ends).

### Functionality

- The code works and performs its intended function with the correct logic.
- Performance has been factored in (for example, the code cleans up after itself to not cause memory leaks).
- The code guards against edge cases and invalid input and has tests to cover it.

### Maintainability

- The code is readable (too many nested 'if's are a bad sign).
- Names used for variables, methods, etc, clearly describe their function.
- The code is easy to understood and there are relevant comments explaining.
- New algorithms are documented in the code with link(s) to external docs (flowcharts, w3c, chrome, firefox).
- There are comments containing link(s) to the addressed issue (in tests and code).

### Quality

- The change does not reimplement code.
- There's not a module from the ecosystem that should be used instead.
- There is no redundant or duplicate code.
- There are no irrelevant comments left in the code.
- Tests are testing the code’s intended functionality in the best way possible.

### Internal

- The original issue has been tagged with a release in ZenHub.
