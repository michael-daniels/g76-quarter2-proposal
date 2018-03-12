# Q1 Project Proposal

* Fork this repo and update this README file with your proposal.
* Make sure to preview your proposal in a markdown preview and [use valid markdown syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/)
  * Unformatted/unreadable proposals will be rejected

## Project Description
A productivity application for managing to-do tasks, workflows, sales pipelines, and anything else you can think to use it for.

## What problem does your project solve?
Our application will give people a task management platform that relies on a board, column, and card system to help them organize information. It will provide enough flexibility for it to be used for many different needs. It can help them manage their day to day tasks, manage workflows, create sales pipelines, etc.

## Who has this problem?
Anyone that doesn't have an efficient way of organizing their daily tasks.

## How will your project solve this problem?
Our application will use a system of boards, columns within those boards, and cards within said columns to organize information.

## What inputs does it need?
Board names, column names, and card names.

## What outputs does it produce?
It will output the information put into it and allow the user to structure it however they prefer.

## What technologies do you plan to use?
HTML5, CSS3, JavaScript, Bootstrap 4, Node.js, Express, Knex, PostgreSQL

## Feature list
Create boards, columns, and cards.
Update boards, columns, and cards.
Delete boards, columns, and cards.
Move cards between columns for workflow functionality.
Account owners can set individual boards to private or public
Public boards are shareable by unique URL.

User authentication:
* Users not logged in can only see boards set to public and cannot update or delete content on any boards.
* Logged in users have full CRUD capability within their own boards.
