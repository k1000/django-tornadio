About
-----

*django-tornadio* - django tornadio integration.
Known to work in Django 1.3


Installation
------------


1. Download and install::

        git clone https://github.com/k1000/django-tornadio
        cd django-stratus
        python setup.py install

   or using pip::     
    
        pip install -e git+https://github.com/k1000/django-tornadio#egg=django_tornadio

2. Add "django-tornadio" to your INSTALLED_APPS in "settings.py" 

USSAGE
------

Just execute command::

        ./manage.py runtornadio

    or::

        ./manage.py runtornadio --reload 8777 7666

where last nubmers indicate Tornadio Socket port and Flash policy server port respectively

OPTIONS
-------

*--reload* Tells Tornado to use auto-reloader.
*--flash_policy_file* Path to Flash policy file "flashpolicy.xml" (in "static" folder)
*--noxheaders* Tells Tornado to NOT override remote IP with X-Real-IP.

CONFIG
------

Ajust ROUTES in settings.py accordingly

DEPENDENCIES
------------
    * tornado_
    * tornadio_
    * django_
    
    
LICENSE
-------

django-stratus is released under the MIT License. See the LICENSE_ file for more
details.

.. _LICENSE: https://github.com/k1000/django-stratus/blob/master/LICENSE
.. _tornado: https://github.com/facebook/tornado
.. _tornadio: https://github.com/MrJoes/tornadio
.. _django: https://www.djangoproject.com/