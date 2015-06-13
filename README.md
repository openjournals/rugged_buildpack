# Heroku Cerdar Buildpack for Injecting Rugged Dependencies

Installs libicu, which is needed by charlock_holmes, and cmake, which
is needed to install rugged.

This buildpack doesn't do anything else, so you'll want to use it
with heroku-buildpack-multi and heroku-buildpack-ruby to get the 
full heroku ruby platform.

