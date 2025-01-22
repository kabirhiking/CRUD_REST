# Installation and Setup Process

Follow these steps to set up your Django project:

1. **Create a Virtual Environment**:
    ```sh
    python -m venv env_site
    ```

2. **Activate the Virtual Environment**:
    ```sh
    .\env_site\Scripts\activate.ps1
    ```

3. **Install Django**:
    ```sh
    pip install django
    ```

4. **Create a New Django Project**:
    ```sh
    django-admin startproject gfg_shopping
    ```

5. **Navigate to the Project Directory**:
    ```sh
    cd gfg_shopping
    ```

6. **Create a New Django App**:
    ```sh
    python manage.py startapp api
    ```

7. **Make Migrations**:
    ```sh
    python manage.py makemigrations
    ```

8. **Apply Migrations**:
    ```sh
    python manage.py migrate
    ```

9. **Run the Development Server**:
    ```sh
    python manage.py runserver
    ```
https://www.geeksforgeeks.org/django-rest-api-crud-with-drf/
Your Django project should now be up and running.