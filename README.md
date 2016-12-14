# HTML language support in Atom with Angular 2 syntax support

[![apm](https://img.shields.io/apm/v/language-html-angular.svg)](https://atom.io/packages/language-html-angular)
[![The MIT License](https://img.shields.io/badge/license-MIT-orange.svg)](https://github.com/drootz/language-html-angular/blob/master/LICENSE.md)
[![Join the chat at https://gitter.im/language-html-angular/Lobby](https://badges.gitter.im/language-html-angular/Lobby.svg)](https://gitter.im/language-html-angular/Lobby?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

Adds syntax highlighting and snippets to HTML files.

## Installation

Fire up a console and type:

        apm install language-html-angular

Or, inside Atom's settings select Install and then search for this package.

## Usage

Open a file in Atom editor and select the `HTML (ng2)` file syntax option.

Ensure to use a theme packages supporting Angular 2 syntax highlighting for this package:
- [tomorrow-night-eigthies-ng-syntax](https://atom.io/themes/tomorrow-night-eighties-ng-syntax)

### Styling Scopes

Here are the scopes used for styling Angular attributes in a syntax theme:

````

  .html {

    .entity.other.attribute-name.ng {
      color: @blue !important;
    }

    .punctuation.separator.key-value.ng {
      color: @blue !important;
    }

    .meta.attribute-with-value.ng {
      color: @yellow !important;
    }

    .punctuation.definition.string.begin.ng {
      color: @yellow !important;
    }

    .punctuation.definition.string.end.ng {
      color: @yellow !important;
    }

    .meta.toc-list.ng {
      color: @yellow !important;
    }

  }


````

***

Forked from the [HTML package for Atom](https://atom.io/packages/language-html).
