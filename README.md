@TODO
=====

- support all config options (dynamically) - https://github.com/swagger-api/swagger-ui#parameters
- update readme / config


Swagger UI Bundle
=================

Creates a [swagger-ui](https://github.com/wordnik/swagger-ui) page (something like [this](http://petstore.swagger.wordnik.com/)) in your Symfony2 application.

* [x] Basic functionalities
* [x] Configurable authentication methods
* [x] Unit tests

# Documentation

* [Installation & Usage](https://github.com/ideahq/swagger-ui-bundle/blob/master/Resources/doc/installation-and-usage.md)
* [Authentication](https://github.com/ideahq/swagger-ui-bundle/blob/master/Resources/doc/authentication.md)
* [Overriding templates](https://github.com/ideahq/swagger-ui-bundle/blob/master/Resources/doc/overriding-templates.md)

## Configuration reference

```yaml
ideahq_swagger_ui:
    url:        ~ # Required
    static_resources:
        resource_dir:         null
        resource_list_filename:  api-docs.json
    operations_sorter:               null
