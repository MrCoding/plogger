# plogger
A fork of the simple Plogger Gallery

Will be updated to be compatible with PHP 5.5 and current MySQL.
Currently a copy of Version 1.0 RC1. Old README below.

##INSTALLATION
To install, upload all of the files in the Plogger distribution to your web server.
Next, create a MySQL database and user from your web hosting control panel.
Then, run the install script (/plog-admin/_install.php) in the web browser of your choice.
The script will guide you through the rest of the installation process.

##INTEGRATION
To integrate Plogger into your website, place the following PHP statements in the .php
file you wish display the gallery in:

First line of the .php file
  <?php require("path/to/plogger.php"); ?>
In the HEAD section
  <?php the_plogger_head(); ?>
In the BODY section where you want the gallery
  <?php the_plogger_gallery(); ?>

Version: 1.0-RC1
