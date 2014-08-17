-- ENSŌ SHARE SUMMARY --

Nice, consistent, image-free social share and follow icons using Font Awesome.

Ensō Share is a feature that combines the functionality of the Service Links,
Follow, Font Awesome and Printer, email and PDF versions modules. Font Awesome
classes are added to Service Links and Follow links to provide clean, flat,
scalable and accessible icons for all your social media needs. Fully commented
SASS and CSS provide great looking defaults and also make it easy to adjust the
styling to suit any site design.

Print, email, PDF and RSS feed icons are supported in addition to the common
social media services.

Ensō Share is a feature for the Ensō distribution but will work fine with any
Drupal site that meets the requirements.


-- REQUIREMENTS --

* Font Awesome (fontawesome)
* Service Links(service_links)
  - general_services 
  - print_services
* Follow (follow)
* Shorten URLs (shorten)
* Printer, email and PDF versions (print)
  - print_mail
  - print_pdf
  - print_pdf_dompdf
  - print_services
  - print_ui
* Strongarm (strongarm)
* CTools (ctools)


-- INSTALLATION --

Install all dependencies above then install the Ensō Share feature module in the
usual way.


-- CONFIGURATION --

Ensō Share has no specific configuration of its own. Please refer to the
documetation for the Service Links, Follow and Printer, email and PDF versions
modules to configure those (e.g. choosing which social media services you want
and what order they are to be displayed in etc).


-- CUSTOMIZATION --

You can customise the look and feel of the icons using either the provided SASS
or CSS files. Both are well commented but SASS is recommended as it has a number
of variables and flags to make it relatively easy to get the look you desire.
For instance, you can easily switch between color or monochomatic, icons and
text or icons only etc.


-- CONTACT --

Current maintainer:
* Brian Hay (inteja) - https://www.drupal.org/user/8781