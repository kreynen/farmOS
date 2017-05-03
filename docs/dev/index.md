# Getting started with farmOS development

## Choose your adventure!

1. **farmOS core development** - Help develop features or fix bugs in farmOS
   itself.
2. **Contrib development** - Build modules that extend farmOS's functionality
   in general ways and contribute them to the public collection for other
   farmOS users to select from and install themselves.
3. **Custom development** - Extend farmOS for your own purposes, without
   necessarily contributing back to the core or contrib communities. Sometimes
   you just need something really specific that no one else needs!

## Set up a local instance

The first step is to set up a "local development instance" of farmOS that you
can tinker with. The currently recommended approach is to use
[Docker](https://www.docker.com/). For more information on installing Docker
and creating a local farmOS dev site, read the
[farmOS Docker documentation](/dev/docker).

## Enable development modules

Regardless of what you are doing, there are a few modules that will probably
be useful during development. The following is a list that are included in
farmOS, but are not enabled by default. To enable modules, log into farmOS as
user 1 and go to `/admin/extend`.

* **Features** - Enables administrators to package configuration into modules.
* **Features UI** - Provides the user interface for Features.
* **Field UI** - User interface for the Field API.
* **Views UI** - Administrative interface for Views.
