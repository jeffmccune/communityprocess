<!SLIDE>
# How it works

The Puppet Webhooks code running in Heroku receives the HTTP POST and:

 1. Github posts JSON to our Heroku app
 2. Persist the JSON to a Delayed Job queue
 3. Start a Delayed Job worker process using workless gem
 4. Data is posted to Trello in a matter of seconds

<img align=center width="40%" src="image/_images/clock.jpg">
