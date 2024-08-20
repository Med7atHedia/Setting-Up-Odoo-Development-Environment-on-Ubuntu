
# Setting Up Odoo Development Environment on Ubuntu

## 1. Update and Upgrade Ubuntu
To update and upgrade your system:
```bash
sudo apt-get update && sudo apt-get upgrade
```

## 2. Install PyCharm
To install PyCharm:
```bash
sudo snap install pycharm-community --classic
```

## 3. Download Odoo Source from GitHub
Choose the desired version and download the ZIP file from the repository.

## 4. Create a New Project in PyCharm
Start a new project in PyCharm.

## 5. Copy and Paste Odoo Source Files into the Project
After creating the project, copy and paste the Odoo source files into your project.

## 6. Install PostgreSQL
To install PostgreSQL:
```bash
sudo apt-get install postgresql
sudo su postgres
createuser --createdb --username postgres --no-createrole --no-superuser --pwprompt odoo16
```

## 7. Install Requirements
To install the necessary requirements for running Odoo:
```bash
pip install -r requirements.txt (specify the correct path to the file)
```

## 8. Create Odoo Configuration File
Copy the `odoo.conf` file from the `debian` folder and modify the details as needed.

![Odoo Configuration](https://github.com/user-attachments/assets/6c54c653-6ab5-4da5-abfc-5075e97442e2)

## 9. Create PyCharm Project Configuration
Set up the project configuration in PyCharm as shown below:

![PyCharm Configuration](https://github.com/user-attachments/assets/6a2ae3a0-2500-424d-813a-0cfd2cd94575)
