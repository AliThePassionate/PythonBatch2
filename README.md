#      WellCome to Python Framework ** Django **


### Table of Contents
## [Step-01 Let Start Django](Step-01)
#### [1.1 Create a folder](1.1)
#### [1.2 Django Requires Python](1.2)
#### [1.3 Pip python package manager like npm](1.3)
## [Step-02  Create Virtual Environment](#Step-02)
## [Step-01 Let Start Django](Step-03)
## [Step-01 Let Start Django](Step-04)
## [Step-01 Let Start Django](Step-05)
## [Step-01 Let Start Django](Step-06)
## [Step-01 Let Start Django](Step-07)
## [Step-01 Let Start Django](Step-08)
## [Step-01 Let Start Django](Step-09)
## [Step-01 Let Start Django](Step-10)
## [Step-01 Let Start Django](Step-11)
## [Step-01 Let Start Django](Step-12)
## [Step-01 Let Start Django](Step-13)





##  Framework

###  Defination
A framework is a pre-built structure or system that provides a foundation and basic functionalities for building something more complex.

###  Python Framework

Python frameworks are pre-built collections of code, tools, and libraries designed specifically to make 

Python development faster, easier, and more structured. They provide a foundation for building applications by offering:

**Common functionalities**: Handle repetitive tasks like URL routing, database interactions, and templating.
**Reusable components**: Provide pre-written code for common web development tasks.
**Structure and conventions**: Guide you to organize code in a consistent way, making it easier to maintain and collaborate on.

Think of them as blueprints or toolkits that help you focus on your application's unique logic rather than reinventing the wheel.

#### Popular Python frameworks for web development include:

- **Django**:
    Full-featured framework for complex web applications, known for its "batteries included" approach.

- **Flask**: 
    Microframework for smaller, more flexible projects, offering modularity and customization.

- **Pyramid**: 
    Versatile framework adaptable for various project sizes and needs.

#### Benefits of using Python frameworks:

- *Faster development*: Accelerate the development process by providing ready-made solutions.
*Reduced code*: Write less code, as frameworks handle common tasks.
*Improved code organization*: Enforce structure and conventions, leading to cleaner and more maintainable code.
*Access to best practices*: Benefit from the experience of the framework's developers.
*Enhanced security*: Frameworks often have built-in security features to protect your applications.


#### Note: We use only **Django** for web development called Django-Development


## Django
Django is a Python framework that makes it easier to create web sites using Python.Django takes care of the difficult stuff so that
you can concentrate on building your web applications.
### Key Features of Django:
- Django is a back-end server side web framework.
- Django is free, open source and written in Python.
- Django makes it easier to build web pages using Python.




 

## Step-01 Let Start Django 

### 1.1 Create a folder (with any name)

we create folder Named Django-Developement

#### Open cmd

Open cmd prompt in this folder and type

```
code .
```
#### Simply open terminal
 

### 1.2 Django Requires Python
To check if your system has Python installed, run this command in the command prompt:

