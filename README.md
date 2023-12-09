###################
Url Shortener App
###################

Url Shortener App is a small prototype of bit.ly,goo.gl and similar type of url shorteners.
This app is made using CodeIgniter 3, Bootstrap 3 and Mysql.

*******************
Screenshots
*******************


Login

.. image:: url-app-assets\url-app-login.png
   :height: 300px
   :width: 400px
   :alt: Login screen


Sign up

.. image:: url-app-assets\url-app-signup.png
   :height: 300px
   :width: 400px
   :alt: Sign up screen

Home

.. image:: url-app-assets\url-app-shorten-page.png?v=1.1
   :height: 300px
   :width: 400px
   :alt: Home screen


Profile

.. image:: url-app-assets\url-app-profile.png
   :height: 300px
   :width: 400px
   :alt: Profile screen


History

.. image:: url-app-assets\url-app-history.png?v=1.1
   :height: 300px
   :width: 400px
   :alt: History screen
*******************
Server Requirements
*******************

PHP version 5.6 or newer is recommended.
Mysql 5+

It should work on 5.3.7 as well, but we strongly advise you NOT to run
such old versions of PHP, because of potential security and performance
issues, as well as missing features.

************
Installation
************

- git clone https://github.com/Brothin/URL-Shortener.git

- cd URL-Shortener

- add database setting in config/database.php

- add your own reCAPTCHA key in views/url-app/account/login.php and views/url-app/account/signup.php
Use google admin link `here <https://www.google.com/recaptcha/admin>`_ for more detail on reCAPTCHA.

- php -S localhost:80

- open the http://localhost/ in your browser to see the working app
