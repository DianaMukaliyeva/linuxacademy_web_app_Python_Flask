
notes
========

notes is a note-taking application that allows us to write notes using **Markdown**. Ideally, this application would be great for storing code snippets with some notes about what we were doing and how the code works.

# Quickstart

## Installation

1. Ensure `pip` and `pipenv` are installed. To install the package after you've cloned the repository, you'll want to run the following command from within the project directory:

```
$ pipenv shell
$ pip install -r requirements.txt
```

2. Set up your local environment in .env.

3. Run the development server:

```
$ export FLASK_APP='.'
$ export FLASK_ENV=development # enables debug mode
$ flask run
```

4. Navigate to Home page http://localhost:5000
