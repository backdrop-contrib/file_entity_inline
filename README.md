File Entity Inline
------------------
If you add fields to a file type, such as the image file type, by default these fields are only 
accessible through the manage files interface in Backdrop CMS Core. This module exposes these
additional fields and allows a site editor to manage them through other forms, such as node
edit forms or reference fields. 

Project Status
----------------
We ran this project through [Coder Upgrade](https://backdropcms.org/project/coder_upgrade)
and made a few small changes. There are no known bugs at the time of the initial beta release.

Please help test this module and report bugs in the [issue queue](https://github.com/backdrop-contrib/file_entity_inline/issues).

Instructions
-----------
1) Install this module using the official Backdrop CMS instructions at
https://backdropcms.org/guide/modules
2) Add custom fields to any file type (admin/structure/file-types).
3) Add an image or file field with custom fields to any content type (admin/structure/types).
4) In the field configuration for the content type, select the custom file fields you would like to expose on other forms. See "Inline fields." By default "All available fields" are selected.

Maintainers
-----------

- [Tim Erickson (stpaultim)](https://github.com/stpaultim)

Credits
-----------

- Support for this module provided by [Simplo.site](https://www.simplo.site)
- Initial port by [Alomgir Hossain](https://github.com/bdalomgir)
- Initial development for Drupal by [Nate Lampton](https://www.drupal.org/u/quicksketch)
- Recently maintained for Drupal by [Damien McKenna](https://www.drupal.org/u/damienmckenna)

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
