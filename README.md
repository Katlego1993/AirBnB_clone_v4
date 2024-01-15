AirBnB Clone V.4 - Web dynamic
Synopsis
This is the 4th version of our AirBnB clone project. We will be using python3, RESTful API, MySQL, Flask, and jQuery AJAX

step2

Table of Contents
Environment
Installation
File Descriptions
Usage
Examples of use
Bugs
Authors
License
Environment
This project is interpreted/tested on Ubuntu 14.04 LTS using python3 (version 3.4.3), jQuery (version 3.x), MySQL (version 5.7), Flask, and Chrome (version 57.0)

Installation
** UNDER CONSTRUCTION **

File Structure
api directory contains Flask web applications for a RESTful API
models directory contains all classes used for this project:
tests directory contains all unit test cases for this project.
web_dynamic directory contains all files necessary to start a dynamic Flask web application.
web_flask directory contains all files necessary to start a Flask web application.
web_static directory contains all html, css and images used for the static website.
0-setup_web_static.sh - bash script that sets up web servers for the deployment of web_static
1-pack_web_static.py - Fabric script that generates a .tgz archive from the contents of web_static, using the function do_pack
2-do_deploy_web_static.py - Fabric script (based on 1-pack_web_static.py) that distributes an archive to web servers, using the function do_deploy
3-deploy_web_static.py - Fabric script (based on 2-do_deploy_web_static.py) that creates and distributes an archive to web servers, using the function deploy
AUTHORS - list of Authors who have worked on this project.
console.py - the console is a command line used to interact with the storage engines.
setup_mysql_dev.sql - MySQL script to set-up the hbnb_dev_db database.
setup_mysql_test.sql - MySQL script to set-up the hbnb_test_db database.
