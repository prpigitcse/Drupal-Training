# Drupal-Training

## Lando installation
[Download link](https://github.com/lando/lando/releases)


## Drupal installation

> composer create-project drupal/recommended-project _[my_site_name_dir]_

It will download latest stable version of Drupal in your system

## Drupal Setup
> cd _[project_installation_directory]_

> lando init

it will ask basic setup question codebase folder, reciepe **(choose drupal 9)**
then it will ask for root directory (e.g. web) and app name

then run

> lando start

It will pull containers and create database and web server and will provide you vhosts.

> lando info

It will provide you information regarding your app.

For ssh into containers

> lando ssh

for mysql

> lando mysql

to run any drush command

> lando drush _[command]_

for composer

> lando composer _[composer command]_

for drupal console

> lando drupal _[command]_

for changing configuration of your web server, you need to edit **.lando.yml**
file. for details you can visit [Documentation](https://docs.lando.dev/config/drupal9.html#getting-started)

If you have changed anything in **.lando.yml**, you need to run
> lando rebuild

To delete containers

> lando destroy
