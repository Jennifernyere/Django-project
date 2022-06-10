# Django-project

Zuri project submission

0\lib\site-packages (20.14.1)
Requirement already satisfied: filelock<4,>=3.2 in c:\users\user\appdata\local\programs\python\python310\lib\site-packages (from virtualenv) (3.6.0)
Requirement already satisfied: six<2,>=1.9.0 in c:\users\user\appdata\local\programs\python\python310\lib\site-packages (from virtualenv) (1.16.0)
Requirement already satisfied: platformdirs<3,>=2 in c:\users\user\appdata\local\programs\python\python310\lib\site-packages (from virtualenv) (2.5.2)
Requirement already satisfied: distlib<1,>=0.3.1 in c:\users\user\appdata\local\programs\python\python310\lib\site-packages (from virtualenv) (0.3.4)
PS C:\Users\user> cd desktop
PS C:\Users\user\desktop> mkdir Zuri_project


Mode                 LastWriteTime         Length Name                                           
----                 -------------         ------ ----                                           
d-----         6/10/2022   7:43 AM                Zuri_project                                   


PS C:\Users\user\desktop> cd Zuri_project
PS C:\Users\user\desktop\Zuri_project> python -m venv myenv
PS C:\Users\user\desktop\Zuri_project> dir


    Directory: C:\Users\user\desktop\Zuri_project

Mode                 LastWriteTime         Length Name                                           
----                 -------------         ------ ----
d-----         6/10/2022   7:43 AM                myenv


PS C:\Users\user\desktop\Zuri_project> myenv\Scripts\activate
(myenv) PS C:\Users\user\desktop\Zuri_project> pip install django
Collecting django
  Using cached Django-4.0.5-py3-none-any.whl (8.0 MB)
Collecting tzdata
  Using cached tzdata-2022.1-py2.py3-none-any.whl (339 kB)
Collecting sqlparse>=0.2.2
  Using cached sqlparse-0.4.2-py3-none-any.whl (42 kB)
Collecting asgiref<4,>=3.4.1
  Using cached asgiref-3.5.2-py3-none-any.whl (22 kB)
Installing collected packages: tzdata, sqlparse, asgiref, django
Successfully installed asgiref-3.5.2 django-4.0.5 sqlparse-0.4.2 tzdata-2022.1
WARNING: You are using pip version 22.0.4; however, version 22.1.2 is available.
You should consider upgrading via the 'C:\Users\user\desktop\Zuri_project\myenv\Scripts\python.exe -m pip install --upgrade pip' command.
(myenv) PS C:\Users\user\desktop\Zuri_project> cd Jennifernyere
(myenv) PS C:\Users\user\desktop\Zuri_project\Jennifernyere> dir


    Directory: C:\Users\user\desktop\Zuri_project\Jennifernyere


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----         6/10/2022   7:46 AM                Jennifernyere
-a----         6/10/2022   7:46 AM            691 manage.py


(myenv) PS C:\Users\user\desktop\Zuri_project\Jennifernyere> python manage.py migrate
Operations to perform:
  Apply all migrations: admin, auth, contenttypes, sessions
Running migrations:
  Applying contenttypes.0001_initial... OK
  Applying auth.0001_initial... OK
  Applying admin.0001_initial... OK
  Applying admin.0002_logentry_remove_auto_add... OK
  Applying admin.0003_logentry_add_action_flag_choices... OK
  Applying contenttypes.0002_remove_content_type_name... OK
  Applying auth.0002_alter_permission_name_max_length... OK
  Applying auth.0003_alter_user_email_max_length... OK
  Applying auth.0004_alter_user_username_opts... OK
  Applying auth.0005_alter_user_last_login_null... OK
  Applying auth.0006_require_contenttypes_0002... OK
  Applying auth.0007_alter_validators_add_error_messages... OK
  Applying auth.0008_alter_user_username_max_length... OK
  Applying auth.0009_alter_user_last_name_max_length... OK
  Applying auth.0010_alter_group_name_max_length... OK
  Applying auth.0011_update_proxy_permissions... OK
  Applying auth.0012_alter_user_first_name_max_length... OK
  Applying sessions.0001_initial... OK
(myenv) PS C:\Users\user\desktop\Zuri_project\Jennifernyere> python manage.py runserver
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
June 10, 2022 - 07:48:02
Django version 4.0.5, using settings 'Jennifernyere.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[10/Jun/2022 07:48:12] "GET / HTTP/1.1" 200 10697
[10/Jun/2022 07:48:12] "GET /static/admin/css/fonts.css HTTP/1.1" 200 423
[10/Jun/2022 07:48:13] "GET /static/admin/fonts/Roboto-Bold-webfont.woff HTTP/1.1" 200 86184
[10/Jun/2022 07:48:13] "GET /static/admin/fonts/Roboto-Light-webfont.woff HTTP/1.1" 200 85692
[10/Jun/2022 07:48:13] "GET /static/admin/fonts/Roboto-Regular-webfont.woff HTTP/1.1" 200 85876
Not Found: /favicon.ico
[10/Jun/2022 07:48:14] "GET /favicon.ico HTTP/1.1" 404 2117
