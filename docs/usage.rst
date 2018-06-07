=====
Usage
=====

To use dmango in a project, add it to your `INSTALLED_APPS`:

.. code-block:: python

    INSTALLED_APPS = (
        ...
        'dmango.apps.DmangoConfig',
        ...
    )

Add dmango's URL patterns:

.. code-block:: python

    from dmango import urls as dmango_urls


    urlpatterns = [
        ...
        url(r'^', include(dmango_urls)),
        ...
    ]
