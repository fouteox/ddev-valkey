[![tests](https://github.com/ddev/ddev-valkey/actions/workflows/tests.yml/badge.svg)](https://github.com/ddev/ddev-valkey/actions/workflows/tests.yml) ![project is maintained](https://img.shields.io/maintenance/yes/2025.svg)

# DDEV add-on template <!-- omit in toc -->

* [Introduction](#introduction)
* [Installation](#installation)

## Introduction

This repository allows you to quickly install Valkey into a [DDEV](https://ddev.readthedocs.io) project using the instructions below.

## Installation

For DDEV v1.23.5 or above run

```sh
ddev add-on get fouteox/ddev-valkey
```

Then restart your project

```sh
ddev restart
```

## Explanation

This Valkey recipe for [DDEV](https://ddev.readthedocs.io) installs a [`.ddev/docker-compose.valkey.yaml`](docker-compose.valkey.yaml) using the `valkey` Docker image.

## Interacting with Valkey

* To reach the Valkey CLI interface, run `ddev valkey-cli` to begin a session. You can also run Valkey CLI commands directly on the command-line, e.g., `ddev valkey-cli INFO`.

**Contributed and maintained by [fouteox](https://github.com/fouteox)**
