Sage-Material-Design
The theme is a fork of Sage Starter Theme version 8.2.1 with Material Design implemented on top of Bootstrap.

Under construction! It's a dev repo!

Installation
Clone the git repo - git clone https://github.com/roots/sage.git and then rename the directory to the name of your theme or website.

If you don't use Bedrock, you'll need to add the following to your wp-config.php on your development installation:

define('WP_ENV', 'development');
Configuration
Edit lib/config.php to enable or disable theme features

Edit lib/init.php to setup navigation menus, post thumbnail sizes, post formats, and sidebars.

Theme development
Sage uses gulp as its build system and Bower to manage front-end packages.

Install gulp and Bower
Building the theme requires node.js. We recommend you update to the latest version of npm: npm install -g npm@latest.

From the command line:

Install gulp and Bower globally with npm install -g gulp bower
Navigate to the theme directory, then run npm install
Run bower install
You now have all the necessary dependencies to run the build process.
