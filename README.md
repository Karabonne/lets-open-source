# Let's Open Source

This is a fork of @aligg's [Code Newbie
Tweets](https://github.com/aligg/Code-Newbie-Tweets). For more information about
the motivations behind this project, go to the original repo.

This is a fork where I revert most changes and file more bugs so there's more
stuff to do for this open source workshop at Hackbright Academy.

Also, I actually changed the whole scope of the project.

# The project: Pinbored

Pinbored is a clone of [pinboard.in](https://pinboard.in/), the "anti-social
bookmarking app".

Also, it will integrate with Reddit. Because why not.

## How to contribute

- Follow the instructions in [Installing for
  development](#Installing-for-development)
- Find an issue (or open a new one)
- Read the wiki
- ???
- Profit

## Installing for development

### Dependencies

- Python 3
- PostgreSQL
- A Reddit API key

### How to install

### Install project dependencies

In a virtual environment, run

```
pip install --upgrade pip
pip install -r requirements.txt
```

#### Run setup script

```
python setup.py
```

This script will

- Create a directory called `secret` with an empty `__init__.py` file inside
- Make a `keys.py` file in the `secret` directory

and remind you to populate `keys.py` with your Reddit API credentials.

#### Configuration

If you'd like to alter default behavior, set the following variables in your
environment:

- `FLASK_DB_URI`
- `FLASK_LISTEN_HOST`
- `FLASK_LISTEN_PORT`

