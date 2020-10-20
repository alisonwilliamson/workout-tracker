# workout-tracker
An app that uses a Mongo database with a Mongoose schema and handle routes with Express.

## Installation
To run on localhost:3000 run npm i to install dependencies and then open your terminal and run node server.js. 

## User Story

* As a user, I want to be able to view create and track daily workouts. I want to be able to log multiple exercises in a workout on a given day. I should also be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, I should be able to track my distance traveled.

## Business Context

A consumer will reach their fitness goals more quickly when they track their workout progress.

## Acceptance Criteria

When the user loads the page, they are given the option to create a new workout or continue with their last workout.

The user can:

  * Add exercises to a previous workout plan.

  * Add new exercises to a new workout plan.

  * View the combined weight of multiple exercises on the `stats` page.