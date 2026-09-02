# Django Online Course App — Final Project

Final project for **Django Application Development with SQL and Databases** (IBM Full Stack Certificate).

## Project

Adds a course **assessment/exam** feature to the existing `onlinecourse` Django app:
- `Question`, `Choice`, and `Submission` models
- Django admin configuration
- Exam form on course detail page
- Submit and exam result views

## Run locally (Cloud IDE recommended)

```bash
pip install -r requirements.txt
python manage.py makemigrations onlinecourse
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver 0.0.0.0:8000
```

## Submission

See [`submission/SUBMISSION_GUIDE.md`](submission/SUBMISSION_GUIDE.md)

---

**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)
