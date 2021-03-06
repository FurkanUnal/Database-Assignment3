# Authentication with PHP and Flutter
- ## A authentication website written in PHP and Flutter. MySQL database is used to manage the data.
# Setup
 ## 1. Download `furkan_unal_110510264.zip` file. 
 ## 2. Go to `C:\xampp\htdocs` on your computer.
 ## 3. Create a new file and name it `phplogin`.   
 ## 4. Go to `phplogin` file you have just created.
 ## 5. Unzip the `furkan_unal_110510264.zip` here.
 ## 6. Now you should create a database. To do that, open XAMPP. Start Apache and MySQL modules. 
 ## 7. Click on Admin for MYSQL module and you will be navigated to the `phpMyAdmin` panel.
 ## 8. Create a new database and name it `authenticate`.
 ![htdocs](./screen-shots/phpmyadmin.png)
 ## 9. Go to `authenticate` and execute `ddl.sql`. This will create users table with the inital user (which is admin).
 ## 10. Make sure that you wrote the right database information in every PHP file (authenticate.php, register.php, getUserData.php, dataView.php, updateData.php).
 ![htdocs](./screen-shots/PHP_Initial_Information.png)
 ## 11. This application is a WEB APPLICATION which is created with Flutter. Therefore make sure that your emulator is an internet browser.
 ![htdocs](./screen-shots/Flutter_Web.png)
 ## 12. After that make sure you wrote correct `.php` file locations into flutter(dart) files. (login_screen.dart, register_screen.dart, home_page.dart). 
 ![htdocs](./screen-shots/loginscreen_php.png)
 ![htdocs](./screen-shots/registerpage_php.png)
 ![htdocs](./screen-shots/homepage_php.png)
 ![htdocs](./screen-shots/updatepage_php.png)
 ## 13. After all of that, app should be run smoothly.
 
 ## Pages
 ![htdocs](./screen-shots/login.png)
 ![htdocs](./screen-shots/register.png)
 ![htdocs](./screen-shots/homepage.png)
 ![htdocs](./screen-shots/updatepage.png)
 
 ## If you get this error. Please update your flutter with `flutter upgrade`.
 ![htdocs](./screen-shots/flutter-error.png)
