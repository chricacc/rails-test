# This is a test app on Ruby on Rails

I developed this really quickly to test the basics of Rails.
I followed the course from "freeCodeCamp.com" on YouTube, and tried to push it a bit further.

//TODO : explore REST implementations
//TODO : apply TDD
//TODO : deploy this using Docker on my own server
//TODO : discover Rail's tooling regarding monitoring/tracing/alerting

## Installation

- Install Rails 8.0.1 (https://guides.rubyonrails.org/install_ruby_on_rails.html)
- Clone this repository
- Run these commands from the source repository :
```bash
bundle install
rails db:migrate
rails s
```
- Navigate to http://localhost:3000

At this point you should be able to :
- Sign up
- Sign in
- Use the basic CRUD actions on the **Friend** model
- See data from any other users you will create, without being able to Update/Delete them

## Notes
As this project is not intended to be ran live : 
- No real database is configured
- No real SMTP server is configured

