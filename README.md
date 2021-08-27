# loopback-framework-ci-status

## Test Report

| Repository Name | Test
|-|-
| loopback-next | [![Continuous Integration Status](https://github.com/loopbackio/loopback-next/actions/workflows/continuous-integration.yml/badge.svg)](https://github.com/loopbackio/loopback-next/actions/workflows/continuous-integration.yml) [![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/q8vp7wrdn2ak6801/branch/master?svg=true)](https://ci.appveyor.com/project/loopbackio/loopback-next/branch/master)
| loopback-connector-grpc | [![Build Status](https://app.travis-ci.com/loopbackio/loopback-connector-grpc.svg?branch=master)](https://app.travis-ci.com/loopbackio/loopback-connector-grpc)
| loopback-connector-kv-redis | [![Continuous Integration](https://github.com/loopbackio/loopback-connector-kv-redis/actions/workflows/continuous-integration.yaml/badge.svg)](https://github.com/loopbackio/loopback-connector-kv-redis/actions/workflows/continuous-integration.yaml)
| loopback-connector-mongodb | [![Continuous Integration (master branch)](https://github.com/loopbackio/loopback-connector-mongodb/actions/workflows/continuous-integration.yaml/badge.svg)](https://github.com/loopbackio/loopback-connector-mongodb/actions/workflows/continuous-integration.yaml)
| loopback-connector-mongodb (5.x branch) | [![Continuous Integration (5.x branch)](https://github.com/loopbackio/loopback-connector-mongodb/actions/workflows/continuous-integration.yaml/badge.svg?branch=5.x)](https://github.com/loopbackio/loopback-connector-mongodb/actions/workflows/continuous-integration.yaml)
| loopback-connector-mysql | [![Continous Integration](https://github.com/loopbackio/loopback-connector-mysql/actions/workflows/ci.yml/badge.svg)](https://github.com/loopbackio/loopback-connector-mysql/actions/workflows/ci.yml)
| loopback-connector-postgresql | [![Continuous Integration](https://github.com/loopbackio/loopback-connector-postgresql/actions/workflows/continuous-integration.yaml/badge.svg)](https://github.com/loopbackio/loopback-connector-postgresql/actions/workflows/continuous-integration.yaml)
| loopback-connector-rest | [![Continuous Integration](https://github.com/loopbackio/loopback-connector-rest/actions/workflows/continuous-integration.yaml/badge.svg)](https://github.com/loopbackio/loopback-connector-rest/actions/workflows/continuous-integration.yaml)
| loopback-connector-soap | [![CI](https://github.com/loopbackio/strong-soap/actions/workflows/continuous-integration.yaml/badge.svg)](https://github.com/loopbackio/strong-soap/actions/workflows/continuous-integration.yaml) [![Build Status](https://app.travis-ci.com/loopbackio/strong-soap.svg?branch=master)](https://app.travis-ci.com/loopbackio/strong-soap)
| strong-soap | [![CI](https://github.com/loopbackio/strong-soap/actions/workflows/continuous-integration.yaml/badge.svg)](https://github.com/loopbackio/strong-soap/actions/workflows/continuous-integration.yaml) [![Build Status](https://app.travis-ci.com/loopbackio/strong-soap.svg?branch=master)](https://app.travis-ci.com/loopbackio/strong-soap)

## Coverage Report

| Repository Name | Coverage
|-|-
| loopback-next | [![Coverage Status](https://coveralls.io/repos/github/loopbackio/loopback-next/badge.svg)](https://coveralls.io/github/loopbackio/loopback-next)
| loopback-connector-soap | [![Coverage Status](https://coveralls.io/repos/github/loopbackio/loopback-connector-soap/badge.svg)](https://coveralls.io/github/loopbackio/loopback-connector-soap)
| strong-soap | [![Coverage Status](https://coveralls.io/repos/github/loopbackio/strong-soap/badge.svg)](https://coveralls.io/github/loopbackio/strong-soap)

## Testing Environment

| Repository Name | Windows x86-64 | macOS x86-64 | Linux x86-64 | Linux Aarch64 | Linux ppc64le | Linux s390x
|-|-|-|-|-|-|-
| loopback-next | 14 | 14 | 10,12,14,16 | - | - | -
| loopback-connector-cassandra | - | - | 8,10,12 | - | - | -
| loopback-connector-cloudant | - | - | 12,14,16 | - | - | -
| loopback-connector-couchdb2 | - | - | - | - | - | -
| loopback-connector-db2 | - | - | - | - | - | -
| loopback-connector-dashdb | - | - | - | - | - | -
| loopback-connector-elastic-search | - | - | - | - | - | -
| loopback-connector-grpc | - | - | 10,12,14 | - | - | -
| loopback-connector-ibmdb | - | - | - | - | - | -
| loopback-connector-ibmi | - | - | - | - | - | -
| loopback-connector-kv-extreme-scale | - | - | - | - | - | -
| loopback-connector-kv-redis | - | - | 10,12,14 | - | - | -
| loopback-connector-mongodb | - | - | 10,12,14 | - | - | -
| loopback-connector-mongodb (5.x branch) | - | - | 10,12,14 | - | - | -
| loopback-connector-mssql | - | - | - | - | - | -
| loopback-connector-mysql | - | - | 12,14,16 | - | - | -
| loopback-connector-openapi | - | - | 10,12,14 | - | - | -
| loopback-connector-oracle | - | - | - | - | - | -
| loopback-connector-postgresql | - | - | 12,14,16 | - | - | -
| loopback-connector-redis | - | - | - | - | - | -
| loopback-connector-rest | - | - | 12,14,16 | - | - | -
| loopback-connector-soap | - | - | 10,12,14 | - | - | -
| loopback-connector-sqlite3 | - | - | - | - | - | -
| loopback-datasource-juggler | - | - | - | - | - | -
| strong-soap | 14 | 14 | 10,12,14,16 | 10,12,14,16 | 10,12,14,16 | 10,12,14,16

## Testing Environment CI provider

| Environment Name | CI Provider
|-|-
| Windows x86-64 (loopback-next) | AppVeyor
| Windows x86-64 | GitHub Actions
| macOS x86-64 | GitHub Actions
| Linux x86-64 (loopback-connector-cassandra/cloudant/grpc/openapi) | Travis CI
| Linux x86-64 | GitHub Actions
| Linux Aarch64 | Travis CI
| Linux Aarch64 | Travis CI
| Linux ppc64le | Travis CI
| Linux s390x | Travis CI

## Notes

### Coverage Reports

Due to limitations of publishing coverage from builds across multiple CI providers, only coverage from tests executed within GitHub Actions are published.
