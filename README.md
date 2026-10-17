# Django questions and answers (OTUS, 2021)

[English](README.md) | [Русский](README.ru.md)

Django question-and-answer application with user profiles, tags and voting.

Course work from OTUS.

## Get the code

```bash
git clone https://github.com/ivan-zamula/django-questions-2021-otus.git
cd django-questions-2021-otus
```

## What the code covers

- Questions and answers with tags, search and pagination.
- Registration, sign-in and user profiles with avatars.
- Voting on questions and answers, and selecting an accepted answer.
- Email notifications for new answers.

## Project structure

| Path | Purpose |
| --- | --- |
| [questions](questions) | Questions, answers, tags and search |
| [users](users) | Accounts and profile images |
| [votes](votes) | Voting and ranking models |
| [otus_django](otus_django) | Django configuration and main URLs |
| [homework](homework) | Original assignment and interface references |

## Development entry points

Start with [manage.py](manage.py) and [project settings](otus_django/settings.py). The code uses Django, `django-crispy-forms` and Pillow. Use versions compatible with this course-era application and configure local database and email settings before starting Django.

The [assignment PDF](homework/homework.pdf) describes the exercise. Images in `homework/` are interface references supplied with the assignment.
