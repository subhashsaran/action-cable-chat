## Chatty: The Rails 5 + Action Cable Example App

This is a really simple chatting app to demonstrate one implementation of Action Cable in a Rails 5 app. Users can sign up/log in with a username and create a chatroom or choose from an existing one to start real-time messaging.

For a walk-through of this application, and to learn more about Action Cable (it's awesome, btw You can view live deployed  application [here](https://action-cable-example-app.herokuapp.com/), or you can use the button below to deploy your own version (you'll need a Heroku account for that).

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Running Locally

You'll need:

* Ruby 2.3.0
* Postgres
* Redis

Then, once you clone down this repo:

* `bundle install`
* `rake db:create; rake db:migrate`

And you're all set.


