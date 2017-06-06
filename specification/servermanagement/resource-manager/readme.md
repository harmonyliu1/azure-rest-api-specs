# ServerManagement
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for ServerManagement.



---
## Getting Started 
To build the SDK for ServerManagement, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration for generating APIs


---
#### Basic Information 
These are the global settings for the ServerManagement API.

``` yaml
# common 
title: Server Management
description: Server Management Client
api-version: 2016-07-01-preview

```


# API Version: 2016-07-01-preview

These settings apply only when `--api-version=2016-07-01-preview` is specified on the command line.

``` yaml $(api-version) == '2016-07-01-preview'
input-file:
- Microsoft.ServerManagement/2016-07-01-preview/servermanagement.json

```
 
# API Version: 2015-07-01-preview

These settings apply only when `--api-version=2015-07-01-preview` is specified on the command line.

``` yaml $(api-version) == '2015-07-01-preview'
input-file:
- Microsoft.ServerManagement/2015-07-01-preview/servermanagement.json

```


---
#### Language-specific settings: CSharp

These settings apply only when `--csharp` is specified on the command line.

``` yaml $(csharp)
csharp:
  # override the default output folder
  output-folder: $(output-folder)/csharp
```
