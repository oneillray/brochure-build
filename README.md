# brochure-build
Bootstrap build for madebyray.com

## getting started
To get setup, you need to have the following installed

  * Ruby
  * Compass
  * Sass

Clone the repo and run ``compass compile`` to get the processed styles.

## custom Bootstrap build
You can comment out what you need/ don't need from ``_boostrap-custom.scss``
in the ``./assets/sass/`` folder. Re-compile the ``Sass`` and away you go.

## Lazyload
Lazyload is simple, just add the ``lazy`` class to each image tag and the 
initialisation in ``./assets/javascripts/app.js`` will take care of the rest.
