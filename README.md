# Little Lemon Web Application


## Main Steps
1. **Create an environment:**

    **Windows:**
    ```
    python -m venv env
    ```
    **MacOS:**
    ```
    python3 -m venv env
    ```

2. **Environment activate:**

    **Windows:**
    ```
    .\env\Scripts\activate
    ```
    **MacOS:**
    ```
    source env/bin/activate
    ```

3. **Install Django:**

    **Windows:**
    ```
    pip install django
    ```
    **MacOS:**
    ```
    pip3 install django
    ```

    **Verify Django Version:**

    **Windows:**
    ```
    python -m django version
    ```
    **MacOS:**
    ```
    python3 -m django version
    ```

4. **Start Project:**

    ```
    django-admin startproject <name> .
    ```

5. **Create APP:**

    **Windows:**
    ```
    python -m django startapp <name>
    ```
    **MacOS:**
    ```
    python3 -m django startapp <name>
    ```

    **OR**

    **Windows:**
    ```
    python manage.py startapp <name>
    ```
    **MacOS:**
    ```
    python3 manage.py startapp <name>
    ```

6. **Run Server:**

    ```
    cd myproject
    ```

    **Windows:**
    ```
    python manage.py runserver
    ```
    **MacOS:**
    ```
    python3 manage.py runserver
    ```

7. **Deactive Environment:**

    ```
    deactivate
    ```

    ## Project Overview
When you submit your assignment, other learners in the course will review and grade your work. They will evaluate the following:

Does the web application use Django to serve static HTML content?

Has the learner committed the project to a Git repository?

Does the application connect the backend to a MySQL database?

Are the menu and table booking APIs implemented?

Is the application set up with user registration and authentication?

Does the application contain unit tests?

Can the API be tested with the Insomnia REST client?