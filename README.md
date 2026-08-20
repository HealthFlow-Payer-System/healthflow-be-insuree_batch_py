# HealthFlow Backend Insuree Batch module

> **HealthFlow Payer System — Egypt context**
>
> This repository is maintained under [HealthFlow Payer System](https://github.com/HealthFlow-Payer-System), an Egypt-focused health-insurance platform built on openIMIS foundations. Egypt-specific localization is applied at the assembly and module boundaries; consult the repository-specific configuration and deployment documentation for the capabilities enabled here.

This repository holds the files of the openIMIS Backend Insuree Batch
module. It is dedicated to be deployed as a module of
[openimis-be_py](https://github.com/openimis/openimis-be_py). Its
purpose is to generate insuree numbers in bulk and then generate ZIP
extracts of the insurees created for card printing.

[![License: AGPL v3](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

## Code climat (develop branch)

## ORM mapping:
TBC

## Listened Django Signals
None

## Services
TBC

## GraphQL Queries
TBC

## GraphQL Mutations - each mutation emits default signals and return standard error lists (cfr. openimis-be-core_py)
TBC

## Additional Endpoints
TBC

## Configuration options (can be changed via core.ModuleConfiguration)
TBC

## openIMIS Modules Dependencies
* location.models.Location
* Insuree.models.Insuree and InsureePhoto
