# Zayzafoun

A simple Arabic blog script written in Python & Flask. Right now the script interface is available in Arabic only.

Thanks for:

* Python: https://www.python.org/
* Flask: http://flask.pocoo.org/
* FontAwesome: http://fortawesome.github.io/Font-Awesome/
* TinyMCE: http://www.tinymce.com/
* LESS: http://lesscss.org/

By: M.Hanny Sabbagh <hannysabbagh[at]hotmail.com]

### Screenshots:

![Screenshot 1](/Screenshot-1.png)

![Screenshot 2](/Screenshot-2.png)

![Screenshot 3](/Screenshot-3.png)

### Installation:

Download all the files an extract them to a new folder, then run:

    ./zayzafoun.py

or by using make

    make run

And to initialize the database (for easy migration tasks)

    make initdb

For deployment with apache2, you may see this: http://flask.pocoo.org/docs/0.10/deploying/mod_wsgi/ For deployment with nginx and others: http://flask.pocoo.org/docs/0.10/deploying/uwsgi/

### TODO:

* Create Admin control panel.
* Create Email subscription widget in the footer.
* Add "ShareThis" widget to posts.
* Change the design.

### Bugs and Requests:

You can open an issue here: https://github.com/mhannysabbagh/zayzafoun/issues
