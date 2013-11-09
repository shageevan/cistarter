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

Wrapper Views
-------------
* header.php
* footer.php

When loading views from your controller, load the wrapper views alongside like:
```
$this->load->view('header');
...Your views...
$this->load->view('footer');
```

Important
---------
Always change your encryption key found at /app/application/config/config.php before you start developing your application. Visit [http://randomkeygen.com](http://randomkeygen.com) to obtain a random CodeIgniter encryption key.