# Integrating Tinymce with Django and React

## Introduction
In this tutorial, we will explore how to seamlessly integrate Tinymce, a powerful rich text editor, into a web application built using Django on the backend and React on the frontend. Offering a user-friendly editing experience, Tinymce is a popular choice for applications that require versatile and rich content creation capabilities.

## Installation
To set up the project, you’ll need to install a few dependencies:

### Django:

First, install Django, which is a high-level Python web framework that promotes rapid development of secure and maintainable websites:

```bash
pip install django
```
Django follows the model-template-views (MTV) architectural pattern and offers many built-in features for user authentication, database management, and web routing.

### django-cors-headers:

To handle Cross-Origin Resource Sharing (CORS), install the django-cors-headers package:

```bash
pip install django-cors-headers
```
This is crucial when your frontend (React) and backend (Django) are hosted on different domains or ports during development.

## installations for frontend

lets move to our frontend folder

```bash
cd frontend
```

now we install the needed libraries

### axios:
```bash
npm install axios
```
we use the axios library to send requests from frontend to backend

### tinymce
```bash
npm install @tinymce/tinymce-react
```

we need this library to use the TinyMCE editor in out page.


for the rest of the tutorial checkout my Medium essay about this project:
##### https://medium.com/@arad.shahrizad/integrating-tinymce-with-django-and-react-5f3a5815f9cc