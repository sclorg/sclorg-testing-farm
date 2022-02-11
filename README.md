# FMF testing plans for usage in the Testing Farm service

This repository contains testing plans, which are used by the [sclorg's](https://github.com/sclorg/) testing GitHub Actions running on Testing Farm infrastructure.

Available testing plans:

| testing plan            | description               |
|  --------------         |------------               |
| `betka-bot.fmf`         | Runs betka tests on Fedora|
| `betka-fedmsg.fmf`      | Runs betka-fedmsg tests on Fedora      |
| `c9s.fmf`               | Runs docker tests on CentOS Stream 9   |
| `fedora.fmf`            | WIP (Work In Progress)    |
| `centos7.fmf`           | Runs docker or OpenShift 3 tests on CentOS 7|
| `container-ci-suite.fmf`| Runs container-ci-suite tests on Fedora|
| `cwt.fmf`               | Runs cwt tests on Fedora  |
