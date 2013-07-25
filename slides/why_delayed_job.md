<!SLIDE>
# Why use Delayed Job?

Heroku provides:

   * Small PostgreSQL databases for free
   * 750 hours of process time for free
   * 31 x 24 = 744 hours for the web process
   * 6 "extra" hours for free

The workless gem allows us to only run DJ worker processes when there's
actually work to be done.

Note: While this is all free of charge, a credit card is required to use the
Heroku API with workless.
