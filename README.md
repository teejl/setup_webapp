# How to Setup a Web App w/ Python (Django)
Through this tutorial I will be using my Raspberry Pi which runs off of Linux operating system. If you wish to run this tutorial from a different operating system some of the syntax will need to be adjusted for the proper operating system. 

## Install Python3 and the Django package with pip
First we must install Python3 (comes with pip) and the Python package Django.
``` shell
sudo apt-get install python3 # install python3 & pip
sudo python3 -m pip install django # install django
```

## Start a Django Project
The next step is to start a Django project.
```shell
python3 -m django --version # check django version
django-admin # check django admin commands
sudo django-admin startproject {project name} # start a project with specified name
```
## Verify the server works locally
Now we want to make sure we can run and connect to the server.
```shell
cd {project name} # enter project directory
tree # show project tree
sudo python3 manage.py runserver # run the server
```
Then go to the following link in your web browser of choice: [localhost:8000](localhost:8000)

