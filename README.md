# gpr-url

[![github release](https://img.shields.io/github/v/release/flex-development/gpr-url-action.svg?include_prereleases\&sort=semver)](https://github.com/flex-development/gpr-url-action/releases/latest)
[![test](https://github.com/flex-development/gpr-url-action/actions/workflows/test.yml/badge.svg)](https://github.com/flex-development/gpr-url-action/actions/workflows/test.yml)
[![module type: esm](https://img.shields.io/badge/module%20type-esm-brightgreen)](https://github.com/voxpelli/badges-cjs-esm)
[![license](https://img.shields.io/github/license/flex-development/gpr-url-action.svg)](LICENSE.md)
[![conventional commits](https://img.shields.io/badge/-conventional%20commits-fe5196?logo=conventional-commits\&logoColor=ffffff)](https://conventionalcommits.org)
[![yarn](https://img.shields.io/badge/-yarn-2c8ebb?style=flat\&logo=yarn\&logoColor=ffffff)](https://yarnpkg.com)

Get a GitHub Package Registry URL

## Contents

- [What is this?](#what-is-this)
- [Use](#use)
- [Inputs](#inputs)
  - [`pkg`](#pkg)
  - [`repo`](#repo)
  - [`server`](#server)
- [Outputs](#outputs)
  - [`url`](#url)
- [Contribute](#contribute)

## What is this?

This is a simple action for creating a GitHub Package Registry (GPR) URL.

## Use

**TODO**: use

## Inputs

### `pkg`

> **default**: `${{ github.event.repository.name }}`

The name of the package.

### `repo`

> **default**: `${{ github.repository }}`

The name of the repository, including the owner.

### `server`

> **default**: `${{ github.server_url }}`

The URL of the GitHub server.

## Outputs

### `url`

The package URL.

## Contribute

See [`CONTRIBUTING.md`](CONTRIBUTING.md).

This project has a [code of conduct](./CODE_OF_CONDUCT.md). By interacting with this repository, organization, or
community you agree to abide by its terms.
