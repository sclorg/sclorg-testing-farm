# FMF testing plans for usage in the Testing Farm service

This repository contains testing plans, which are used by the [sclorg's](https://github.com/sclorg/) testing GitHub Actions running on Testing Farm infrastructure.

Available testing plans:

| testing plan                             | description                              |
|------------------------------------------|------------------------------------------|
| `betka-bot.fmf`                          | Runs betka tests on Fedora               |
| `betka-fedmsg.fmf`                       | Runs betka-fedmsg tests on Fedora        |
| `c9s.fmf`                                | Runs container tests on CentOS Stream 9  |
| `c10s.fmf`                               | Runs container tests on CentOS Stream 10 |
| `fedora.fmf`                             | Runs container tests on Fedora           |
| `container-ci-suite`                     | Runs container-ci-suite tests on Fedora  |
| `container-ci-suite.fmf`                 | Runs container-ci-suite tests on Fedora  |
| `cwt.fmf`                                | Runs cwt tests on Fedora                 |
| `gpu-fedora`                             | Runs tests on Fedora with NVidia GPUs    |
| `nightly-container-centos-stream-10.fmf` | Nightly build tests on CentOS Stream 10  |
| `nightly-container-centos-stream-9.fmf`  | Nightly build tests on CentOS Stream 9   |
| `nightly-container-f.fmf`                | Nightly build tests on Fedora            |
