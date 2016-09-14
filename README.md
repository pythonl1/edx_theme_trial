# edx-bootstrap-theme - LMS
edx-bootstrap-theme for open edX dogwood release (comprehensive theming)

> Open edX responsive theme using [Bootstrap](http://getbootstrap.com/).
> LMS Landing Page
![Screenshot](https://github.com/dadasoz/edx-bootstrap-theme/blob/master/docs/images/1.png)

> LMS Login Page
![Screenshot](https://github.com/dadasoz/edx-bootstrap-theme/blob/master/docs/images/2.png)

> LMS Registration Page
![Screenshot](https://github.com/dadasoz/edx-bootstrap-theme/blob/master/docs/images/3.png)

> LMS Dashboard
![Screenshot](https://github.com/dadasoz/edx-bootstrap-theme/blob/master/docs/images/4.png)

## About this Open edX theme

It is based on [Bootstrap](http://getbootstrap.com/), it uses bootstrap's Sass library – which is used by Open edX).

## How to use this theme

First, open your '/edx/app/edxapp/edx-platform/themes' directory and clone this repo in as edx-bootstrap-theme. 

Next, open your 'lms.env.json' file and edit 'COMPREHENSIVE_THEME_DIR' to '/edx/app/edxapp/edx-platform/themes/edx-bootstrap-theme'

Save this file, and run 'paver updaate_assets lms' then 'paver lms'.
