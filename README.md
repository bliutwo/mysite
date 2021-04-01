# Webapp Template

[Bookmark](https://docs.djangoproject.com/en/3.1/intro/tutorial01/)

This is a template for making a Heroku Python/Django app. The goal is to have a working implementation with frontend and backend where functionality can be implemented quickly with a fork.

**Note**: I will only be adding files that I change from the default `django-admin startproject mysite` command, since doing a `git add .` adds the section of code with a secret key.

## Frontend Checklist

- [ ] Form fill boxes
- [ ] Drop-down menu with options
- [ ] Upload text file

## Backend Checklist

- [ ] Parse uploaded text file
- [ ] Parse drop-down menu information
- [ ] Parse form fill box information
- [ ] Display information on screen
- [ ] Allow user to interact with and change on-screen information

## Misc. Notes

### Three-Step Guide to Making Model Changes

- Change your models (in `models.py`).
- Run `python3 manage.py makemigrations` to create migrations for those changes.
- Run `python3 manage.py migrate` to apply those changes to the database.
