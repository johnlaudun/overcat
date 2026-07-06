---
layout: post
title: "Probabilities"
---

A fair portion of simulating reality is based in probabilities both because users need to have choices—there’s no need for probabilities in a novel because there’s only one path—and because games need to have variability if they are going to offer meaningful opportunities for replay. 

Also, games are almost by definition a safe environment in which to take risks, and those risks must result in success, failure, or something interesting in between. 

There are a lot of ways to generate probabilities, but rolling dice or drawing cards are the two with which most players are familiar and a good game harnesses that familiarity in ways that surprise, and delight, its players. 

*I have an example in a follow-up post to this one, but, for now, let’s take a look at the basics.*

## Dice Probabilities

A single die, whether it is 4-sided, 6-sided, 8-sided, 10-sided, 12-sided, or 20-sided (just to name the most common dice), produces an equal probability of its outcomes: there is a 1-in-6 chance of rolling any number, 1 through 6, when rolling a 6-sided die. 

But the minute you add a die and begin to create a dice pool from which you sum numbers, you have the beginning of a bell curve in which some outcomes are more likely than others. E.g., “lucky seven” is lucky by simply being the most probably outcome of rolling two dice, 16.67%, with all the other outcomes trailing off on either side of the curve, eventually diminishing to 2.78% for either 2, “snake eyes,” or 12, “box cars.” ([AnyDice](https://anydice.com) is a great website to check out possibilities and outcomes.) 

But you need not sum a dice pool. You can also, for example, count the number of successes, often called “hits” in combat-oriented games or keeping certain dice, like producing various “hands” in Yahtzee. 

One of the dice pool systems I am trying out in *Metal Boxes* is the d66 system, where you roll two die, usually of different colors (but you could just as easily read them left-to-right, if you like), such that instead of having 11 possible outcomes when summing a roll of two dice, you actually have 36 outcomes: (1,1), (1,2), (1,3) … (6,5), (6,6). 

I am using such a system to generate spaces within a ship, with one die determining the width of a space and one its length. (Or X and Y for you cartesianists.) If either die is a 1, then a player has rolled a corridor, as opposed to fuller-sized compartments. I wanted to know what the probability of the player rolling a corridor was in such a system.

## Probability of Rolling a One with Two Dice

Okay, so as noted above, when rolling two six-sided dice, there are a total of 36 possible outcomes. This is calculated as 6 outcomes from the first die × 6 outcomes from the second die for a total of 36.

To find the probability of rolling at least one '1', we can count the possible outcomes in which a 1 occurs:

- Outcomes where the first die is a '1': (1,1), (1,2), (1,3), (1,4), (1,5), (1,6) — 6 outcomes.
- Outcomes where the second die is a '1': (2,1), (3,1), (4,1), (5,1), (6,1) — 5 additional outcomes.

This gives us a total of 11 possible outcomes in which a 1 is featured:

The probability of rolling at least one '1' is calculated as 11 in 36 which we can calculate using simply math: 11 / 36 =0.306 x 100 = 30.6%. 

30% is closer to one-third than I would have initially imagined. For my own use, that might mean more corridors than I want, or, maybe just maybe it means, given the likelihood of rolling a corridor, that I need to make corriros more interesting.
