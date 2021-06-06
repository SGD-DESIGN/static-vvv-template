# VVV Static site template

A static site in VVV

## Overview

I like having the option to create an empty static site for small projects that don't require php or a CMS like WordPress. This is based on the original Static-VVV Repo from https://github.com/lacqui

Original configuration is as follows:

- PHP is disabled
- Index is set to 'index.html'
- Autoindex is enabled (directory will be shown)
- Hidden files are shown

## All the configuration you need:

```yaml
my-site:
  repo: https://github.com/sgd-design/static-vvv-template
  hosts:
    - my-site.test
```

## Configuration Options

```yaml
hosts:
  - foo.test
```

Defines the domain and host for VVV to listen on.
