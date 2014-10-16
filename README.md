# BIOMD0000000283: chance

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000283.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000283.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000283 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Default parameter values are those in the right hand panel of Fig 12. The
other panels may be obtained by setting X to 1, 2 or 4, and K3 to 0, 1/2 or 1.

This model is described in:  
**The kinetics of the enzyme-substrate compound of peroxidase.**   
Britton Chance, _Journal of Biological Chemistry_, 151, 553-577, 1943. [PDF at
JBC](http://www.jbc.org/content/151/2/553)  
reprinted in: _Adv Enzymol Relat Areas Mol Biol._ 1999;73:3-23.
PubmedID:[10218104](http://www.ncbi.nlm.nih.gov/pubmed/10218104)>  
Abstract:  
Under the narrow range of experimental conditions, and at a temperature of
approximately 25 degrees, the following data were obtained. 1. The equilibrium
constant of peroxidase and hydrogen peroxide has a minimum value of 2 x
10(-8). 2. The velocity constant for the formation of peroxidase-H2O2 Complex
I is 1.2 x 10(7) liter mole-1 sec.-1, +/- 0.4 x 10(7). 3. The velocity
constant for the reversible breakdown of peroxidase-H2O2 Complex I is a
negligible factor in the enzyme-substrate kinetics and is calculated to be
less than 0.2 sec.-1. 4. The velocity constant, k3, for the enzymatic
breakdown of peroxidase-H2O2 Complex I varies from nearly zero to higher than
5 sec.-1, depending upon the acceptor and its concentration. The quotient of
k3 and the leucomalachite green concentration is 3.0 x 10(4) liter mole-1
sec.-1. For ascorbic acid this has a value of 1.8 x 10(5) liter mole-1 sec.-1.
5. For a particular acceptor concentration, k3 is determined solely from the
enzyme-substrate kinetics and is found to be 4.2 sec.-1. 6. For the same
conditions, k3 is determined from a simple relationship derived from
mathematical solutions of the Michaelis theory and is found to be 5.2 sec.-1.
7. For the same conditions, k3 is determined from the over-all enzyme action
and is found to be 5.1 sec.-1. 8. The Michaelis constant determined from
kinetic data alone is found to be 0.44 x 10(-6). 9. The Michaelis constant
determined from steady state measurements is found to be 0.41 x 10(-6). 10.
The Michaelis constant determined from measurement of the overall enzyme
reaction is found to be 0.50 x 10(-6). 11. The kinetics of the enzyme-
substrate compound closely agree with mathematical solutions of an extension
of the Michaelis theory obtained for experimental values of concentrations and
reaction velocity constants. 12. The adequacy of the criteria by which
experiment and theory were correlated has been examined critically and the
mathematical solutions have been found to be sensitive to variations in the
experimental conditions. 13. The critical features of the enzyme-substrate
kinetics are Pmax, and curve shape, rather than t1/2. t1/2 serves as a simple
measure of dx/dt. 14. A second order combination of enzyme and substrate to
form the enzyme-substrate compound, followed by a first order breakdown of the
compound, describes the activity of peroxidase for a particular acceptor
concentration. 15. The kinetic data indicate a bimolecular combination of
acceptor and enzyme-substrate compound.

This model is the one described in the appendix of the article. It reproduces,
amongst others, figure 12. The parameters and concentrations used are rescaled
as stated in the article. K2 and K3 stand for k2 and k3, respectively, divided
by k1.


