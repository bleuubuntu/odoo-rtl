# Odoo RTL (Right to left) Project

This project developed as a set of modules to provide Right to left support for Odoo (formely known as OpenERP).

the project contains 3 main modules that cover the three main features in odoo that require RTL support:

* the backend module (web module and its descendants).
* the report module.
* the frontend (website) module and its descendant modules.

## Installation

## Note on Odoo installation.

*It seems that the direct download of odoo from their website or from nightly build are not the latest built according to issue #odoo/798, until they fix this issue, you have to [download](https://github.com/odoo/odoo/archive/8.0.zip) or  clone directly from github.com/odoo/odoo and switch to branch 8.0 before launch the server, this doc will not cover odoo installation process*

#### For Backend UI
1. [download](https://github.com/barsi/odoo-rtl/archive/master.zip) and extract the modules in addons folder.
2. restart odoo server.
3. go to settings => update modules list.
4. go to settings => language and make sure your target language (e.g. arabic) is Right to left direction.
5. install **Web RTL** module.
6. go to preference and change your language to an RTL language, or restart your browser if you already using the target language.

#### For Reports
1. Install Report RTL.
2. change your language into RTL language.
3. select any report and print it.
4. if your report still in LTR, make sure that the report is not depends on Partner's language (e.g. Invoice Reports, Sale report). or review steps of backend UI.

#### For Frontend
1. Install Website RTL
2. go to website, and select the target language.


## Contributions and Support
1. you can post an issue (for bugs and new features).
2. create a pull request.
3. or by email (if you dont have a github account).


## For OpenERP 7.0 RTL
we developed an RTL support for V7.0 reports, go **[to this link.](https://github.com/barsi/openerp-rtl)**

### Credits
Thanks go to Obay Albadri, he started RTL css for Version 7.0, we continue adding above it.

### License
This project is licensed under [AGPL v3](http://www.gnu.org/licenses/agpl-3.0.html) (the same as odoo).

