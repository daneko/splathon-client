# openapi
Splathonで使うAPI

This Dart package is automatically generated by the [OpenAPI Generator](https://openapi-generator.tech) project:

- API version: 1.0.0
- Build package: org.openapitools.codegen.languages.DartClientCodegen

## Requirements

Dart 1.20.0 or later OR Flutter 0.0.20 or later

## Installation & Usage

### Github
If this Dart package is published to Github, please include the following in pubspec.yaml
```
name: openapi
version: 1.0.0
description: OpenAPI API client
dependencies:
  openapi:
    git: https://github.com/GIT_USER_ID/GIT_REPO_ID.git
      version: 'any'
```

### Local
To use the package in your local drive, please include the following in pubspec.yaml
```
dependencies:
  openapi:
    path: /path/to/openapi
```

## Tests

TODO

## Getting Started

Please follow the [installation procedure](#installation--usage) and then run the following:

```dart
import 'package:openapi/api.dart';


var api_instance = new Sample1Api();
var id = 8.14; // num | user id

try {
    var result = api_instance.getUserById(id);
    print(result);
} catch (e) {
    print("Exception when calling Sample1Api->getUserById: $e\n");
}

```

## Documentation for API Endpoints

All URIs are relative to *https://localhost/splathon/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*Sample1Api* | [**getUserById**](docs//Sample1Api.md#getuserbyid) | **GET** /user/{id} | 


## Documentation For Models

 - [SampleObj](docs//SampleObj.md)


## Documentation For Authorization

 All endpoints do not require authorization.


## Author



