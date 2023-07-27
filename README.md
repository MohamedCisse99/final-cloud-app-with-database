# Online Course Application on Django 

This is a simple Django online course application with a SQLite database that allows the addition of courses, questions, and the ability to conduct student evaluations.

Developed as a project for the [IBM Full Stack Software Developer Professional Certificate](https://www.credly.com/org/ibm/badge/full-stack-software-developer-professional-certificate) program.

## ER diagram
![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

## Install and Run

At the terminal run the command

```text
python3 -m pip install -U -r requirements.txt

python3 manage.py makemigrations
python3 manage.py migrate

python3 manage.py runserver
```

Open [localhost:8000/onlinecourse](http://localhost:8000/onlinecourse/) to view it in your browser.
