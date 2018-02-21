---
layout: ontology_detail
id: reno
title: RENOVATE
jobs:
  - id: https://travis-ci.org/xxxgao/renovate
    type: travis-ci
build:
  checkout: git clone https://github.com/xxxgao/renovate.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: RENOVATE is an ontology...
domain: stuff
homepage: https://github.com/xxxgao/renovate
products:
  - id: reno.owl
  - id: reno.obo
dependencies:
 - id: po
 - id: ro
 - id: pato
tracker: https://github.com/xxxgao/renovate/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
