# Social Collaboration Apis
This repository contains OpenAPI specifications for collaboration services including
user management, task management and messaging.

## Repository structure
* [api](api) - APIs declarations
* _bin_ - scripts for APIs generation and mocks building
* [generators](generators) - custom API clients/stubs generators
* [server-mocks](server-mocks) - APIs server mocks and blackbox tests
* [docs](docs) - generated APIs documentation

## Requirements
In order to build artifacts and run mock server you'll need:
* Maven 3
* JDK 8
* Bash 4
* Git

## Cloning repository

git clone https://github.com/black32167/social_api.git

## Building artifacts
    # List all build options available:
    <social_api>$ ./bin/build.sh
    
    # Build all:
    <social_api>$ ./bin/build.sh all
    
    # Generate APIs artifacts only:
    <social_api>$ ./bin/build.sh apis
    
    # Builds mock API server:
    <social_api>$ ./bin/build.sh mock-server
    
## Run mock server
    <social_api>$ ./bin/run.sh