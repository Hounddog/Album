
# Sample Album Modulefor Zend Framework 2

## Introduction

Album is a sample Module based on the (Getting Started)[http://framework.zend.com/manual/2.0/en/user-guide/overview.html] guide framework.zend.com .

## Installation

### Main Setup

1. Clone this project into your `./module/` directory and enable it in your
   `application.config.php` file.

```php
<?php
return array(
    'modules' => array(
        'Application',
        'Album',
    ),
    'module_listener_options' => array(
        'config_glob_paths'    => array(
            'config/autoload/{,*.}{global,local}.php',
        ),
        'module_paths' => array(
            './module',
            './vendor',
        ),
    ),
);
```

Copy the These files
 `module/Album/config/database.local.php.dist` to `config/autload/database.local.php`
 `module/Album/config/global.php.dist` to `config/autload/global.php`

 ###Usage
 Browser to the album page

 `your-domain-name/album`