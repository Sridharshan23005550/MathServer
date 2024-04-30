# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
PS C:\Users\admin> env1/scripts/activate
* (env1) PS C:\Users\admin> git clone https://github.com/sridharshan/MathServer.git
Cloning into "MathServer'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 15 (delta 4), reused 3 (delta 3), pack-reused 10
Receiving objects: 100% (15/15), done. Resolving deltas: 100% (4/4), done. (
env1) PS C:\Users\admin> cd mathserver
* (env1) PS C:\Users\admin\mathserver> django-admin startproject yadhav
(env1) PS C:\Users\admin\mathserver> code.
(env1) PS C:\Users\admin\mathserver> cd yadhav
* (env1) PS C:\Users\admin\mathserver\yadhav> python manage.py startapp mathapp
( Watching for file changes with StatReloader
env1) PS C:\Users\admin\mathserver\sridharshan python manage.py runserver 8000
Performing system checks...
System check identified no issues (@silenced).
You have 18 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.
Run python manage.py migrate to apply them.
April 29, 2024 21:33:44
Django version 5.0.4, using settings 'sridharshan.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
[29/Apr/2024 21:33:48] "GET / HTTP/1.1" 200 1527
Not Found: /favicon.ico
[29/Apr/2024 21:33:48] "GET /favicon.ico HTTP/1.1" 404 2372
POST method is used request.POST: <QueryDict: {'csrfmiddlewaretoken': ['rBEIdcG7ahft2didfjo8bAfXNsy52]r@GDX@YMGT7DKIXELRFUTAyim6g2GgfG16'], 'radius': ['15'], 'height': ['10'], 'area': ['e']]>
radius 15
height - 10
Area 2355.0 [
29/Apr/2024 21:34:56] "POST / HTTP/1.1" 200 1534

## SERVER SIDE PR![c231f249-e791-4f72-8ca7-3470e84e21c7](https://github.com/selvasachein/MathServer/assets/149986733/08ad59ef-287b-4d3d-bcfc-9c42245c0cf8)
OCESSING:


## HOMEPAGE:
![8b6b8081-ffd1-4b57-b8e8-374da2ff09a2](https://github.com/selvasachein/MathServer/assets/149986733/24a5b875-74b5-46cb-b5c5-b668812e3682)


## RESULT:
The program for performing server side processing is completed successfully.
