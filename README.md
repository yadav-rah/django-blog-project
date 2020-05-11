# Python-Django Blog Project @ 2017

This is a basic Python-Django based blog posting application.

## Project Setup

1. Fork & clone the project.
2. Create a virtual environment using `python3 -m venv blogproject`, this will create a *blogproject* folder.

3. Activate the virtual environment using `source path_to_blogproject/bin/activate`. Activating the virtual environment will change your shell’s prompt to show what virtual environment you’re using.

    ```bash

    $ python --version
    Python 2.7.15+
    $ source blogpost/bin/activate
    (blogpost) $ 
    (blogpost) $ python --version
    Python 3.6.8
    (blogpost) $

    ```

4. Navigate to the project directory. 

5. Using `pip install -r requirements.txt`install required packages for the blog project.

6. Using `python manage.py runserver 0.0.0.0:8000` start django server.

7. On you browser hit `localhost:8000`, your blog project is up and running.

## Project Requirements

```python
python >= 3.5.2
django == 1.10.0
django-bootstrap3==11.1.0
```

### Happy Learning

Followed & learned from **Jose Portilla-Python Full Stack Development** Udemy course.