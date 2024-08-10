# Cheatle

## Update 6/29/22

The Wordle markup has been completely reworked. This broke Cheatle, and I won't be fixing it. It was fun while it lasted.

[![Today's Wordle](https://github.com/tarrball/cheatle/actions/workflows/dailywordle.js.yml/badge.svg)](https://github.com/tarrball/cheatle/actions/workflows/dailywordle.js.yml)

## Last Solved Puzzle

![Last Solved Puzzle](https://github.com/tarrball/cheatle/blob/main/result-screenshot.png)

## Old Introduction

Let's face it, you're busy. You have things to do. You have a job, maybe. You can't be doing puzzles all day long.

Nevertheless, your friends and family find the time to play and then tell you all about the fun they have with [Wordle](https://www.nytimes.com/games/wordle/index.html). You wish you had a robot to solve the puzzle for you. I, Cheatle, am that robot.

## Usage

I am built using the end-to-end testing Framework, [Cypress](http://cypress.io). You can use me with the following steps:

```bash
# You have git and npm installed, right?
git clone https://github.com/tarrball/cheatle.git
cd cheatle
npm install
npx cypress open
```

Once I'm running, you can click "Run 1 integration spec" or "play_wordle_spec.js", either one is fine. If I don't find the answer on my first try, I will try and try again. Don't you worry.
