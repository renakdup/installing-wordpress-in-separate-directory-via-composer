# Installing WordPress via Composer in a separate directory
Example of using Composer for installing WordPress core in a separate directory of your project.  

Installing WordPress in a separate directory is a variant of installing WordPress via Composer where we place all the core files in a separate directory, away from the project files.

This option has its advantages and disadvantages you can take a look at it in the article below.


## Installation
- Install Composer locally or you can use docker container and run commands inside a container   
  `docker run --rm -it -v "$PWD":/usr/src/myapp -w /usr/src/myapp pimlab/composer:2.0.0-alpha3-php7.4 sh`

- Then you can run composer commands inside a container.   
Run `composer install`

- Fill consts of connection to DB in the `wp-config.php`
- Visit adminpanel `/wp/wp-admin`
---

### For more information you can read articles:
[Install WordPress via Composer - EN](https://wp-yoda.com/en/wordpress/installing-wordpress-via-composer/)  
[Install WordPress via Composer - RU](https://wp-yoda.com/wordpress/ustanovka-wordpress-cherez-composer-2/)
