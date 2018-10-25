---
id: installation
title: "Installation"
---
Verdaccio est une application Web multi-plateforme. Quelques conditions préalables sont requises pour son installation.

#### Conditions préalables

1. Nœud supérieur à 
    - Pour la version `verdaccio@2.x` Noeud `v4.6.1` est la version minimale prise en charge.
    - Pour la version `verdaccio@latest` Noeud `6.12.0` est la version minimale prise en charge.
2. npm `>=3.x` ou `yarn`
3. L'interface web prend en charge les navigateurs `Chrome, Firefox, Edge, et IE9`.

## Installing the CLI

`verdaccio` must be installed globaly using either of the following methods:

Using `npm`

```bash
npm install -g verdaccio
```

or using `yarn`

```bash
yarn global add verdaccio
```

![install verdaccio](/svg/install_verdaccio.gif)

## Basic Usage

Once it has been installed, you only need to execute the CLI command:

```bash
$> verdaccio
warn --- config file  - /home/.config/verdaccio/config.yaml
warn --- http address - http://localhost:4873/ - verdaccio/3.0.1
```

For more information about the CLI, please [read the cli section](cli.md).

## Docker Image

`verdaccio` has an official docker image you can use, and in most cases, the default configuration is good enough. For more information about how to install the official image, [read the docker section](docker.md).

## Cloudron

`verdaccio` is also available as a 1-click install on [Cloudron](https://cloudron.io)

[![Install](https://cloudron.io/img/button.svg)](https://cloudron.io/button.html?app=org.eggertsson.verdaccio)