# Django-Learning

## 🛠️ Django Setup Summary (Using `pipenv`)

## ✅ Project Setup

1. **Created a Django project directory:**
   - `D:\Python\Django_Project`

2. **Initialized virtual environment with Pipenv:**
   ```bash
   pipenv install django
   ```
   - Virtualenv created at:  
     `C:\Users\DELL\.virtualenvs\Django_Project-*`
   - Django installed successfully.

3. **Navigated into subfolder `storefront`:**
   ```bash
   cd .\storefront\
   ```

4. **Initialized another pipenv environment inside `storefront`:**
   ```bash
   pipenv install django
   ```

5. **Activated virtual environment:**
   ```bash
   pipenv shell
   ```

## 🚀 Django Project Start

6. **Started new Django project:**
   ```bash
   django-admin startproject storefront .
   ```

7. **Ran development server on port 9000:**
   ```bash
   python manage.py runserver 9000
   ```
   - Server running at: [http://127.0.0.1:9000](http://127.0.0.1:9000)
   - Warning: favicon.ico not found (normal for fresh project).
   - Unapplied migrations noted.
   ![image](https://github.com/user-attachments/assets/d09d4bd1-9702-495b-8f0e-e6de20948b60)


## 🔧 Next Steps

- Run migrations:
  ```bash
  python manage.py migrate
  ```
