#######################
Django Addons Framework
#######################

Warning:: This is the future branch for the complete refactor of aldryn-addons
          to a more genericly useful system called django-addons.

`Django addons`_ are re-usable django apps that follow certain conventions to
abstract out complicated configuration from the individual django website
project into upgradable packages. With this approach it is possible
to avoid repetitive "add this to ``INSTALLED_APPS`` and that to
``MIDDLEWARE_CLASSES`` and add these to ``urls.py``" work. The settings logic
is bundled with the Addon and only interesting "meta" settings are exposed.

``django-addons`` is a framework to utilise such Addons in django projects.

The goal is to keep the footprint inside the django website project as small
as possible, so updating things usually just mean bumping a version in
``requirements.txt`` and no other changes in the project.

TODO: Installation instructions and Usage.
