Slideshow Recipe
======================

This module is a simple config recipe that simply adds and updates config on your site
to implement a simple slideshow using the Flexslider module and Flexslider views.

We have also added an install file to add some sample content. Please install **Slideshow Sample Content** module for this.

**This recipe is still under development**, but suitable for testing and feedback. We appreciate
your ideas and input.

This recipe creates

 - A Slideshow content type
 - A view using Flexslider and Flexslider Views module to display Slideshows. For the slideshow images also added an image style.
 - A Flexslider configuration file for this slideshow.
 - Three sample slideshow content
 - Added some CSS to look nice using CSS Injector module.

 While some users may be happy with the configuration of this Slideshow feature 
 exactly as defined in the recipe. We expect that most users will use 
 this recipe as a starting point and customize it to meet their unique needs. 


Requirements
------------

Requires [BackdropCMS 1.20](https://github.com/backdrop/backdrop/releases/tag/1.20.0) or greater.

This recipe is currently configured to use the Flexslider module 
to display the slideshow. You will need to enable and configure the Flexslider and Flexslider Views module to benefit from that formatting. 

Installation
------------

- This recipe can be found in the Recipes package on the modules 
  page (admin/modules/list).

- Install this like any other module using the official Backdrop CMS 
  instructions at https://backdropcms.org/guide/modules.

- Disabling and uninstalling this module will not delete any of the 
  configuration that this module provides, but will disable any CSS
  files that came with the recipe.

After Installation
------------------

- Add a couple of "Slideshow" nodes to the site.

- By default Slideshow block is added on the Home layout on the top region, please place it correctly for your use case.

NOTE: In most cases you will need to customize your layout or css to get the slideshow to span the entire width of the
screen. Try using this block in the Top region, when using Basis as your theme to see a full width version of 
slideshow.

Uninstall or Upgrate Options
----------------------------

It is not currently possible to uninstall or upgrade this recipe.
If you no longer wish to keep this functionality, you will need 
to remove the items added by the recipe manually.


Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/slide_show_recipe/issues.

Feedback
--------

We are experimenting with config recipes and welcome your feedback. Please,
let us know how this config recipe worked for you and how you think we 
could improve it for other users in the future. 
https://github.com/backdrop-contrib/slide_show_recipe/issues

Current Maintainers
-------------------
- [Tim Erickson](https://github.com/stpaultim).
- [Sudipto Kumar Mitra (sudipto68)](https://github.com/sudipto68)

Credits
-------

- Sponsored by [Simplo](https://www.simplo.site)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.

