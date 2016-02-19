# drf-auth
Simple authentication and user management built with Django Rest Framework.

## Quick start

1. Add "drfauth" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'drfauth',
    ]

2. Include the drfauth URLconf in your project urls.py like this::

    url(r'^drfauth/', include('drfauth.urls')),

3. Run `python manage.py migrate` to create the drfauth models.

4. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

5. Visit http://127.0.0.1:8000/drfauth/ to participate in the poll.