<div align="center">
    <h1 align="center">plone.recyclebin</h1>
</div>
<div align="center">
[![PyPI](https://img.shields.io/pypi/v/plone.recyclebin)](https://pypi.org/project/plone.recyclebin/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/plone.recyclebin)](https://pypi.org/project/plone.recyclebin/)
[![PyPI - Wheel](https://img.shields.io/pypi/wheel/plone.recyclebin)](https://pypi.org/project/plone.recyclebin/)
[![PyPI - License](https://img.shields.io/pypi/l/plone.recyclebin)](https://pypi.org/project/plone.recyclebin/)
[![PyPI - Status](https://img.shields.io/pypi/status/plone.recyclebin)](https://pypi.org/project/plone.recyclebin/)


[![PyPI - Plone Versions](https://img.shields.io/pypi/frameworkversions/plone/plone.recyclebin)](https://pypi.org/project/plone.recyclebin/)

[![CI](https://github.com/plone/plone.recyclebin/actions/workflows/main.yml/badge.svg)](https://github.com/plone/plone.recyclebin/actions/workflows/main.yml)
![Code Style](https://img.shields.io/badge/Code%20Style-Black-000000)

[![GitHub contributors](https://img.shields.io/github/contributors/plone/plone.recyclebin)](https://github.com/plone/plone.recyclebin)
[![GitHub Repo stars](https://img.shields.io/github/stars/plone/plone.recyclebin?style=social)](https://github.com/plone/plone.recyclebin)

</div>

A recycle bin for Plone, making it possible to restore deleted content.

## Features

TODO: List our awesome features

## Installation

Install plone.recyclebin with `pip`:

```shell
pip install plone.recyclebin
```

And to create the Plone site:

```shell
make create-site
```

## Contribute

- [Issue tracker](https://github.com/plone/plone.recyclebin/issues)
- [Source code](https://github.com/plone/plone.recyclebin/)

### Prerequisites ✅

-   An [operating system](https://6.docs.plone.org/install/create-project-cookieplone.html#prerequisites-for-installation) that runs all the requirements mentioned.
-   [uv](https://6.docs.plone.org/install/create-project-cookieplone.html#uv)
-   [Make](https://6.docs.plone.org/install/create-project-cookieplone.html#make)
-   [Git](https://6.docs.plone.org/install/create-project-cookieplone.html#git)
-   [Docker](https://docs.docker.com/get-started/get-docker/) (optional)

### Installation 🔧

1.  Clone this repository, then change your working directory.

    ```shell
    git clone git@github.com:plone/plone.recyclebin.git
    cd plone.recyclebin
    ```

2.  Install this code base.

    ```shell
    make install
    ```


### Add features using `plonecli` or `bobtemplates.plone`

This package provides markers as strings (`<!-- extra stuff goes here -->`) that are compatible with [`plonecli`](https://github.com/plone/plonecli) and [`bobtemplates.plone`](https://github.com/plone/bobtemplates.plone).
These markers act as hooks to add all kinds of subtemplates, including behaviors, control panels, upgrade steps, or other subtemplates from `plonecli`.

To run `plonecli` with configuration to target this package, run the following command.

```shell
make add <template_name>
```

For example, you can add a content type to your package with the following command.

```shell
make add content_type
```

You can add a behavior with the following command.

```shell
make add behavior
```

```{seealso}
You can check the list of available subtemplates in the [`bobtemplates.plone` `README.md` file](https://github.com/plone/bobtemplates.plone/?tab=readme-ov-file#provided-subtemplates).
See also the documentation of [Mockup and Patternslib](https://6.docs.plone.org/classic-ui/mockup.html) for how to build the UI toolkit for Classic UI.
```

## License

The project is licensed under GPLv2.

## Credits and acknowledgements 🙏

Generated using [Cookieplone (1.0.0)](https://github.com/plone/cookieplone) and [cookieplone-templates (f436000)](https://github.com/plone/cookieplone-templates/commit/f43600068a2ed0e833072cdc4963358a238a430a) on 2026-05-28 12:05:25.147512. A special thanks to all contributors and supporters!
