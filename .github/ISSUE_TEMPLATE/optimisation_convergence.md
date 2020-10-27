---
name: Optimisation convergence
about: An optimisation problem is not working as well as expected
---

> Describe the symptoms of the bad convergence here.

## Checklists of things to try

### Debug steps

- [ ] Extract what the optimizer sees exactly
- [ ] Extract the gradients

### Things to try

- [ ] Avoid 0s of variables
- [ ] scaling of variables
  - [ ] only positive?
  - [ ] All between 0-1?
- [ ] gradients
  - [ ] step type
  - [ ] step sizes
