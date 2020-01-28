# Twig admin theme

Admin theme based on the twig engine.

## Branch Compatibility

* master branch is compatible with OXID eShop compilation master
* b-2.x branch is compatible with OXID eShop unreleased b-6.x
* v1.0.0 release is compatible with OXID eShop b-6.0 to b-6.2

## Installation

**Run the following command to install theme:**

```bash
composer require oxid-esales/twig-admin-theme
```

**(Only for PE) Install OXID eSales PE twig component:**

If you are using Professional Edition, please install Twig component for OXID eShop Professional Edition:

```bash
composer require oxid-esales/twig-component-pe
```

**(Only for EE) Install OXID eSales EE twig component:**

If you are using Enterprise Edition, please install Twig component for OXID eShop Enterprise Edition:

```bash
composer require oxid-esales/twig-component-ee
```

**Note:**

The twig theme for admin will be registered during the installation. If you are having some issues, that the wrong Admin 
theme is loaded, please check if the `oxid_esales.theme.admin.name` parameter is set correctly:

.. code:: yaml

    parameters:
      oxid_esales.theme.admin.name: 'admin_twig'


## License

See LICENSE file for license details.

## Bugs and Issues

If you experience any bugs or issues, please report them in the section **Twig engine** of https://bugs.oxid-esales.com.
