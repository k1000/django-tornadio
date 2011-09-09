About
-----

*django-tornadio* - django tornadio integration.
Known to work in Django 1.3

Features
--------

* manage multimple Projects - GIT repositories
* create/uplod/modify/delete files together with GIT commits
* view commit history and its diffs for any file 
* browse and view files as tehy was in any point of the repo history
* editor syntax highliting (thanx to CodeMirror 2)
* editor zen-coding for .html nad .css files ( thanx to zen-texarea.js )


Installation
------------


1. Download and install::

        git clone https://github.com/k1000/django-stratus
        cd django-stratus
        python setup.py install

   or using pip::     
    
        pip install -e git+https://github.com/k1000/django-stratus#egg=stratus

2. Add "stratus" to your INSTALLED_APPS in "settings.py" 

USSAGE
------

Just execute command::

        ./manage.py runtornadio --reload 8777


CONFIG
------

Ajust ROUTES in settings.py

DEPENDENCIES
------------
    * tornado
    * tornadio
    * django
    
    
LICENSE
-------

django-stratus is released under the MIT License. See the LICENSE_ file for more
details.

.. _LICENSE: https://github.com/k1000/django-stratus/blob/master/LICENSE

