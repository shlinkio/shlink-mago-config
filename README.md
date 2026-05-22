# Shlink Mago config

Reusable shared [Mago](https://mago.carthage.software) configuration for Shlink PHP projects

## Usage

Install the package using composer

    composer require --dev shlinkio/shlink-mago-config

Update your `mago.toml` config to import this config

```toml
version = "1"
php-version = "8.4.0"

# Add this
extends = "vendor/shlinkio/shlink-mago-config/mago.toml"

[source]
workspace = "."
paths = [...]
```
