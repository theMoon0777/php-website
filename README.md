# b1 web analytics
A ready to use collection of php scripts for web analytics.

## Why should I use b1 web analytics?
There are atleast 4 reasons:
* **it's server-sided**
* **it's independent**
* **it's open source**
* **it's free**

## Usage
Place b1webanalytics.php and b1settings.php in the same directory as your own php scripts.

Before using the scripts you need to modify the mysql parameters (user, password, database, host) in b1settings.php else nothing will work:

b1settings.php
```php
$b1_analytics_db = new b1_db_manager("user", "password", "database", "localhost");
```

After that all you need to do is including b1webanalytics.php in your own php scripts to start collecting data:
```php
include "b1webanalytics.php";
```

After collecting enough data you will see a simple report when opening b1statistics.php.

## Requirements
* PHP 5.0 or higher
* a MySQL Server
* (a webserver of course)

### PLEASE NOTE: b1 web tracking is still in development. We rely on your feedback!
