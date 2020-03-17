# PHPtest

This is a laravel project

To run this you will need:

1)XAMPP

2)Composer(after installing composer you may need to restart you terminal)

3)Laravel

Next you will need to create an empty database named phptest
for that you need to open XAMPP, start Apache and MySQL, and then click on "admin" that is next to MySQL start
that will open a page in browser. There you can create an empty database by clicking databases and then inserting name "phptest" and then click "create".
In order to create the tables you will need to run a console command in project directory:
php artisan migrate



Then you can run a command in project directory:
php artisan serve

That will provide you with a server to view this project.
