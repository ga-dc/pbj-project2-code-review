# Project 2 Code Review

For this exercise, we'll be forming pairs, and reviewing each other on our
projects!

The goal is to take some time to improve your code, with the help of a dedicated
second pair of eyes. Each team member will get ~40 minutes of help improving
their code.

**Note**: you should **not** be implementing any new functionality during this
exercise, only **reviewing / refactoring existing code.**

## Before You Begin
Push the latest copy of your project to GitHub, so your partner can give you the
most accurate feedback possible.

## Objective
- Imagine trying to get this code presentable to an employer.
- Focus on code quality/maintainability - Things you could look for:
  - Code Indentation
  - look for places where you could utilize associations instead of complex AR queries
  - remove code duplication(extract methods if you can)
  - abstract program functionality into methods for clarity
  - ensure CSS selectors are over arching concepts instead of specific elements
  - remove logic from views to controller or model
    - database queries belongs in controller
    - business logic belongs in model

## Schedule

### 4:00 - 4:30: Review Partner's Code

Both of you will be working 'solo' on this portion:

1. Fork your partner's repo
2. Clone the fork down to your computer
3. Open the code in atom.
  * No need to setup the DB or run the app... just look at the code
4. Spend ~20 minutes leaving comments on your partner's code.
  * Look for potential bugs, and other things outlined in the [code quality guidelines](code_quality_guidelines.md)
5. When done, add, commit, and push to your fork
6. Make a pull request from your fork to their repo
7. Go to **this repo** (`project2-code-review`) and create an issue with a link to your pull request


### 4:30 - 4:45 Discuss Partner A's Code

Pick one partner and spend 15 minutes discussing the comments left on that
partner's code. You can even pair on implementing some suggestions if you have
time.

### 4:45 - 5:00 Discuss Partner B's Code

Spend 15 minutes discussing the comments left on the other partner's code. You
can even pair on implementing some suggestions if you have time.

### 5:00 - 5:05 Document your PR w/ Instructors

Each partner should open an issue on **this repo**. In the issue, include a
link to the Pull Request that you created, and one thing that you learned in
completing this exercise.
