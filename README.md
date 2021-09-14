[![Build Status](http://runbot.odoo.com/runbot/badge/flat/1/master.svg)](https://github.com/hoangviethung/muk_backend_theme_odoo14)
[![Tech Doc](http://img.shields.io/badge/master-docs-875A7B.svg?style=flat&colorA=8F8F8F)](https://github.com/hoangviethung/muk_backend_theme_odoo14)
[![Help](http://img.shields.io/badge/master-help-875A7B.svg?style=flat&colorA=8F8F8F)](https://github.com/hoangviethung/muk_backend_theme_odoo14)
[![Nightly Builds](http://img.shields.io/badge/master-nightly-875A7B.svg?style=flat&colorA=8F8F8F)](https://github.com/hoangviethung/muk_backend_theme_odoo14)

## MuK Web Theme

This module offers a mobile compatible design for Odoo Community. Furthermore it allows the user to define some design preferences. So he can choose the size of the sidebar and the position of the chatter. In addition, the background image of the app menu can be set for each company.

# Installation

To install this module, you need to:

Download the module and add it to your Odoo addons folder. Afterward, log on to your Odoo server and go to the Apps menu. Trigger the debug mode and update the list by clicking on the "Update Apps List" link. Now install the module by clicking on the install button.

Another way to install this module is via the package management for Python (PyPI).

To install our modules using the package manager make sure odoo-autodiscover is installed correctly. Then open a console and install the module by entering the following command:

pip install --extra-index-url https://nexus.mukit.at/repository/odoo/simple <module>

<b>Module:</b>

odoo<version>-addon-<module_name>

<b>Example:</b>

sudo -H pip3 install --extra-index-url https://nexus.mukit.at/repository/odoo/simple odoo11-addon-muk-utils

Once the installation has been successfully completed, the app is already in the correct folder. Log on to your Odoo server and go to the Apps menu. Trigger the debug mode and update the list by clicking on the "Update Apps List" link. Now install the module by clicking on the install button.

The biggest advantage of this variant is that you can now also update the app using the "pip" command. To do this, enter the following command in your console:

pip install --upgrade --extra-index-url https://nexus.mukit.at/repository/odoo/simple <module>

The module name consists of the Odoo version and the module name, where underscores are replaced by a dash.

When the process is finished, restart your server and update the application in Odoo. The steps are the same as for the installation only the button has changed from "Install" to "Upgrade".

You can also view available Apps directly in our repository and find a more detailed installation guide on our website.

For modules licensed under OPL-1, you will receive access data when you purchase the module. If the modules were not purchased directly from MuK IT please contact our support (hoangviet.hung.009@gmail.com) with a confirmation of purchase to receive the corresponding access data.

# Upgrade

To upgrade this module, you need to:

Download the module and add it to your Odoo addons folder. Restart the server and log on to your Odoo server. Select the Apps menu and upgrade the module by clicking on the upgrade button.

If you installed the module using the "pip" command, you can also update the module in the same way. Just type the following command into the console:

pip install --upgrade --extra-index-url https://nexus.mukit.at/repository/odoo/simple <module>

When the process is finished, restart your server and update the application in Odoo, just like you would normally.

# Configuration

No additional configuration is needed to use this module.

# Usage

After the module is installed, the design is adjusted accordingly.

# Author & Maintainer

This module is maintained by the MuK IT GmbH.

MuK IT is an Austrian company specialized in customizing and extending Odoo. We develop custom solutions for your individual needs to help you focus on your strength and expertise to grow your business.

## Getting started with Greenbeli

For a standard installation please follow the <a href="https://github.com/hoangviethung/muk_backend_theme_odoo14">Setup Template</a>
from the documentation.
