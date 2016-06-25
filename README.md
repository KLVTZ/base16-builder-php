# Base16 Builder PHP
An example PHP implementation of a base16 builder that follows the conventions found at: https://github.com/chriskempson/base16
Requires PHP 5.3 or greater.

**This is an early proof of concept application and is likely to change**

## Installation

    git clone https://github.com/chriskempson/base16-builder-php
    cd base16-builder-php
    composer install

## Usage

    php cli.php update
Updates all scheme and template repositories as defined in `schemes.yaml` and `templates.yaml`.

    php cli.php
Build all templates using all schemes

## Why on earth use PHP?
Because anyone can read PHP, even if they can't program :wink: