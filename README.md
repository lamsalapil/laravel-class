<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<h1> Let's Start. </h1>

<h2>Firt steps</h2>

<p>
<h3>Download and Install.</h3><br>
<a href="https://www.apachefriends.org/download.html">-> xampp </a><br>
<a href="https://getcomposer.org/download/">->Composer</a><br>
<a href="https://code.visualstudio.com/">->Visual studio code</a> <br>
<a style="color=green;">-->other code editor</a>

</p>

<p>
Open terminal or CMD
go first in this Path 
->  C:\xampp\htdocs
then
create a project in laravel

~~~
composer create-project laravel/laravel myfirstproject
~~~
open that project we have created our first project

~~~
path
C:\xampp\htdocs\myfirstproject
~~~

For learn we should download templete in laravel project.
<a href="https://www.creative-tim.com/product/material-dashboard-laravel">Download Material dashboard laravel</a>

after install Material dashboard

create a database:
-Open xampp
-CLICK *new
-Create Database:XYZ

~~~
Change .env

> DB_DATABASE=XYZ
~~~

Migrate all database
~~~
Open Terminal

>php artisan migrate

~~~

~~~
Route::get('/Product','App\Http\Controllers\HomeController@getproduct')->name('getproduct');
            [______]    [_________________________________] [______]           [__________]
           url name          path of controller             function            route name

~~~

</p>