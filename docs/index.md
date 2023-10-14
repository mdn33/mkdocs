# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Marco Nepi

    bla bla bla

::: src.foo.bar
    handler: python

::: src.foo.bar2

# Documentation for `MyClass`

::: src.foo.MyClass
    handler: python
    options:
      members:
        - method_a
        - method_b
      show_root_heading: false
      show_source: false


::: src.test.bar2