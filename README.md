# opam-setup-environment-list

This repository contains a list of opam setup environment allowing you to easily
setup your OCaml development environment.

## How to use?

[Opam](https://opam.ocaml.org) offers a simple way to import and export opam
setup environment. To import one of the configuration file listed below, use
```
opam switch import [configuration_file]
```

**It is recommended to switch to a fresh OCaml compiler for not conflict with
installed package. Use ```opam switch [compiler_version] to do it**

## List

* [eliom-base-app](https://raw.githubusercontent.com/dannywillems/opam-setup-environment-list/master/eliom-base-app). *Prerequisite:* libmagickcore-dev
