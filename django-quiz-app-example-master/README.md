### Instructions to setup
```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py syncdb
```
on first setup, it will ask to create superadmin.

### To run server
```bash
python manage.py runserver localhost:8000 
```
Login at: http://localhost:8000/admin with superadmin credentials and create quizzes
Access quizzes at: http://localhost:8000/quizes/