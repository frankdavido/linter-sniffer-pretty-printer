# Sniffer, Linter, Pretty Printer

A collection of configurations for PHPCS, the ESLint JavaScript linter, the Stylelint CSS linter, Editorconfig and Browserslist for your WordPress projects.

## Disclaimer

I use this as base for my themes and plugins.

If you want to contribute to WordPress Core, please make sure to follow the official WordPress Coding Standards.
I can't guarantee that using the configurations in this repository ensures 100% adherence to the official WordPress Coding Standards.

As a matter of fact, the following warning was given on the WP Australia Slack group:

> My recommendation is to _not_ use it, you won’t be adhering to WordPress’s coding standards if you use that repo.
>
> A whole bunch of things, there are _official_ packages with official coding standards, those are the packages that should be used.

Please use at your own discretion or write your own package.json and configs (maybe without Prettier).

## Origin of configs/packages (installed through npm or packagist)

*   eslint-config-wordpress: https://github.com/WordPress-Coding-Standards/eslint-config-wordpress

    Installation instructions from the readme:

    > Add this to your .eslintrc.json file:
    > `"extends": "wordpress"`

*   stylelint-config-wordpress: https://github.com/WordPress-Coding-Standards/stylelint-config-wordpress

    Installation instructions from the readme:

    > If you've installed stylelint-config-wordpress locally within your project, just set your stylelint config to:
    >
    > ```
    > {
    > "extends": "stylelint-config-wordpress"
    > }
    > ```

*   WPCS: https://github.com/WordPress-Coding-Standards/WordPress-Coding-Standards

*   Browserslist: https://github.com/WordPress/packages/tree/master/packages/browserslist-config

    Installation instructions from the readme:

    > Install the module `npm install @wordpress/browserslist-config`
    > Add this to your package.json file:
    >
    > ```
    > "browserslist": [
    > "extends @wordpress/browserslist-config"
    > ]
    > ```

## Origin of manually added configs

*   stylelint-order: https://sridharkatakam.com/format-css-per-wordpress-coding-standards-using-csscomb-sublime-text

*   The phpcs.xml.dist is slightly opinionated and based on https://github.com/copyblogger/genesis-sample/blob/develop/phpcs.xml.dist

*   .editorconfig: https://github.com/WordPress/wordpress-develop/blob/master/.editorconfig

## Why Prettier?

Because it makes life easier. But it might cause deviations from pure WordPress coding standards.

## Usage

Sridhar Katakam has written a tutorial on how to setup Visual Studio Code with Prettier and the configs from this repo.

https://sridharkatakam.com/linting-and-formatting-in-visual-studio-code-for-wordpress/

## Contributions

Feedback, bug reports, and pull requests are welcome.

## Contributors

Thank you to everyone contributing to this project.
