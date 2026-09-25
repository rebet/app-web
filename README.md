# Rebet Web Application

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

This is a skeleton for the Rebet web application.  
It is currently under development and has not been released yet.

## How To Setup

1. `composer create-project rebet/app-web my-app`
1. `cd my-app`
1. `composer rebet project:init` [^1]
   * Answer some configuration questions.
1. `code .`
1. **Reopen in Container** in your VSCode

[^1]: You can use `--` and `--no-interaction` option with any configure options you want as non blocking one liner command. (e.g. `composer rebet project:init -- --no-interaction --locale ja_JP`)
