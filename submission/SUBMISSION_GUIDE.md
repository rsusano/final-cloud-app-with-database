# Django Online Course App — Submission Guide

**Repo:** https://github.com/rsusano/final-cloud-app-with-database  
**Passing score:** 10.5 / 15 (70%)

> Run migrations, create admin data, and take screenshots in **IBM Skills Network Cloud IDE**.

---

## Q1 — models.py URL (3 pts)

```
https://github.com/rsusano/final-cloud-app-with-database/blob/master/onlinecourse/models.py
```

---

## Q2 — admin.py URL (3 pts)

```
https://github.com/rsusano/final-cloud-app-with-database/blob/master/onlinecourse/admin.py
```

---

## Q3 — Admin screenshot (1 pt)

Upload **`03-admin-site.png`** showing:
- Authentication and Authorization section
- OnlineCourse section

---

## Q4 — course_detail_bootstrap.html URL (2 pts)

```
https://github.com/rsusano/final-cloud-app-with-database/blob/master/onlinecourse/templates/onlinecourse/course_detail_bootstrap.html
```

---

## Q5 — views.py URL (2 pts)

```
https://github.com/rsusano/final-cloud-app-with-database/blob/master/onlinecourse/views.py
```

---

## Q6 — urls.py URL (2 pts)

```
https://github.com/rsusano/final-cloud-app-with-database/blob/master/onlinecourse/urls.py
```

---

## Q7 — Exam passed screenshot (2 pts)

Upload **`07-final.png`** showing:
- Congratulations message
- Score > 80
- Exam results

---

## Cloud IDE setup commands

```bash
cd /home/project
git clone https://github.com/rsusano/final-cloud-app-with-database.git
cd final-cloud-app-with-database
pip3 install -r requirements.txt
python3 manage.py makemigrations onlinecourse
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver 0.0.0.0:8000
```

**Launch Application** → port **8000**

### Admin setup (http://localhost:8000/admin)

1. Create a **Course** with image, description, lessons
2. Add **2 Questions** (grade 50 each) linked to the course
3. Add **Choices** per question — mark correct answers
4. Create a **test user** (or register on site)
5. Enroll in course → take exam → select correct answers → Submit

**Passing exam:** score must be **> 80** (e.g. 2 questions × 50 pts, all correct = 100)

---

## Submission order

1. Push code to GitHub (done in Cursor)
2. Cloud IDE — clone, migrate, superuser, test data
3. Screenshots: admin + passed exam
4. Coursera → Launch App → paste URLs + upload images
