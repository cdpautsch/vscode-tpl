# VSCODE-TPL README

The Pattern Language (TPL) syntax highlighting extension for Visual Studio Code. TPL is used to create rules and models which describe applications, products and other real-world entities that have been modeled in BMC Discovery.

This software is based on existing extension for Atom editor: https://github.com/trianglesis/language-tplpre

TPL is used in BMC's Discovery application. Full documentation can be found here: https://docs.bmc.com/docs/display/DISCO113

TPL Documentation: https://docs.bmc.com/docs/display/DISCO113/The+Pattern+Language+TPL

This extension is not endorsed or sponsored by BMC in any way. The intent is to provide a tool to help developers who work with TPL and Discovery.

## Why Visual Studio Code?
Visual Studio Code is a much more powerful tool than simple text editors. It is customizable and lightweight, making it ideal for a lesser known language such as TPL. You can open up a directory of TPL patterns, giving you the option to search them all inside the editor, make global changes, and organize projects with greater efficiency. It runs on Windows, Mac, and Linux.

Download VS Code here: https://code.visualstudio.com/

## Installation
* Clone the Git repo to your computer:
    * Using SSH: `git clone git@github.com:cdpautsch/vscode-tpl.git`. _Note: This method requires you to setup an [SSH key](https://help.github.com/en/articles/connecting-to-github-with-ssh)_.
    * Using HTTPS: `git clone https://github.com/cdpautsch/vscode-tpl.git`
* Download and copy the extension (the entire folder) into the `<user home>/.vscode/extensions` folder and restart Visual Studio Code.

_Note: Once the language is more polished, we will eventually publish it to the VSCode extension marketplace, allowing you to enable the extension entirely from within VSCode._

## Want to Contribute?
This repository is open to contributions from others. Please follow contribution guidelines:
* For bugs or other problems, please create an issue using the bug template.
* If you have a particular feature in mind, please create an issue using the feature template.
* New features and fixes should be made in a new branch, split off from master, then merged with a pull request that requires approvals of at least 2 others (or admin approval).

## Future Plans
* Publish the extension to VSCode marketplace once the extension has matured and been refined.
* Develop a custom theme which provides custom theming for TPL colors
* Develop a system for linting TPL code
* Develop a system for error-checking
