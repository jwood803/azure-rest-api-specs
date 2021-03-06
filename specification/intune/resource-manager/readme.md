# Intune
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Intune.



---
## Getting Started 
To build the SDK for Intune, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information 
These are the global settings for the Intune API.

``` yaml
openapi-type: arm
tag: package-2015-01-preview
```


### Tag: package-2015-01-preview

These settings apply only when `--tag=package-2015-01-preview` is specified on the command line.

``` yaml $(tag) == 'package-2015-01-preview'
input-file:
- Microsoft.Intune/preview/2015-01-14-preview/intune.json
```
 
### Tag: package-2015-01-privatepreview

These settings apply only when `--tag=package-2015-01-privatepreview` is specified on the command line.

``` yaml $(tag) == 'package-2015-01-privatepreview'
input-file:
- Microsoft.Intune/preview/2015-01-14-privatepreview/intune.json
```

---
# Code Generation


## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-go
```


## C# 

These settings apply only when `--csharp` is specified on the command line.
Please also specify `--csharp-sdks-folder=<path to "SDKs" directory of your azure-sdk-for-net clone>`.

``` yaml $(csharp)
csharp:
  azure-arm: true
  license-header: MICROSOFT_MIT_NO_VERSION
  namespace: Microsoft.Azure.Management.Intune
  output-folder: $(csharp-sdks-folder)/Intune/Intune/Generated
  clear-output-folder: true
```


## Go

These settings apply only when `--go` is specified on the command line.

``` yaml $(go)
go:
  license-header: MICROSOFT_APACHE_NO_VERSION
  namespace: intune
  clear-output-folder: true
```

### Go multi-api

``` yaml $(go) && $(multiapi)
batch:
  - tag: package-2015-01-preview
```

### Tag: package-2015-01-preview and go

These settings apply only when `--tag=package-2015-01-preview --go` is specified on the command line.
Please also specify `--go-sdk-folder=<path to the root directory of your azure-sdk-for-go clone>`.

``` yaml $(tag) == 'package-2015-01-preview' && $(go)
output-folder: $(go-sdk-folder)/services/intune/mgmt/2015-01-14-preview/intune
```


## Java

These settings apply only when `--java` is specified on the command line.
Please also specify `--azure-libraries-for-java-folder=<path to the root directory of your azure-libraries-for-java clone>`.

``` yaml $(java)
java:
  azure-arm: true
  fluent: true
  namespace: com.microsoft.azure.management.intune
  license-header: MICROSOFT_MIT_NO_CODEGEN
  payload-flattening-threshold: 1
  output-folder: $(azure-libraries-for-java-folder)/azure-mgmt-intune
```
