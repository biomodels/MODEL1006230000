# MODEL1006230000: Smith2004_CVS_human

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230000.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Minimal haemodynamic system model including ventricular interaction and valve dynamics.**   
Smith BW, Chase JG, Nokes RI, Shaw GM, Wake G. _Med Eng Phys_ 2004
Mar;26(2):131-9 [15036180](http://www.ncbi.nlm.nih.gov/pubmed/15036180) ,  
**Abstract:**   
Characterising circulatory dysfunction and choosing a suitable treatment is
often difficult and time consuming, and can result in a deterioration in
patient condition, or unsuitable therapy choices. A stable minimal model of
the human cardiovascular system (CVS) is developed with the ultimate specific
aim of assisting medical staff for rapid, on site modelling to assist in
diagnosis and treatment. Models found in the literature simulate specific
areas of the CVS with limited direct usefulness to medical staff. Others model
the full CVS as a closed loop system, but they were found to be very complex,
difficult to solve, or unstable. This paper develops a model that uses a
minimal number of governing equations with the primary goal of accurately
capturing trends in the CVS dynamics in a simple, easily solved, robust model.
The model is shown to have long term stability and consistency with non-
specific initial conditions as a result. An "open on pressure close on flow"
valve law is created to capture the effects of inertia and the resulting
dynamics of blood flow through the cardiac valves. An accurate, stable
solution is performed using a method that varies the number of states in the
model depending on the specific phase of the cardiac cycle, better matching
the real physiological conditions. Examples of results include a 9% drop in
cardiac output when increasing the thoracic pressure from -4 to 0 mmHg, and an
increase in blood pressure from 120/80 to 165/130 mmHg when the systemic
resistance is doubled. These results show that the model adequately provides
appropriate magnitudes and trends that are in agreement with existing data for
a variety of physiologically verified test cases simulating human CVS
function.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Smith BW, Chase JG, Nokes RI, Shaw GM, Wake G.
(2004) - version=1.0**
](http://models.cellml.org/exposure/f629920d520a0ea9f51dbde8754470da)  
The original CellML model was created by:  
**Geoffrey Nunns**   
gnunns1@jhu.edu  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


