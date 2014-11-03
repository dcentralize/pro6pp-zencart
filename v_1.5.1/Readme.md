What these folders represent?
=============================

The folders contain the files that need changes.

* `add` = Has files that should be added to your installation.
* `modify` = Contains the differences of files that should be modified

The `split_street_housenumber.sql` script in the root of this folder is for existing shops only. You can execute it from the Admin section at `Tools -> Install SQL patches`.

__Note1:__ Always backup your database before executing any new queries.

__Note2:__ Deploy the patches on a staging environment and not on the production.
