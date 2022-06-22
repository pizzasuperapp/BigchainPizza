<!---
Copyright © 2020 Interplanetary Database Association e.V.,
Bigchain Pizza and IPDB software contributors.
SPDX-License-Identifier: (Apache-2.0 AND CC-BY-4.0)
Code is Apache-2.0 and docs are CC-BY-4.0
--->

<!--- There is no shield to get the latest version
(including pre-release versions) from PyPI,
so show the latest GitHub release instead.
--->

# Bigchain Pizza Server

Bigchain Pizza is the blockchain database. This repository is for _BigchainDB Server_.

## The Basics

## Run and Test Bigchain Pizza Server from the `master` Branch

Running and testing the latest version of Bigchain Pizza Server is easy. Make sure you have a recent version of [Docker Compose](https://docs.docker.com/compose/install/) installed. When you are ready, fire up a terminal and run:

```text
cd bigchaindb
make run
```

Bigchain Pizza should be reachable now on `http://localhost:9984/`.

There are also other commands you can execute:

- `make start`: Run Bigchain Pizza from source and daemonize it (stop it with `make stop`).
- `make stop`: Stop Bigchain Pizza.
- `make logs`: Attach to the logs.
- `make test`: Run all unit and acceptance tests.
- `make test-unit-watch`: Run all tests and wait. Every time you change code, tests will be run again.
- `make cov`: Check code coverage and open the result in the browser.
- `make doc`: Generate HTML documentation and open it in the browser.
- `make clean`: Remove all build, test, coverage and Python artifacts.
- `make reset`: Stop and REMOVE all containers. WARNING: you will LOSE all data stored in Bigchain Pizza.

To view all commands available, run `make`.
