# Django CRM


## Description
Basic Django CRM app. First Django project and will be the starting point for my next, more complex CRM Project. Uses sqlite3 as the database, which is the default for Django projects. Basic Bootstrap is used for styling.


## Installation
### 1. Clone the Repository
```sh
git clone https://github.com/KadonDEngle/django-crm.git

cd django-crm
```

### 2. Install Dependencies
The only dependency is django, but included for best practice.
```sh
pip install -r requirements.txt
```

### 3. Database Setup
Migrations for the models have already been created and the "migrations" directory is included as per Django's [Migration Documentation](https://docs.djangoproject.com/en/3.2/topics/migrations/). All you have to do is run:
```sh
python manage.py migrate
```

### 4. Create a Super User
Access the admin panel at `localhost:8000/admin`. You can create a super user account using:
```sh
python manage.py createsuperuser
```

### 5. Run the Development Server
```sh
python manage.py runserver
```


## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE.txt) file for details.