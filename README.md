# Notes-To-Self

An app for writing time-stamped notes to an SQLite database.

By default, this app runs in debug mode.

All notes are saved to the 'test.db' file.

This app is a fork of [this repo](https://github.com/jakerieger/FlaskIntroduction) for this [blog post](https://www.center-the-div.com/2020/06/notes-to-self-python-flask-database-app.html).

# Do you need to use the virtual environment?

If all the modules listed in the 'requirements.txt' file are installed globally, then the virtual environment won't be required.

But if the virtual environment is required, then enter the following commands

```
$ cd env/bin/
$ source activate

```

# To deactivate the virtual environment

```
$ deactivate

```

# To run the app on your linux machine

Open a terminal in the the working directory, then run the command

```
$ python3 app.py

```

# Or to save typing

Add the following line to your '.bashrc' file.

```
alias p3='python3 app.py'

```

# Boomark 'localhost:5000'

Once the server is running, open your browser at [localhost:5000](http://localhost:5000/) to use the app.
