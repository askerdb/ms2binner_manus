---
title: 'MS2binner: A Python package for binning MS2 spectra'
tags:
  - Python
  - Mass spectrometry
  - Cheminformatics
authors:
 - name: Asker Brejnrod
   orcid: 0000-0002-1327-2051
   affiliation: 1
 - Arjun Sampath
   affiliation: 1
 - Pieter C. Dorrestein
   affiliation: 1
   orcid: 0000-0002-3003-1030
affiliations:
 - name: Skaggs School of Pharmacy, University of California, San Diego
   index: 1
date: 13 August 2017
bibliography: paper.bib
---

# Summary

Mass spectrometry has become a key technology for investigating the metabolome, the set of metabolites in a sample. Untargeted aquisition of metabolite signals has traditionally suffered from lack of ability to recognize molecules solely on their m/z value and retention time, and thus LC-MS/MS has become a valuable tool. For a set of aquired signals, the ions are fragmented and a new so-called MS2 spectra is aquired giving a fingerprint of the ion that is easier to identify. The development of in-silico tools to handle this data often require inputting a matrix of all MS2 spectra with the peaks binned to a lower dimensionality to alleviate noise. Standard open data formats in the field such as MGF, MzML and MzXML is supported..
MS2binner supports the development of machine learning based tools, by providing a user-friendly commandline tool and library that can bin the peaks, and apply standard noise filtration methods in the field. Additionally, it provides visualization capabilities that makes it quick to inspect the set of MS2 spectra.
The package is tested, documented and packaged for simple installation and use.

# Statement of need
Several tools in the field has developed their own capabilities to do peak binning. We are hoping that by providing this tool the community will have access to simple, reproducible means of generating input for modelling tasks

# Citations

# Figures

# Acknowledgements

The authors would like to acknowledge Wout Bittremioux and Chrissy Aceves for advice on feature sets.

# References