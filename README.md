1- update and upgrade ubuntu

    sudo apt-get update && sudo apt-get upgrade

2- install pycharm

    sudo snap install [pycharm-community] --classic

3- download odoo sourse from github

    chose the version and dowload ZIP file 

4- create new project on pycharm

    new project

5- copy and past odoo source files in the project

6- install postgresql

    sudo apt-get install postgresql

    sudo su postgres

    createuser --createdb --username postgres --no-createrole --no-superuser --pwprompt odoo16

7- install requirements

    pip install -r requirements.txt (path)

8- create odoo confg file

    copy odoo.conf file from debian folder and change details

![image](https://github.com/user-attachments/assets/6c54c653-6ab5-4da5-abfc-5075e97442e2)


9- create pycharm confg project

![image](https://github.com/user-attachments/assets/6a2ae3a0-2500-424d-813a-0cfd2cd94575)

