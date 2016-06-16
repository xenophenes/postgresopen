postgresopen
============

PostgresOpen Templates

These templates are used to override the templates which exist
in the pgeu-website code base / repo.  All of the actual django
website code is run by the pgeu-webiste code, whose repo is
located at:

  https://git.postgresql.org/gitweb/?p=pgeu-website.git;a=summary

and can be cloned from:

  git://git.postgresql.org/git/pgeu-website.git

Use:

  scripts/pushsite

to push the changes into the /srv/www dir.

There is also a scripts/pushsite.beta for pushing changes to the
beta directory.
