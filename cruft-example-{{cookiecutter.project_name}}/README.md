# {{cookiecutter.project_display_name}}

This is a sample repository created from the cookiecutter template at {{cookiecutter._template}}. You can find more information about cookiecutter at https://www.cookiecutter.io/.

Cookiecutter templates are often used in combination with [cruft](https://cruft.github.io/cruft/) to track updates of the template in the downstream projects.

The content of this repository was initially generated with the following command:

```bash
cruft create \
    --no-input \
    --extra-context '{ "project_name": "{{cookiecutter.project_name}}", "project_display_name": "{{cookiecutter.project_display_name}}" }' \
    {{cookiecutter._template}}
```

