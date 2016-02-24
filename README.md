# springer-paper-template

[![Build Status](https://travis-ci.org/furushchev/springer-paper-template.svg)](https://travis-ci.org/furushchev/springer-paper-template)

### Prerequisities

```bash
# only for ubuntu 12.04
$ sudo apt-add-repository ppa:texlive-backports/ppa
$ sudo apt-get update
```

### How to use

1. edit latex files
2. compile

  ```bash
  make
```

### Enable auto pdf generation

- Install [Travis Command Line Tool](https://github.com/travis-ci/travis.rb#installation)
- Enable Travis

  ```bash
  travis enable
  travis setup releases --force
```

- Push your tag by `git push --tag`. Then you can watch pdf in github releases.

### Clean

```bash
$ make clean
# or
$ make wipe
```
