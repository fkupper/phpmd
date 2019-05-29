# Custom PHPMD rulesets

This project contains a ruleset to be used with phpmd https://github.com/phpmd/phpmd

## Installation

```bash
$ composer global require fkupper/phpmd
```

## Rules
- All phpmd rules
- Excluded static usage of classes due to laravel facades among others
- Excluded some short variable names such as `$to` in a mailable or `$I` in codeception
