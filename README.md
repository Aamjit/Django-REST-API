# learning-Django

<hr>

_Django project to create a small REST API using djangorestframework_

### Building an API to display a list of books present in the database

![screenshot](https://github.com/Aamjit/learning-Django/blob/main/Screenshot%202021-10-19%20at%2012-07-17%20Book%20List%20%E2%80%93%20Django%20REST%20framework.png)

### API

<p> API is an acronym for Application Programming Interface that software uses to access data(in web development) that separates back-end from the front-end. Representational State Transfer (REST) is an architectural style for an application program interface (API) first proposed in 2000 by Roy Fielding in his dissertation thesis. It is an approach to building APIs on top of the web, which means on top of the HTTP protocol. Every Restful API are stateless, supports common HTTP verbs (GET, POST, PUT, DELETE, etc.)  and returns data either in JSON or XML formats.
</p>

<p>Django is not just the Python Web Development Framework but also the most powerful toolkit for building Web APIs. It is used for making back-end API for large companies like Instagram, Disqus, etc. rather than just a monolithic websites.
</p>

We can run the project by
- Navigating to the project folder that contains
  - .vscode
  - bookapi
  - db.sqlite3
  - manage.py
  - myApp1
  - Pipfile
  - Pipfile.lock
  - README.md
- Run the command `python manage.py runserver` in the CLI. (Make sure python is configured in your system.)
- After running we will see some logs.
```
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
October 19, 2021 - 11:17:49
Django version 3.1.2, using settings 'myApp1.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```

- THis means your projects is up and running. After this go to the link by `ctrl + click` or typing the link in the browser followed by a `/api/`
- The link should look something like this `http://127.0.0.1:8000/api/`
- Then it will show you the list of the books that are in the database. That's it for this. ♾️