```
python --version
```
### if you learn about python please go to this repostry step by step
**[Pythonforpassionate](https://github.com/HashimThePassionate/Python-For-Absolute-Beginners)**


### 1.3 Pip python package manager like npm

To install Django, you must use a package manager like pip, which is included in Python when simply install python.
To check if your system has pip installed, run this command in the command prompt:

```
pip --version
```


### 1.4 By default python version 3.11 installed in this virtual environment

    - Because python 3.11 version installed globally on my machine
    - to install different python version
    - go to python.org and install different version globally
    - we are going to install python 3.12 separately
    - so have a look to our environment variables when two different python versions is installed

```terminal
C:\Users\aaaa\AppData\Local\Programs\Python\Python311\;
```

### Now we install another version python 3.12 
   
   [python.org](https://www.python.org/downloads/release/python-3121/) 

### 1.5 Check python version

**first run command in cmd**
```terminal
where python
```
**Expected Output**
```
C:\Users\DELL\AppData\Local\Programs\Python\Python3.12\python.exe
C:\Users\DELL\AppData\Local\Programs\Python\Python3.11\python.exe
```




## Step-02  Create Virtual Environment

It is suggested to have a dedicated virtual environment for each Django project, and one way to manage a virtual environment is ``virtualenv``package, which is included in Python

### 2.1 check virtualenv package is installed or not

```terminal
pip list
```
### See pip list
```
Package      Version
------------ -------
asgiref      3.7.2
distlib      0.3.3
filelock     3.13.1
pip          23.3.2
platformdirs 4.1.0
setuptools   65.5.0
sqlparse     0.4.4
tzdata       2023.4
```

### 2.2 if virtualenv is not installed that install this package
```
pip install virtualenv

```

### 2.3 check version of virtualenv
```
virtualenv --version
```

### 2.4 Now create a virtual environment

- Run this command in  Vs Code terminal

```
python -m virtualenv virtual
```
### Purpose of Virtual Environments:

Isolation: They prevent conflicts between different project dependencies and system-wide Python installations. This ensures that each project has its own set of packages and versions, avoiding compatibility issues.
Reproducibility: They enable you to recreate the exact environment needed to run a project, even on different machines or in the future. This is crucial for ensuring consistent development and deployment.
Testing: They allow you to safely test different Python versions or packages without affecting your main Python installation, making experimentation and testing easier.
Cleanliness: They keep your project's dependencies organized and separate from other projects, promoting a more organized and maintainable workspace.


### Now see a folder virtual is created and inside this virtual you will folders structure like this

virtual
    |____ lib
    |        |___site-packages   
    |            |___ .......
    |____ Scripts
    |           |____ ....... 
    |____ pyvenv.cfg  

### 2.4 Explain Virtualenv structure
 
 ### 2.4.1 Virtual 
Virchowalino can give any letters,like:  name, place, things etc.
- but first use letter that were given to this repostry eg; virtual 

 ### 2.4.2 lib

- Contains the core Python library, including essential modules and packages.
- It's a replica of the standard Python library, but isolated for this specific environment.
- Allows the virtual environment to function independently of your system-wide Python installation.

### 2.4.3 Site-packages

- Houses third-party packages installed using pip within this virtual environment.
- Separates these packages from any other virtual environments or your system-wide Python installation.
- Ensures each project has its own set of dependencies without conflicts.

### 2.4.4 Scripts

1.Contains executable scripts for Python and its tools, such as:
- The Python interpreter itself (python or python3)
- The package installer (pip)
- Other utilities like virtual environment management tools

2.Activates the virtual environment when you run the appropriate script (e.g., Scripts\activate on Windows).

### 2.4.5 pyvenv.cfg 

1.A configuration file that stores metadata about the virtual environment, including:
- The path to the Python interpreter used to create it
- Any custom settings or configuration options

2.Used by virtual environment tools to manage and interact with the environment.


### 2.5 Then you have to activate the environment, by typing this command:

    - On Window
```
virtual\Scripts\activate
```
### Explain
- **virtual**: This refers to the name of the virtual environment you want to activate. Replace it with the actual name of your environment (e.g., my_env).
- **\Scripts**: This part indicates the subdirectory within the virtual environment that contains the activation script.
- **\activate**: This is the name of the activation script itself. 

**Purpose**:
   This command activates a virtual environment, making it the active Python environment for your current terminal session. This means any Python packages you install or scripts you run will be confined to that environment, not affecting your system-wide Python installation.






## Step-03 Error

### 3.1 if you activate virtual environment and got error like this

```
    virtual\Scripts\activate : File C:\Users\aaa#\Desktop\django\virtual\Scripts\activate.ps1 cannot be loaded because running scripts is disabled on this system. For more 
information, see about_Execution_Policies at https:/go.microsoft.com/fwlink/?LinkID=135170.
At line:1 char:1
+ virtual\Scripts\activate
+ ~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

```
### Explain error
- The error message indicates that PowerShell script execution is disabled on your system, and it's preventing the activation script from running. 
- To resolve this issue, you can change the execution policy to allow script execution

 ### 3.2 to solve this error follow these steps**

    - First click on search icon
    - type Windows Powershell
    - right click on Windows Powershell icon and run as a administrator
    - type this command

```windowPowerShell
Set-ExecutionPolicy RemoteSigned
```
    - and finaly after running this command type "y"
    - now softly activate your virtual environment

- Once the environment is activated, you will see this result in the terminal:
```
(virtual) C:\Users\aaaa\Desktop\Batches\Django_Development
```

### 3.2 deactivate virtual environment simple type
```django
deactivate
```




## Step-04 Create Virtualenv with any python version(3.12 or 3.11)

### 4.1copy the path of python 3.12 version and create a new virtualenv

```
python -m virtualenv -p C:\Users\DELL\AppData\Local\Programs\Python\Python3.12\python.exe Virtual3.12
```
## OR

### 4.2copy the path of python 3.12 version and create a new virtualenv

```
python -m virtualenv -p C:\Users\DELL\AppData\Local\Programs\Python\Python3.11\python.exe Virtual3.11
```


#### Now again check python version 3.12
```
python --version
```

#### Congratulations You have python 3.12 on new virtual environment




## Step-5 Install Django

Now, that we have created a virtual environment, we are ready to install Django. Note: Remember to install Django while you are in the virtual environment ! Django is installed using pip, with this command:
```
(virtual3.12) C:\Users\aaaa\Desktop\Batches\Django_Development>pip install django
```
### 5.1 to check django install or not run 
```
(virtual3.12) C:\Users\aaaa\Desktop\Batches\Django_Development>django-admin --version
```
### See Django version
```
    5.0.1
```

### 5.2 Deactivate virtualenv

```python
deactivate
```

### Now we deactivate virtual environment check django again

```
django-admin --version
```

    - Note we got error like this

```
'django-admin' is not recognized as an internal or external command,
operable program or batch file.
```

### Why we got this error please have a research thank you!!!!
## Regards Muhammad Hashim




#  Class 02 (Run Server)

## Step-06  Create another Virtual environment

####  create Virtualenv, Follow these steps from class01 /  step-02 / 2.3, 2.4, 2.5 & step-05/ only install Django in virtualenv 

### Now create a virtual environment

- Run this command in  Vs Code terminal

```
python -m virtualenv virtual
```
### Then you have to activate the environment, by typing this command:

    - On Window
```
virtual\Scripts\activate
```

## Step-07cd command

### 7.1 While virtual environment is inactive:

##### 1. Virtual Environment Name:

Please specify the exact name of the virtual environment (e.g., "venv", "my_env", etc.).
##### 2. Starting Location:

Indicate the current directory where you'll be executing the cd commands. Are you already within the virtual environment's root directory, or do you need to navigate there first?
##### 3. Desired Destination:

- Clearly state the specific directory or file within the project structure that you want to reach using the cd commands.
- Once I have this information, I'll provide tailored cd commands to seamlessly guide you to your intended destination within the virtual environment.

**Here are examples assuming different scenarios**:

*Scenario 1*: Navigate to the "app" directory from the virtual environment's root:

If already within the virtual environment:
```Bash
cd lib/site-packages/app
```
 
 If starting from outside the virtual environment:
- Activate the virtual environment (e.g., source venv/bin/activate)
- Then use the command above.

*Scenario 2*: Access the "models.py" file within the "projectname" app:

```Bash
cd lib/site-packages/projectname/projectname/models.py
```


### 7.2 After creating virtualenv, use cd command to enter your virtualenv

- First you run command to enter virtual
```bash
cd virtual
```
Expexted output
```
(virtual) PS E:\django\virtual>

```
- run command to enter lib
```bash
cd lib
```
Expexted output
```
(virtual) PS E:\django\virtual\lib>

```
- run command to enter lib
```bash
cd site-packages
```
Expexted output
```
(virtual) PS E:\django\virtual\lib\site-packages>

```
#### Then you creat a start django project


## Step-08 Create a Django Project
### 8.1 Creating Django startproject

    - Once Django is installed, you can create a Django project using the following command:

```django
django-admin startproject projectname

```

### 2.2 After Creating Project projectname we see these levels

```
virtual
    |____ lib
    |        |___site-packages   
    |            |___ projectname
    |                |___ projectname
    |                     |___ __init__.py   
    |                     |___ asgi.py
    |                     |___ settings.py
    |                     |___ urls.py
    |                     |___ wsgi.py
    |____ Scripts
    |           |___ ....... 
    |____ pyvenv.cfg  
```

### 8.3 Explain projectname folder
folder structure
```
projectname
    |___ projectname
        |___ __init__.py   
        |___ asgi.py
        |___ settings.py
        |___ urls.py
        |___ wsgi.py
    |___ manage.py

```

### 8.3.1 Project Directory(projectname/any name)

**projectname/**: 
This is the root directory of your Django project, containing all essential files and subdirectories.

### 8.3.2 Main Project App Directory:

**projectname/projectname/**: 
This subdirectory houses the core Python files for your main Django app, which shares the same name as your project.

**1. init.py**:

- Marks the directory as a Python package, enabling imports from other parts of the project.
- Often empty, but can contain initialization code.

**2. asgi.py**:

- Configures the application for Asynchronous Server Gateway Interface (ASGI), a protocol for handling asynchronous web requests.
- Essential for modern Python web servers like Uvicorn and Daphne.

**3. settings.py**:

The central configuration file for the Django project.

Contains crucial settings like:
- Database connections
- Installed apps
- Templates and static files directories
- Security and middleware settings
- Email configurations

**4. urls.py**:

- Defines URL patterns that map incoming URLs to specific views (functions that handle requests and return responses).
- Controls how users navigate through the application's pages.

**5. wsgi.py**:

- Interfaces Django with a web server gateway interface (WSGI)-compliant server like Apache or Gunicorn.
- Translates HTTP requests into Django calls and returns responses.


### 8.3.3 Project Management Script:

** manage.py**:

A command-line utility for interacting with the Django project.

**Used to**:
- Start the development server
- Run migrations to update the database schema
- Create and manage apps
- Collect static files
- Perform other administrative tasks




## Step-9 Detail explain BuildIn Code of Setting.py

### 9.1 BuildIn Code 

```python

from pathlib import Path

# Build paths inside the project like this: BASE_DIR / 'subdir'.
BASE_DIR = Path(__file__).resolve().parent.parent


# Quick-start development settings - unsuitable for production
# See https://docs.djangoproject.com/en/5.0/howto/deployment/checklist/

# SECURITY WARNING: keep the secret key used in production secret!
SECRET_KEY = 'django-insecure-qq2o2zx7=)u+f!af0p=fn=my*pr&_oyri2j89$)r5yyqvfacq0'

# SECURITY WARNING: don't run with debug turned on in production!
DEBUG = True

ALLOWED_HOSTS = []


```

### 9.1.1 Importing Pathlib:

```Python
from pathlib import Path
```
- This line imports the Path class from the pathlib module, providing a more object-oriented and convenient way to work with file paths in Python.

### 9.1.2 Setting BASE_DIR:

```Python
BASE_DIR = Path(__file__).resolve().parent.parent
```

This line sets a variable named BASE_DIR to represent the absolute path to the root directory of your Django project. It does this by:
- *Path(__file__)*: Creates a Path object representing the current file (settings.py itself).
- *resolve()*: Converts the path to its absolute path, removing any relative parts.
- *parent.parent*: Navigates up two levels in the directory structure to reach the project root.

*Purpose* :

- Creating consistent paths: Django uses BASE_DIR to construct paths to various project resources (templates, static files, apps) in a platform-independent way, ensuring consistent behavior across different operating systems.
- Reference point for configuration: Many other settings within settings.py often reference BASE_DIR to locate files and directories relative to the project root.

### 9.1.3 Quick-Start Development Settings:


- Quick-start development settings - unsuitable for production
 (Djangoproject.com)[See https://docs.djangoproject.com/en/5.0/howto/deployment/checklist/]

- This comment highlights that the default settings are for development purposes only and not recommended for production environments.
- It directs you to Django's documentation for deployment checklists to ensure proper security and configuration in production.

### 9.1.4 SECRET_KEY:

```Python
SECRET_KEY = 'django-insecure-qq2o2zx7=)u+f!af0p=fn=my*pr&_oyri2j89$)r5yyqvfacq0'
```
This is a critical security setting used for:
- Signing cookies
- Generating cryptographic tokens for sessions and password resets
- Protecting sensitive data

*Purpose*:
*Preventing attacks*: It's essential to keep this key secret and change it in production to prevent attacks like session hijacking and cross-site request forgery.


### 9.2 Install Application
### BuiltIn Code
```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
]
```
### Explain
### 9.2.1 Default Built-in Apps:

- django.contrib.admin:
Provides the Django admin interface, an auto-generated interface for managing your project's models and data.
- django.contrib.auth:
Handles user authentication, including registration, login, logout, permissions, and groups.
- django.contrib.contenttypes:
Keeps track of different content types in your project, enabling generic relationships between models.
- django.contrib.sessions:
Manages user sessions, storing and retrieving session data across requests.
- django.contrib.messages:
Frameworks for storing and displaying user messages (e.g., success messages, error messages).
- django.contrib.staticfiles:
Manages static files (CSS, JavaScript, images) used for the frontend of your website.

### 9.2.2 Purpose:

- This setting specifies the list of applications that are activated and available within your Django project.
- Each application provides specific functionalities and features for your website.
- Django loads and integrates these apps to build the complete functionality of your project.

### 9.2.3 Key Points:

- The order of apps in INSTALLED_APPS can sometimes matter for dependencies between apps.
- You can add your own custom apps to this list to extend your project's functionality.
- Installed apps contribute models, views, templates, and other components to your project.
- Django loads these apps in the order they are listed, so dependencies should be placed before apps that depend on them.


### 9.3 Middleware

### BuildIn Code
```python
MIDDLEWARE = [
    'django.middleware.security.SecurityMiddleware',
    'django.contrib.sessions.middleware.SessionMiddleware',
    'django.middleware.common.CommonMiddleware',
    'django.middleware.csrf.CsrfViewMiddleware',
    'django.contrib.auth.middleware.AuthenticationMiddleware',
    'django.contrib.messages.middleware.MessageMiddleware',
    'django.middleware.clickjacking.XFrameOptionsMiddleware',
]
```
### Explain

### 9.3.1 django.middleware.security.SecurityMiddleware:


*Purpose*:
 Enhances security by:
- Setting HTTP headers for security-related features (e.g., HSTS, XSS protection).
- Protecting against common vulnerabilities like clickjacking.
- Handling redirects for HTTPS enforcement.
### 9.3.2 django.contrib.sessions.middleware.SessionMiddleware:

*Purpose*: 
Manages user sessions, enabling features that require state across multiple requests:
- Stores session data in cookies or the database.
- Associates a session with each incoming request.
- Facilitates user login, shopping cart persistence, etc.

### 9.3.3 django.middleware.common.CommonMiddleware:

*Purpose*: 
Provides common functionality for request-response handling:
- Handles redirects for URLs ending with slashes.
- Sets the Content-Length header for responses.
- Handles ETags for static files.

### 9.3.4 django.middleware.csrf.CsrfViewMiddleware:

*Purpose*: 
Protects against Cross-Site Request Forgery (CSRF) attacks:
- Adds a CSRF token to forms for verification.
- Checks for valid tokens in POST requests.

### 9.3.5 django.contrib.auth.middleware.AuthenticationMiddleware:

*Purpose*: 
Manages user authentication:
- Associates authenticated users with requests.
- Sets the user attribute on request objects.

### 9.3.6 django.contrib.messages.middleware.MessageMiddleware:

*Purpose*: 
Handles temporary messages for users:
- Stores messages in sessions for display across requests.
- Used for flash messages, success/error alerts, etc.

### 9.3.7 django.middleware.clickjacking.XFrameOptionsMiddleware:

*Purpose*: 
Mitigates clickjacking attacks:
- Sets the X-Frame-Options header to prevent embedding the site in iframes.

### Order of Middleware:

- The order of middleware in the MIDDLEWARE list is crucial, as they are processed in a chain-like manner.
- Security-related middleware like SecurityMiddleware and ClickjackingMiddleware often come first.
- Session and authentication middleware typically follow.
- Common middleware and CSRF middleware are placed accordingly based on requirements.

### Custom Middleware:

You can create custom middleware for specific needs by defining Python classes and adding them to the MIDDLEWARE list.


### 9.4 ROOT_URLCONF

### BuildIn Code
```python
ROOT_URLCONF = 'projectname.urls'
```

### 9.4.1 Explain

- *ROOT_URLCONF*: A Django setting that stores a Python dot notation path to the root URL configuration module.
- *'projectname.urls'*: The value in this case, indicating that the root URL configuration module is named urls.py and resides within the projectname directory.

### Process/Working

- *Incoming Request*: When a user requests a URL in your Django application, Django first consults the ROOT_URLCONF setting to locate the root URL configuration module.
- Loading the Module: Django imports the specified module (projectname.urls in this case).
- Searching for Patterns: Within that module, Django searches for a variable named urlpatterns. This variable holds a list of URL patterns, each defining a mapping between a URL path and a corresponding view function.
- Matching Patterns: Django iterates through the urlpatterns list, comparing the requested URL with each pattern.
- View Function Execution: If a match is found, Django executes the associated view function, passing the request object as an argument.
- View Generates Response: The view function performs necessary actions (e.g., retrieving data from the database) and generates an appropriate response (e.g., an HTML page).
- Response Returned: Django sends the generated response back to the user's browser.

*Purpose*:

- It specifies the root URL configuration module for your Django project.
- This module acts as the starting point for Django's URL dispatching system, mapping URLs to specific views (functions that handle requests and generate responses).

### Key Points:

- The urls.py module within each Django app can define its own URL patterns, which can then be included in the root urls.py for a hierarchical structure.
- The include() function in Django's URL dispatcher allows for modularization and reusability of URL patterns.
- Changing the ROOT_URLCONF setting effectively switches the entire URL configuration for your project.


### 9.5 Templates

### BuiltIn Code
```python
TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': [],
        'APP_DIRS': True,
        'OPTIONS': {
            'context_processors': [
                'django.template.context_processors.debug',
                'django.template.context_processors.request',
                'django.contrib.auth.context_processors.auth',
                'django.contrib.messages.context_processors.messages',
            ],
        },
    },
]
```
### 9.5.1 Explain

Here's a detailed explanation of the TEMPLATES setting in Django's settings.py file:

### TEMPLATES = [...]: 
A list of dictionaries, each representing a different template configuration. The default configuration is typically sufficient for most projects.
### Within the default configuration:

**'BACKEND'**: 'django.template.backends.django.DjangoTemplates':

Specifies the backend engine responsible for loading and rendering templates. Here, it uses Django's built-in templating system.

### 'DIRS': []:

An empty list in this case, indicating that Django will look for templates in the default locations (application templates directories and project-level templates directory). You can add custom directories here if needed.

### 'APP_DIRS': True:

Instructs Django to search for templates within each installed application's templates directory. This is often convenient for organizing templates by feature.

### 'OPTIONS': {...}:

Provides additional configuration options, including:
*'context_processors'*: A list of processors that add context variables to every template. These variables are accessible within the templates to display dynamic content. 
Common processors include:
*'django.template.context_processors.debug'*: Adds debugging information in development mode.
*'django.template.context_processors.request'*: Provides access to the current request object.
*'django.contrib.auth.context_processors.auth'*: Adds authentication-related variables (e.g., user.is_authenticated).
*'django.contrib.messages.context_processors.messages'*: Adds message variables for user feedback.

### 9.5.2 Purpose:

Configures how Django locates, loads, and renders templates, which are the HTML files that define the structure and content of your web pages.
Key takeaways:

The TEMPLATES setting is essential for managing templates in Django projects.
It controls where Django looks for templates, how it loads them, and what context variables are available within them.
Understanding this configuration allows you to customize template loading and rendering to suit your specific project needs.



### 9.6 WSGI_APPLICATION 

```python
WSGI_APPLICATION = 'projectname.wsgi.application'
```
### 9.6.1Explain

Here's a detailed explanation of the WSGI_APPLICATION = 'projectname.wsgi.application' setting in Django's settings.py file:




### WSGI_APPLICATION:
 The name of the setting within the settings.py file.
*= 'projectname.wsgi.application'*: The value assigned to the setting, which is a Python path pointing to a callable:

*projectname*: Replace this with the actual name of your Django project.
*wsgi.py*: The file containing the WSGI application callable, usually located in your project's root directory.
*application*: The name of the callable object within the wsgi.py file.

### Processing/Working

- **Server Configuration**:
When you deploy a Django application using a WSGI server (e.g., Apache, Gunicorn), you configure the server to load the WSGI application specified in WSGI_APPLICATION.

- **Loading the Callable**:
The server imports the wsgi.py file from your project and retrieves the application object.

- **Handling Requests**:
Whenever a request arrives, the server calls the application object, passing it the request details.

- **Django Interaction**:
The application object initiates Django's request-response cycle, which involves:
- Routing the request to the appropriate view function.
- Processing the request logic in the view.
- Generating a response.

### Response Return:
The application object returns the generated response to the server, which then sends it back to the client's browser.

### 9.6.2 Purpose:

- Specifies the entry point for a Django application when using a WSGI server.
- WSGI (Web Server Gateway Interface) is a standard for connecting Python web applications to web servers.
- The setting tells the server where to find the callable object that handles incoming requests and generates responses.


### 9.6.2 Key Points:

- *Default Value*: If not specified, Django uses 'django.core.wsgi.get_wsgi_application', which dynamically loads the application from your project's settings.py file.
- *Production Importance*: While optional during development, this setting is crucial for proper deployment on WSGI servers.
- *WSGI File Contents*: The wsgi.py file typically contains a few lines of code that load Django's settings and create the WSGI application object.



### 9.7 Database

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.sqlite3',
        'NAME': BASE_DIR / 'db.sqlite3',
    }
}
```


### 9.7.1 Purpose:

Configures how Django interacts with the database used to store and manage your project's data.

### Explanation:

- *DATABASES*: A dictionary containing database configuration settings for different database connections.
- *'default'*: Key for the default database connection used by Django.
- *'ENGINE'*: Specifies the database backend to use (e.g., 'django.db.backends.sqlite3' for SQLite, 'django.db.backends.postgresql' for  PostgreSQL, etc.).
- *'NAME'*: Name or path to the database file.
- *BASE_DIR / 'db.sqlite3'*: Uses a relative path (based on the project's base directory) to create a SQLite database file named 'db.sqlite3' in the project's root directory.

### 9.7.2 Key Points:

- **Default SQLite**: Django uses SQLite as the default database for simplicity and ease of setup in development environments.
- **Production Databases**: For production environments, you'll typically use more robust database systems like PostgreSQL, MySQL, or Oracle, requiring additional configuration options within the 'default' dictionary.
- **Multiple Databases**: Django supports multiple database connections, which you can configure by adding more keys to the DATABASES dictionary.



### 9.8  UTH_PASSWORD_VALIDATORS 
      
 ### BuiltIn Code
 ```python 
      UTH_PASSWORD_VALIDATORS = [
    {
        'NAME': 'django.contrib.auth.password_validation.UserAttributeSimilarityValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.MinimumLengthValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.CommonPasswordValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.NumericPasswordValidator',
    },
]
```

### 9.8.1 Explain

### Structure: 
It's a list of dictionaries, each specifying a password validation function to be applied.

Django includes four built-in validators:

### 1.UserAttributeSimilarityValidator:

Discourages passwords that are too similar to the user's personal information (e.g., username, email, first/last name).
Prevents weak passwords that could be easily guessed based on known details.

### 2.MinimumLengthValidator:

Enforces a minimum password length (default: 8 characters).
Longer passwords are generally more secure as they're harder to crack.

### 3.CommonPasswordValidator:

Checks against a list of common passwords (e.g., "password123", "qwerty").
Prevents users from choosing easily guessed passwords.

### 4.NumericPasswordValidator:

Disallows passwords consisting only of numbers.
Encourages the use of more complex passwords with a mix of characters.

### 9.8.2 Customization:

You can disable specific validators by removing them from the list.
You can create custom validators for additional password requirements.
You can adjust the minimum password length by setting the min_length option within the MinimumLengthValidator.

### 9.8.3 Purpose:

Enforces password strength and security rules to protect user accounts.
Ensures that users create strong, unique passwords that are difficult to guess or crack.

### 9.8.4 Importance:

Password validation is crucial for web application security.
Using these built-in validators helps protect user accounts from unauthorized access and potential data breaches.


### 9.9 Internationalization
```python
LANGUAGE_CODE = 'en-us'

TIME_ZONE = 'UTC'

USE_I18N = True

USE_TZ = True
```

### 9.9.1 Explain
### 1. LANGUAGE_CODE = 'en-us'


**Effect**:
- Used for language-specific features like translation and formatting.
- Determines the language used in templates, forms, and generated content.
- Can be overridden for individual users or sessions.

**Purpose**: 
Specifies the default language for the Django application.


### 2. TIME_ZONE = 'UTC'


**Effect**:
Ensures consistent handling of time-related data across different time zones.
Used for storing and displaying dates and times.
Can be adjusted to match the local time zone of your users.

**Purpose**:
 Sets the default time zone for the application.

### 3. USE_I18N = True


**Effect**:
- Allows for translation of text content into multiple languages.
 -Activates language-specific formatting for dates, times, numbers, and currencies.

**Purpose**: 
Enables internationalization features in Django.

### 4. USE_TZ = True


**Effect**:
- Stores dates and times in the database in UTC.
- Handles time zone conversions appropriately when displaying data to users.
- Ensures correct time-related calculations regardless of the user's location.

**Purpose**: 
Enables time zone awareness in Django.


### 9.10 Static files (CSS, JavaScript, Images)
```python
STATIC_URL = 'static/'

```
### 9.10.1 Explain

Here's a detailed explanation of the STATIC_URL = 'static/' setting in Django's settings.py file:

### 1.Setting the URL:

The value 'static/' indicates that static files will be accessible under the URL path /static/ in your application.
Example: To access a CSS file named style.css, you'd use the URL http://yourdomain.com/static/style.css.

### 2.Loading Static Files in Templates:

Use the {% static %} template tag to generate correct URLs for static files within your templates:
```html

<link rel="stylesheet" href="{% static 'css/style.css' %}">
```

### 3.Static Files Directory:

- **Django searches for static files in either**:

- The static/ directories within each app
- The STATICFILES_DIRS setting in settings.py (for project-wide static files)

- **Serving in Development**:

During development, Django's development server serves static files automatically for convenience.

- **Production Deployment**:

In production, you'll typically configure your web server (e.g., Apache, Nginx) to serve static files directly, bypassing Django for performance reasons.

### 9.10.2 Purpose:

- It defines the base URL that Django will use to serve static files (CSS, JavaScript, images, etc.) in your web application.
- It's a crucial setting for managing static files effectively and ensuring they are accessible from your web pages.

### 9.11.3 Key Points:

- Change STATIC_URL if you prefer a different URL pattern for static files.
- Use the collectstatic command to collect static files from all apps into a single directory for deployment.
- Set up your web server to serve static files directly in production for optimal performance.


### 9.12 Default primary key field type
```python
DEFAULT_AUTO_FIELD = 'django.db.models.BigAutoField'
```
### 9.12.1 Explain
Here's a detailed explanation of the DEFAULT_AUTO_FIELD = 'django.db.models.BigAutoField' setting in Django's settings.py file:

DEFAULT_AUTO_FIELD: Setting name that governs automatic primary key creation.
=: Assignment operator to set the value.
'django.db.models.BigAutoField': Value assigned, indicating Django should use BigAutoField for default primary keys.

### BigAutoField:

64-bit integer field: Accommodates a massive range of values (up to 9 quintillion), suitable for very large datasets.
Introduced in Django 3.2: Became the default primary key field for new projects to address potential limitations of the older 32-bit AutoField.

### 9.12.2 Purpose:

Controls the default field type used for primary keys when you don't explicitly define one in your model classes.
Ensures compatibility with newer Django versions and scalability for large datasets.


### 9.12.3 Key Points:

- **Compatibility**: Using BigAutoField ensures compatibility with newer Django versions and future database migrations.
- **Scalability**: Prepares your project for potential growth in data volume.
- **Explicit Definition**: While DEFAULT_AUTO_FIELD sets the default, you can still explicitly define primary key fields in individual models if needed.

### Customization: 
You can change the default to other field types (e.g., AutoField, UUIDField) if your project has specific requirements.




## Step-010 How to Create and Start Application

### 10.1 Steps to Create an Application:

- Open your terminal.
- Use the cd command to change the directory to your Django project's root folder.
#### Run the Creation Command:

Execute the following command to create a new application named "app":
```bash
django-admin startapp admission
```
### 10.1.1 Go to setting.py file and INSTALLED_APPS:

### Purpose: 
Lists  installed application in your project, including built-in Django app and your custom app.

```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'app',
    '
]

```


### 10.2 App folder Structure

```
virtual
    |____ lib
    |        |___site-packages  
    |            |___ app
    |            |    ├── migrations/
    |            |    |  └── __init__.py
    |            |    |  ├── __init__.py
    |                 |  ├── admin.py
    |            |    |  ├── apps.py
    |            |    |  ├── models.py
    |            |    |  ├── tests.py
    |            |    |  └── views.py 
    |            |    |
    |            |    ├── __init__.py
    |            |    ├── admin.py
    |            |    ├── apps.py
    |            |    ├── models.py
    |            |    ├── tests.py
    |            |    └── views.py 
    |            |   
    |            |___ projectname
    |                |___ projectname
    |                     |___ __init__.py   
    |                     |___ asgi.py
    |                     |___ settings.py
    |                     |___ urls.py
    |                     |___ wsgi.py
    |        
    |____ Scripts
    |           |___ ....... 
    |____ pyvenv.cfg  
```

### 10.3 Purpose of Applications in Django:

*Modularization*: 
Applications break down a large project into smaller, self-contained units, promoting better organization, maintainability, and reusability.
*Separation of Concerns*:
 Each application focuses on a specific functionality (e.g., user authentication, blog posts, e-commerce), keeping code focused and easier to manage.
*Independent Development*:
 Applications can be developed and tested independently, allowing for parallel work and easier collaboration.


### 10.4 creating multiple applications run the following commands

```bash
django-admin  startapp admission
django-admin  startapp student
django-admin  startapp teacher

```

 ### Purpose: 

Lists  installed all applications in your project, including built-in Django apps and your custom apps.
```python
INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
     # Add your custom apps here:
    'admission',
    'student',
    'teacher',
]

```
- Importance for multiple apps: Ensures Django recognizes and integrates the features and functionality of your newly created apps.



## Step-11 Creating Templtes

### 11.1 Create dynamic templates folder inside Application

    Create templates directory inside application and inside templates create another directory with same application name and inside it create html files, the result should be link this.

### 11.2 Folder Structure

```
virtual
    |____ lib
    |        |___site-packages  
    |            |____ app
    |            |    |___ Templates
    |            |    |   ├──home.html
    |            |    |
    |            |    ├── migrations/
    |            |    |  └── __init__.py
    |            |    |  ├── __init__.py
    |            |    |  ├── models.py
    |            |    |  ├── tests.py
    |            |    |  └── views.py 
    |            |    |
    |            |    ├── __init__.py
    |            |    ├── admin.py
    |            |    ├── apps.py
    |            |    ├── models.py
    |            |    ├── tests.py
    |            |    └── views.py 
    |            |   
    |            |___ projectname
    |                |___ projectname
    |                     |___ __init__.py   
    |                     |___ asgi.py
    |                     |___ settings.py
    |                     |___ urls.py
    |                     |___ wsgi.py
    |        
    |____ Scripts
    |           |___ ....... 
    |____ pyvenv.cfg  
```


## Step-12 Define Views

Code
```python  
from django.shortcuts import render
def home(request):
    name = "Muhammad Hashim"
    age = 23
    d = {'name':name, 'age':age}
    return render(request, 'SimpleApp/index.html', d)

```

### 12.1 Purpose of settings.py:

- It's the central configuration file for Django projects, defining various settings that control the project's behavior.
- It acts as a central hub for storing project-wide configurations, making customization and management easier.

### 12.2 Common Built-in Settings:

**1.Installed Apps**:

- *INSTALLED_APPS*: A list of installed Django apps and third-party apps that your project uses.
Controls which features and functionalities are available.

**2.Database Configuration**:

*DATABASES*: Defines the database settings, including engine, name, user, password, host, port, and other options.
Specifies how Django interacts with the database.

**3.Middleware**:

- *MIDDLEWARE*: A list of middleware classes that Django runs during request and response processing.
Handles tasks like authentication, security, session management, and more.

**4.Templates**:

- *TEMPLATES*: Settings for template engines, such as Django's built-in template engine or third-party engines.
Controls how templates are rendered and displayed.

**5.Static Files**:

- *STATIC_URL*: The base URL for serving static files (CSS, JavaScript, images).
Specifies where static files are located and how they're accessed.

**6.Media Files**:

- *MEDIA_URL*: The base URL for serving user-uploaded media files.
Similar to static files, but for user-generated content.

**7.Security**:

- *SECRET_KEY*: A secret key used for cryptographic signing and security.
Essential for security features like password hashing and session protection.

**8.Internationalization**:

- *LANGUAGE_CODE*: The default language for the project.
- *TIME_ZONE*: The default time zone for the project.
**9.Debugging**:

- *DEBUG*: Toggles debugging mode on or off.
Provides detailed error messages and stack traces during development.






## Step-13 url in projectlevel

### Code
```python
from django.contrib import admin
from django.urls import path, include
urlpatterns = [
    path('admin/', admin.site.urls),
    path('home/',include('app.urls')),
]
```

### Explain

### 13.1 Purpose of settings.py:

It's the central configuration file for Django projects, storing essential settings that control various aspects of the application.
It dictates how Django interacts with databases, templates, static files, email, security, and other functionalities.

### 13.2Common Built-in Settings:

### 1. Basic Configuration:

- *BASE_DIR*: Specifies the absolute path to the project's root directory.
- *SECRET_KEY*: A unique, secret string used for security purposes (e.g., signing cookies).
- *DEBUG*: A boolean flag that controls whether Django runs in debug mode (extra logging, error pages).
- *ALLOWED_HOSTS*: A list of allowed hostnames or IP addresses for security.




## Step-13 Create html document 

- inside app/ inside templates / inside home.html

### Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- <meta http-equiv="refresh" content="05"> -->
    <title>Div </title>
</head>
<body>
    <article>
        <h2>Google Chrome</h2>
        <p>Google Chrome is a web browser developed by Google, released in 2008. Chrome is the world's most popular web browser today!</p>
    </article>
    <details>
        <summary>Epcot Center</summary>
        <p>Hi,{{name}} How are you? Your age is {{age}}</p>
    </details>
    <p>This is just a simple paragraph</p>
</body>
</html>
```


## Step-14 Run Server

 ### 14.1 Define Server:

 -It's a computer program or device that provides a service to other programs or devices, called clients.
- It operates in a client-server model, where clients make requests and servers respond with the requested resources or services.

### 14.2 Key Functions:

- Receiving and Processing Requests: Servers listen for incoming requests from clients over a network or internet connection.
- Fulfilling Requests: They process the requests, retrieve or generate the necessary data or resources, and send back a response to the client.
- Sharing Resources and Services: Servers can provide various functionalities, including:
   - Sharing files (e.g., file servers)
   - Storing and managing databases (e.g., database servers)
   - Hosting websites (e.g., web servers)
   - Handling email (e.g., email servers)
   - Running applications (e.g., application servers)
   - Streaming media (e.g., media servers)
   - Handling gaming (e.g., game servers)
   - Performing computations (e.g., cloud servers)

### 14.3 Types of Servers:

1.**Physical Servers**: Dedicated hardware machines running server software.
2.**Virtual Servers**: Software-based emulations that share resources on a physical server.
3.**Cloud Servers**: Virtual servers offered as a service by cloud providers.

### Common Server Examples:

- Web servers (e.g., Apache, Nginx)
- Database servers (e.g., MySQL, PostgreSQL)
- File servers (e.g., Samba, NFS)
- Mail servers (e.g., Postfix, Exim)
- Application servers (e.g., Tomcat, JBoss)
- Game servers (e.g., Minecraft, Counter-Strike)

### 14.4 Essential Roles in Modern Computing:

Servers are fundamental to the operation of the internet, networks, and various applications.
They power websites, databases, email systems, online services, and more, enabling data sharing, communication, and collaboration.
  

 ### 14.5  How to run server in Django-Development
    - Open your command prompt or terminal.
    - Navigate to the root directory of your Django project. This is the directory that contains the manage.py file.
    eg;
    ```
    (virtual) PS E:\django\virtual\lib\site-packages\projectname>
    ```
    - To start the development server, run the following command:

```bash
 How to run server in Django-Development
```
Expected Output
```bash

```

    to quit server run the following command On windows

```bash
crtl + c
```


# Congradulations you get success to run Server










