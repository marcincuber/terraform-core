Terraform-core plugin for Sublime Text 3
====================================

### Features:

* Syntax highlighting for `.tf`,`.tfvars` and `.hcl` files.
* Format on save using `terraform fmt` (only available in version >= 0.6.15)
* Code completion for resources and data sources
* Terraform snippets supporing new syntax variables (terraform version >=0.12)

Installation
------------

### Using Package Control

1. Having [Package Control](https://packagecontrol.io/installation) installed
2. Open the palette by pressing `Ctrl+Shift+P` (Win, Linux) or `Cmd+Shift+P` (OS X).
3. Select _"Package Control: Add Repository"_
4. Enter `https://github.com/marcincuber/terraform-core`
5. Open command palette again
6. Select _"Package Control: Install Package"_
7. Select _"sublime-terraform"_

### Manually

1. Open the Sublime Text Packages folder
    - OS X: `~/Library/Application Support/Sublime Text 3/Packages/`
    - Windows: `%APPDATA%/Sublime Text 3/Packages/`
    - Linux (Ubuntu/Debian): `~/.config/sublime-text-3/Packages/`

2. Clone this repo:

```
$ https://github.com/marcincuber/terraform-core
```

## Configuration

The defaults are available in the `Terraform.sublime-settings` file.

## Development

To update the completion files you will need Ruby 2.2+

1. Install Ruby
2. `bundle install`
3. `bundle exec rake completions`

## Credit

Plugin based on work available in:

- [Terraform.tmLanguage](https://github.com/alexlouden/Terraform.tmLanguage)
- [sublime-terraform](https://github.com/tmichel/sublime-terraform)