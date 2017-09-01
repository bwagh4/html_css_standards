# Files &amp; Folders

## Folder Structure

Our standard folder structure is as follows:

```diff
└── assets
    ├── media
    |   ├── images
    |   ├── fonts
    |   └── uploads
	|   └── View
    ├── Content(styles)
    ├── scripts
    └── vendor(Third party)
```

Additionally, an example of a typical sass directory structure can be found in [the sass section](/standards/scss.md#folder-structure).

## File Names

Use lowercase for all file names (including images) with hyphens as delimiters between words.

The only exception to this rule is SCSS partials which should be prefixed with an underscore.

**Good Examples**

* modern.css
* global-masthead.html
* common.png
* _globle.scss

## Storage of Dev Assets

Do not store development assets such as wireframes, PSDs, sprite source files, etc. in the actual project respository.