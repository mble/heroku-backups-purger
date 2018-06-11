# Heroku Backups Purger

This is a tiny script that parses the output of `heroku pg:backups` for a given app, and destroys all logical backup captures that are >= 30 days old.

It will eat your backups, and has auto confirmation. It requires the Heroku CLI installed, and a Heroku auth token set in order to complete the operations.

Use with extreme caution.
