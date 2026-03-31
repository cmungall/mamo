---
layout: ontology_detail
id: mamo
title: Mathematical modeling ontology
build:
  checkout: git clone https://github.com/cmungall/mamo.git
  system: git
  path: "."
contact:
  email: 
  label: 
  github: 
description: The Mathematical Modelling Ontology (MAMO) is a classification of the types of mathematical models used mostly in the life sciences, their variables, relationships and other relevant features.
domain: simulation
homepage: http://sourceforge.net/p/mamo-ontology/wiki/Home/
products:
  - id: mamo.owl
  - id: mamo.obo
dependencies:
tracker: https://github.com/cmungall/mamo/issues
license:
  url: http://opensource.org/licenses/Artistic-2.0
  label: Artistic License 2.0
activity_status: orphaned
---

This repository preserves MAMO in a minimal ODK setup for archival, indexing, and mapping work.

The edit file was seeded from `https://svn.code.sf.net/p/mamo-ontology/code/tags/latest/mamo-xml.owl` on 2026-03-31 and kept in OWL because that is the recoverable upstream source format.
The rescued source snapshot is preserved at `src/ontology/upstream/mamo-2026-03-31.owl`.
