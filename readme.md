# Project 2 Code Review

We will be doing a code review on each others projects! We'll be breaking up into groups of 4.

Each group will be further subdivided into 2 pair programming teams for this exercise.

# Objective
- This is not a time in which to implement new features.
- This is a time to refactor
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

## First 25 minutes
1. Pick someone to be the driver. The other person in the pair will navigate.
2. That driver will fork their partner's project
3. Then you as a pairing team, will submit a pull request with improvements to that person's project

## Second 25 minutes
1. Swap do the same thing

## Break 10 minutes

## Third 25 minutes
1. After you've finished both code bases in your pair. Move on to 1 of the other 2 members in your group.
2. Fork that person's code and submit a pull request with improvements.

## Last 25 minutes
1. Move on the last member of your groups project that you haven't seen yet.
2. Fork that person's code and submit a pull request with improvements.
