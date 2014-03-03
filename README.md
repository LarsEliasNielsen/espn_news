ESPN News
=========

A block module for Drupal 7, that fetches sport news from ESPN Developer API.
Content belongs to ESPN and the ESPN Developer Center, all rights reserved.

This is a simple module that defines a block with latest sport news from ESPN. All methods are explained and documented, so take a look in the .module-file.

## Try it out
If you want to try out this module on a Drupal-site follow the intructions below:

***SSH***

If you have access to a webserver via SSH or working on a local project with a terminal, you can clone the project to your Drupal-site. Go to your Drupal-site, and go to `<YOUR_SITE>/sites/all/modules/` and clone the project:
```bash
git clone git@github.com:LarsEliasNielsen/espn_news.git espn_news
```

***Download***

If you don't have SSH access to your site, you can downlaod a ZIP-file containing the module and extract it to you Drupal-site. Download the ZIP from the [ESPN News repository](https://github.com/LarsEliasNielsen/espn_news), and extract it to `<YOUR_SITE>/sites/all/modules/`.
Rememeber to rename the extracted folder to `espn_news`, if a branch name is added to the folder name.


## Files
***espn_news.info***

This file describes the module to Drupal, and let you customize how your module is presented in the module overview (title, description, package, configuration settings).

***espn_news.module***

This file contains (for this module; all) logic and methods for the module. It specifies a block to Drupal and requests data and prints it.

***espn_news.install****

This file contains a couple of methods, that is run when the module is being installed/enabled/unabled/uninstalled.
Variables and tables are created/destroyed here.
