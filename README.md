
notes
========

notes is a note-taking application that allows us to write notes using **Markdown**. Ideally, this application would be great for storing code snippets with some notes about what we were doing and how the code works.

# Quickstart

## Installation


1. Set up your local environment in .env.

2. Ensure `pip` and `pipenv` are installed. To install the package after you've cloned the repository, you'll want to run the following command from within the project directory:

```
$ pipenv install
$ pipenv shell
```

3. For the first time apply the migration to the database:

```
$ flask db upgrade
```

4. Run the development server:

```
$ flask run
```

5. Navigate to Home page http://localhost:5000

##License
notes is a public domain work, dedicated using CC0 1.0. Feel free to do whatever you want with it.
