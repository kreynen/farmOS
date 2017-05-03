# Dependencies

farmOS dependencies are defined in `farm.info.yml`, and are automatically
enabled when farmOS is installed. This document describes all of the
dependencies explicitly listed in `farm.info.yml`, as well as any child
dependencies of the explicit dependencies.

## Core modules

Core modules come included with Drupal core.

* **Automated Cron** - Provides an automated way to run cron jobs, by executing
  them at the end of a server response.
* **Block** - Controls the visual building blocks a page is constructed with.
  Blocks are boxes of content rendered into an area, or region, of a web page.
* **Breakpoint** - Manage breakpoints and breakpoint groups for responsive
  designs.
* **File** - Defines a file field type.
* **System** - Handles general site configuration for administrators.
* **Toolbar** - Provides a toolbar that shows the top-level administration menu
  items and links from other modules.
* **Update Manager** - Checks for available updates, and can securely install
  or update modules and themes via a web interface.
* **User** - Manages the user registration and login system.
* **Views** - Create customized lists and queries from your database.

## Contrib modules

Contrib modules are general add-ons for Drupal created by the Drupal community.
They are used by farmOS, but are not specific to farmOS or agriculture in
general.

* **[Log](https://www.drupal.org/project/log)** - Provides a log entity type
  for real world record keeping.

## farmOS modules

farmOS modules are what bring everything together to create a Drupal
distribution that is specifically for farm record keeping and management.

* **Farm Action** - Provides an action log type.
* **Farm Blocks** - Provides common blocks used throughout the farmOS
  interface.
* **Farm Harvest** - Provides a harvest log type.
* **Farm Input** - Provides an input log type.
* **Farm Observation** - Provides an observation log type.
* **Farm People** - Provides tools for managing people on the farm.
* **Farm Roles** - Provides default user roles for farmOS.

## Themes

Themes are what give Drupal a specific look and feel. As opposed to modules,
which provide most of the functionality, themes focus on the display. They sit
on top of everything and make decisions about how they look.

* **farmOS Theme** - farmOS Drupal theme. Based on Bootstrap.
* **[Bootstrap](https://www.drupal.org/project/bootstrap)** - Built to use
Bootstrap, a sleek, intuitive, and powerful front-end framework for faster and
easier web development.
