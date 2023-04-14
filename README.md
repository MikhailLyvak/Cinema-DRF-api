# Dockerizing DRF Cinema

Cinema service made with DFR for management.

## 💼 Installing using GIT
```
git clone https://github.com/MikhailLyvak/Cinema-DRF-api.git
cd cinema-api
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

# 📝 Then do following steps
```python
export DB_HOST=<your db hostname>
export DB_NAME=<your db name>
export DB_USER=<your db user>
export DB_PASSWORD=<your db password>
export DB_SECRET_KEY=<your secret key>
python manage.py migrate
python manage.py runserver
```
