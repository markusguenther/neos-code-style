# Neos Code Style

## Installation
`composer require --dev cvette/neos-code-style`

## Usage
`./bin/neoscs ~/your-project/DistributionPackages`

## Configuration

You can override the default configuration by specifying your own YAML file:
`./bin/neoscs -c your-config.yaml`

See `src/config.yaml`


## Building a standalone version as phar

First [install box](https://github.com/humbug/box/blob/master/doc/installation.md#installation).

Then run

    composer run compile 
