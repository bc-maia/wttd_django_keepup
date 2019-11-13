# SUSTAINABLE DJANGO

## Keeping Django Code Update when further versions are release

Python [pip](https://pip.pypa.io/en/stable/) documentation

Remember to backup your current pip installed apps:

```console
pip freeze > requirements.txt
```

Check the [release notes](https://docs.djangoproject.com/en/2.2/releases/2.2/) and

Update the desired package: (without a tag, the package will be updated to the latest version)

```console
pip install --update django
```

And check if your code has some needed fix:

```console
> python manage.py check

System check identified no issues (0 silenced).
```
