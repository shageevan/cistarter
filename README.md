CodeIgniter App Starter Kit
==================

This repository will help you kickstart your codeigniter projects.

Sparks Installed
----------------
* CodeIgniter REST Client - [https://github.com/philsturgeon/codeigniter-restclient](https://github.com/philsturgeon/codeigniter-restclient)
* CodeIgniter CURL Library - [https://github.com/philsturgeon/codeigniter-curl](https://github.com/philsturgeon/codeigniter-curl)
* CodeIgniter IonAuth Authentication Library - [https://github.com/benedmunds/CodeIgniter-Ion-Auth](https://github.com/benedmunds/CodeIgniter-Ion-Auth)

User Interface Components
-----------------
* Boostrap - [http://getbootstrap.com](http://getbootstrap.com)
* Font Awesome - [http://fortawesome.github.io/Font-Awesome/](http://fortawesome.github.io/Font-Awesome/)

App Views
-------------
Load your views using
```
$this->load->appviews(array('viewfile1','viewfile2','viewfile3'));
```
This will load header and footer of the application automatically. If you want to edit, you can find them in /application/views/common/ folder.

Important
---------
Always change your encryption key found at /app/application/config/config.php before you start developing your application. Visit [http://randomkeygen.com](http://randomkeygen.com) to obtain a random CodeIgniter encryption key.