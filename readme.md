# Codeception Module CLI

A Codeception module for testing basic shell commands and shell output.

[![Actions Status](https://github.com/Codeception/module-cli/workflows/CI/badge.svg)](https://github.com/Codeception/module-cli/actions)
[![Latest Stable Version](https://poser.pugx.org/codeception/module-cli/v/stable)](https://github.com/Codeception/module-cli/releases)
[![Total Downloads](https://poser.pugx.org/codeception/module-cli/downloads)](https://packagist.org/packages/codeception/module-cli)
[![License](https://poser.pugx.org/codeception/module-cli/license)](/LICENSE)

## Requirements

* `PHP 7.4` or higher.

## Installation

```
composer require "codeception/module-cli" --dev
```
Make the Cli-Module availabel with your general YAML-Configuration or with the configuration for your tester like in this example:
```
actor: AcceptanceTester
modules:
    enabled:
        - Asserts
        - Cli
        - WebDriver:
  ...      
```
## Documentation

See [the module documentation](https://codeception.com/docs/modules/Cli).

[Changelog](https://github.com/Codeception/module-cli/releases)

## License

`Codeception Module CLI` is open-sourced software licensed under the [MIT](/LICENSE) License.

© Codeception PHP Testing Framework
