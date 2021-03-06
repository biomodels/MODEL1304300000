# MODEL1304300000: MODEL1304300000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1304300000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1304300000.git@20140916`

## Usage

Importing the model package.

`import MODEL1304300000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Hofmeyr1996 - metabolic control analysis

Understanding of genetic mechanisms would not be possible by studying the
properties of individual components. To better understand the system as a
whole, it is necessary to study the interaction between components and their
response to each other. This paper describes a strategy for the experimental
control analysis called co-response analysis.

This model is described in the article:

[Co-response analysis: a new experimental strategy for metabolic control
analysis](http://identifiers.org/pubmed/8944170)

Hofmeyr JH, Cornish-Bowden A

Journal of Theoretical Biology [1996, 182(3):371-380]

Abstract:

The formulation of the standard summation and connectivity relationships as a
statement that the matrix of all the elasticities in a system is the inverse
of the matrix of all the control coefficients is completely general, provided
that only control coefficients for independent fluxes and concentrations are
considered, and that the elasticity matrix is written to take account of the
stoichiometry of the pathway and the implied dependences between
concentrations. This generally implies that co-response analysis is also
general, i.e. that all of the elasticities and all of the control coefficients
in any system, regardless of branching, feedback effects, moiety conservation
or other complications, can be determined by comparing the effects of
perturbations of the enzyme activities on the steady-state fluxes and
concentrations of the pathway. The approach requires no quantitative
information about the magnitudes of the effects on the individual enzyme
activities, and consequently no enzymes need to be studied in isolation from
the pathway.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1304300000](http://identifiers.org/biomodels.db/MODEL1304300000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


