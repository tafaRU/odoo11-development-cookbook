# odoo11-development-cookbook
This repository is meant to practice Odoo development by following the exercises in the book `Odoo 11 Development
Cookbook - Second Edition`. The version of Odoo used will be 12.0 instead of 11.0.  
[Here](https://www.packtpub.com/application-development/odoo-11-development-coobook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788471817) is available its related code repository, published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.

## Chapter 4
### Using scaffold to create a module
To quickly create a new modules, Odoo provides the `scaffold` command.

```
$ ~/odoo-dev/odoo/odoo-bin scaffold my_scaffolded
```
To use template provided by [OCA](https://github.com/OCA/maintainer-tools/tree/master/template/module), we can use the following command:
```
$ ~/odoo-dev/odoo/odoo-bin scaffold -t ~/odoo-dev/maintainer-tools/template/module my_oca_scaffolded

```
