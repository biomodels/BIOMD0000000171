# BIOMD0000000171: model_0000001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000171.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000171.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000171 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


# Leloup and Goldbeter, 1998

This model was created after the article by Leloup and Goldbeter, _J Biol
Rhythms_ 1998, Vol:13(1),pp70-87, pubmedID: 9486845  
A Model for Circadian Rhythms in _Drosophila_ Incorporating the Formation of a
Complex between the PER and TIM Proteins  
The parameters and initial concentrations are taken to reproduce figs. 4 D,E,F
in the publication.  
For a simulation without light dependent degradation of TIM_pp, change the the
parameter _v_dT_fac_ to 1.  
The light/dark phases length can be set using the parameter _l_d_ .

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


