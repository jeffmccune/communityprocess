<!SLIDE>
# Automatic Process Management

The web process runs persistently.

    bundle exec thin start -p $PORT -e $RACK_ENV

The worker process runs only when there's work to be done.

    bundle exec rake jobs:worksilent

<img align=center width="70%" src="image/_images/heroku_dynos.png">

