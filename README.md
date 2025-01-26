# asdf-universal-ctags [![GitHub Actions Status:Commit](https://github.com/ompugao/mise-universal-ctags/workflows/Commit%20workflow/badge.svg)](https://github.com/ompugao/mise-universal-ctags/actions?query=workflow%3A%22Commit+workflow%22) [![GitHub Actions Status:Schedule](https://github.com/ompugao/mise-universal-ctags/workflows/Schedule%20workflow/badge.svg)](https://github.com/ompugao/mise-universal-ctags/actions?query=workflow%3A%22Schedule+workflow%22)

Universal-ctags plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

Forked from [mise-plugins/mise-vim](https://github.com/mise-plugins/mise-vim).

## Usage

### Install

The plugin can be install using the following command.

```sh
asdf plugin-add ctags https://github.com/ompugao/mise-universal-ctags.git
asdf install ctags <version>
```
### .tool-versions file

You can specify the version to install with a line like so in your .tool-versions file:
ctags <version>

### Using the CLI

You can then set the local/global version to your new version with `asdf local ctags <version>` or `asdf global ctags <version>`.

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of ctags.
