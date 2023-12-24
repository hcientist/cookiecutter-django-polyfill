# What

Default answers for most of [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django) for Django newbs especially those under my tutelage.

## How
1. somehow come to have this repo's `cookiecutter-django-simple.json` file on your machine.
    * note: you will need the path to this file in a moment where we'll refer to it as `PATH_TO_THIS_FILE` (e.g. on my machine it's at `~/dev/cookiecutter-django-polyfill/cookiecutter-django-simple.json` so i will substitute that for `PATH_TO_THIS_FILE` in the following steps)
2. With 1 small update detailed next, use [cookiecutter-django](https://github.com/cookiecutter/cookiecutter-django) as [it instructs in the Setting Up Development Environment steps here](https://cookiecutter-django.readthedocs.io/en/latest/developing-locally.html#setting-up-development-environment), except with an extra command line argument in step 3 (make this small addition):
    <pre>cookiecutter gh:cookiecutter/cookiecutter-django <ins>PATH_TO_THIS_FILE</ins></pre>

# When

Perhaps when you're very new to Django and you've been pointed in this direction.

# Why

Because the cookiecutter template or Django is fantastic, but for my purposes I want to be able to assume that my students have several of the options chosen as specified here.

# Who

* All my Django (and more) is with thanks to [Nathan Self](https://sanghani.cs.vt.edu/person/nathan-self/).
* Originally first-drafted by [Michael C. Stewart](https://hcientist.com/)
