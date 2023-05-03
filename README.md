# Dockerizing DRF Cinema

Cinema service made with DFR for management.

## 💼 Installing using GIT
```
git clone https://github.com/MikhailLyvak/Cinema-DRF-api.git
cd cinema-api
python -m venv venv
venv\Scripts\activate (on Windows)
source venv/bin/activate (on macOS)
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

# 📈 Run with DOCKER
```python
# DOCKER should be already installed
docker-compose build
docker-compose up
```

# 🤟 To get access to work with api do next steps
```python
create user via /api/user/register/
get access token via /api/user/token/
```

# 📜 Some project Features
- JWT authenticated
- Admin panel /admin/
- Documentation is located at /api/doc/swagger/
- Managing orders and tickets
- Creating movies with genres, actors
- Creating cinema halls
- Adding movie sessions
- Filtering movies and movie sessions

![image](https://user-images.githubusercontent.com/118639650/235923639-3c57e987-b40e-4330-a9a8-3cb5262ecf68.png)
![image](https://user-images.githubusercontent.com/118639650/235923727-eb92c7b4-61b5-4d92-b9c9-8a778339d704.png)

