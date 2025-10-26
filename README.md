# Only Members

A Rails app with Devise authentication where users can create posts. Post authors are only visible to logged-in members.

## Features

- User authentication (Devise)
- Create and view posts
- Author names hidden from non-members
- Dynamic navigation based on auth status

## Setup

```bash
bundle install
rails db:migrate
rails server
```

Visit `http://localhost:3000`

## Tech Stack

Ruby on Rails 8.0.3 • Devise • SQLite3