---
layout: ontology_detail
id: ms
label: Mass spectrometry ontology
title: Mass spectrometry ontology
contact:
  email: gerhard.mayer@rub.de
  label: Gerhard Mayer
description: A structured controlled vocabulary for the annotation of experiments concerned with proteomics mass spectrometry.
integration_server: https://raw.githubusercontent.com/MICommunity/psidev/master/psi/psi-ms/mzML/controlledVocabulary/
domain: MS experiments
mailing_list: psidev-ms-vocab@lists.sourceforge.net
homepage: http://www.psidev.info/groups/controlled-vocabularies
page: http://www.psidev.info/groups/controlled-vocabularies
dependencies:
 - id: pato
 - id: uo
products:
  - id: ms.obo
  - id: ms.owl
build:
  source_url: https://raw.githubusercontent.com/MICommunity/psidev/master/psi/psi-ms/mzML/controlledVocabulary/psi-ms.obo
  method: obo2owl
---

A structured controlled vocabulary for the annotation of experiments concerned with proteomics mass spectrometry. Developed by the HUPO Proteomics Standards Initiative (PSI).
