laravel-admin

⛵laravel-admin is administrative interface builder for laravel which can help you build CRUD backends just with few lines of code.

Documentation | 中文文档 | Demo | Demo source code | Extensions

 Build Status  StyleCI  Scrutinizer Code Quality  Packagist  Total Downloads  Awesome Laravel

Inspired by SleepingOwlAdmin and rapyd-laravel.

Screenshots
laravel-admin

Requirements
PHP >= 7.0.0
Laravel >= 5.5.0
Fileinfo PHP Extension
Installation
This package requires PHP 7+ and Laravel 5.5, for old versions please refer to 1.4

First, install laravel 5.5, and make sure that the database connection settings are correct.

composer require encore/laravel-admin
Then run these commands to publish assets and config：

php artisan vendor:publish --provider="Encore\Admin\AdminServiceProvider"
After run command you can find config file in config/admin.php, in this file you can change the install directory,db connection or table names.

At last run following command to finish install.

php artisan admin:install
Open http://localhost/admin/ in browser,use username admin and password admin to login.

Configurations
The file config/admin.php contains an array of configurations, you can find the default configurations in there.

Backers
Thank you to all our backers! 🙏 [Become a backer]



Sponsors
Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [Become a sponsor]

         

Other
laravel-admin based on following plugins or services:

Laravel
AdminLTE
Datetimepicker
font-awesome
moment
Google map
Tencent map
bootstrap-fileinput
jquery-pjax
Nestable
toastr
X-editable
bootstrap-number-input
fontawesome-iconpicker
