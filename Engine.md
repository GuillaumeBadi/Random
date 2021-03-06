MJML Engine
===========

The `mjml-engine` is the core of the MJML renderer. It exposes the MJML parser and the MJML-to-HTML transpiler.

## How it works

<p align="center"><a href="#" target="_blank"><img width="600"src="https://cloud.githubusercontent.com/assets/6558790/12552666/72297fbc-c373-11e5-981b-62217a960c0f.png"></a></p>

The engine is composed of multiple parts:

### [`documentParser`](#)

Parse the markup MJML string and return a JSON representation

### [`mjml2html`](#)

Turn a JSON MJML representation and returns an HTML string using react components

### [`MJMLElementsCollection`](#)

Contains the standard MJML elements exposed to the API

## Changelog
Please refer to the [release](#) section to get more details about the diferent improvements

## Issues

Please make sure to check the closed issue and to tag your issues with the `engine`  tag
