# kusion-api-go

## Overview

This repository stores the API definitions used by the core components of Kusion. 

## Purpose

This library is published separately to avoid circular dependency and diamond dependency problems for users who depend on more than one of `kusionstack.io/kusion`, `kusionstack.io/kusion-module-framework` and `kusionstack.io/catalog`, etc. 

## Where does this repo come from? 

`kusion-api-go` is synced from [](https://github.com/KusionStack/kusion/tree/main/pkg/apis). Code changes will be first made in `kusion` and later synced into this repository. The tag versions of `kusion-api-go` are compatible with `kusion` since `v0.13.0`. 

## Contributing

See [the contributing document](CONTRIBUTING.md).
