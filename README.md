# Rails Stupid Coaching

A tiny Rails app that plays a lazy life coach. You ask a question and the coach answers based on how you asked it.

Built during the [Le Wagon](https://www.lewagon.com) AI Software Development bootcamp (2026) as a first introduction to the Rails request cycle without a database.

> Status: work in progress. The Rails app is generated and the routes, controller and views are the next step.

## How the coach replies

| You say | Coach says |
| --- | --- |
| `I am going to work` | "Great!" |
| A question ending with `?` | "Silly question, get dressed and go to work!" |
| Anything else | "I don't care, get dressed and go to work!" |

## Planned structure

- `GET /ask` shows a form with a question field
- `GET /answer` reads the `question` param and renders the coach's reply
- `QuestionsController` with `ask` and `answer` actions

## Tech stack

Ruby on Rails 8, ERB views, HTML and CSS.

## Run it locally

```bash
git clone https://github.com/StefanoIncisa/rails-stupid-coaching.git
cd rails-stupid-coaching
bundle install
rails server
```
