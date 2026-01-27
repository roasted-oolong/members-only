# Members-Only Rails Auth

A private clubhouse web application where members can write anonymous posts. Built to learn user authentication and authorization in Ruby on Rails.

## About

This project implements a membership system where authenticated users can create posts and see author information, while non-authenticated visitors can only view posts without knowing who wrote them. The focus was on building secure authentication from scratch and understanding Rails session management.

## Built With

- Ruby on Rails
- PostgreSQL
- Bcrypt (password encryption)
- HTML/CSS

## Key Features

- User registration and authentication system
- Secure password hashing with bcrypt
- Session-based authorization
- Conditional content display based on authentication status
- Post creation restricted to authenticated users

## Getting Started

### Prerequisites

- Ruby 3.x
- Rails 7.x
- PostgreSQL

### Installation

1. Clone the repository
```bash
git clone https://github.com/roasted-oolong/members-only-rails-auth.git
cd members-only-rails-auth
```

2. Install dependencies
```bash
bundle install
```

3. Set up the database
```bash
rails db:create
rails db:migrate
```

4. Start the server
```bash
rails server
```

5. Visit `http://localhost:3000` in your browser

## What I Learned

Implementing authentication from scratch taught me how Rails manages sessions and secure password storage. The biggest challenge was understanding the flow of authentication checks across controllers and implementing proper authorization logic to conditionally render content based on user login status.

## Contact

Jenna Lee - [LinkedIn](https://linkedin.com/in/jenna-h-lee) - jennalee.tea@gmail.com

Project Link: [https://github.com/roasted-oolong/members-only-rails-auth](https://github.com/roasted-oolong/members-only-rails-auth)
