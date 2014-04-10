#Drupal Boilerplate#
-

Drupal boilerplate is not a module. Instead it just serves as a directory structure for
starting a new drupal site. The idea behind Drupal boilerplate came from working on so many
different sites which each follow their own development practice, directory structure,
deployment guidelines, etc...

Drupal boilerplate tries to simplify starting a new site by having the most common
directory structures and files already included and set up.

##Getting started##
You can start by [downloading](https://github.com/TallerWebSolutions/drupal-boilerplate/zipball/master)
this project. Once you download it you will find that every folder contains a readme.md file.
This readme.md file has been extensively documented to explain what belongs
in that specific directory.

Here's a breakdown for what each directory/file is used for. If you want to know more please
read the readme inside the specific directory.

* [docroot](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/master/docroot)
 * Where your drupal root should start.
 * The settings.php is not ignored by the GIT, it's expected to use an include file, like: settings.local.php
   where all the local configurations will be.
* [drush](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/master/drush)
 * Contains project specific drush commands, aliases, and configurations.
* [results](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/master/results)
 * This directory is just used to export test results to. A good example of this
   is when running drush test-run with the --xml option. You can export the xml
   to this directory for parsing by external tools.
* [scripts](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/master/scripts)
 * A directory for project-specific scripts.
* [tests](https://github.com/TallerWebSolutions/drupal-boilerplate/tree/master/tests)
 * A directory for external tests. This is great for non drupal specific tests
 such as selenium, qunit, casperjs or cucumber.
* [databases](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/master/databases)
 * The databases directory is used to place dumps from the persistant storages like MySQL,
 MongoDB and others, used for the initial boot in new environments.
* [configs](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/master/configs)
 * The configs directory is used to place configurations of other softwares like Apache Solr,
 Redis, MongoDB and others.
* [.gitignore](https://github.com/TallerWebSolutions/drupal-boilerplate/blob/master/.gitignore)
 * Contains the a list of the most common excluded files.

Built by Robots&trade;
