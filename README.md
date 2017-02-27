# Geek World

Development of a blog application using Google App Engine.

![blog demo](https://github.com/anmolmann/multi-user-blog/blob/master/images/project-demo.png)

##### This document is intended to guide you through implementing the entire project.

## Table of contents

- [Quick Start](#quick-Start)
- [Documentation](#documentation)
- [Setup](#setup)
- [Usage](#usage)

## Quick Start

Let's get Started

- Blog includes the following features:
	- Front page that lists blog posts.
	- A form to submit new entries.
	- Blog posts have their own page
- Users are only able to edit/delete their posts. They receive an error message if they disobey this rule.
- Users can like/unlike posts, but not their own. They receive an error message if they disobey this rule.
- Users can comment on posts. They can only edit/delete their own posts, and they should receive an error message if they disobey this rule.


## Documentation

The two main technologies used in this project are Google App Engine and Jinja2.

## Setup

- Install Python if necessary.
- Install Google App Engine SDK.
- Sign Up for a Google App Engine Account.
- Create a new project in Google’s Developer Console using a unique name.
- Follow the App Engine Quickstart to get a sample app up and running.
- Deploy your project with gcloud app deploy.
 	- View your project at unique-name.appspot.com/login.
- When developing locally, you can use dev_appserver.py to run a copy of your app on your own computer, and access it at http://localhost:8080/.

## Usage

Follow this url:
- [Geek_World](https://udacity-158017.appspot.com/login)

