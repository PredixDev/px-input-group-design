# Button Group

Predix Experience Input Group module is a simple implementation of input groups.

## Demo

You can review input group styles and recommended markup here: https://github.build.ge.com/pages/PXd/px-input-group-design

## Dependencies

Px's Input Group module depends on two other PXd modules:

* [px-buttons-design](https://github.build.ge.com/PXd/px-buttons-design)
* [px-forms-design](https://github.build.ge.com/PXd/px-forms-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save https://github.build.ge.com/PXd/px-input-group-design.git

Once installed, `@import` into your project's Sass file in its Objects layer:

    @import "../px-input-group-design/objects.input-group";

See [px-getting-started](https://github.build.ge.com/PXd/px-getting-started#a-note-about-relative-import-paths) for an explanation of the `../`

## Import once

All rulesets are wrapped in the following `@if` statement:

    @if import-once('objects.input-group') { ... }

## Usage

The following variables are available for use in the module:

    $inuit-input-group-color
    $inuit-input-group-color--icon
