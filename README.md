# BIOMD0000000407: Schliemann2011_TNF_ProAntiApoptosis

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000407.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000407.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000407 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**Heterogeneity Reduces Sensitivity of Cell Death for TNF-Stimuli**   
Schliemann M, Bullinger E, Borchers S, Allgower F, Findeisen R, Scheurich P.
_BMC Syst Biol._ 2011 Dec 28;5(1):204.
[22204418](http://www.ncbi.nlm.nih.gov/pubmed/22204418) ,  
**Abstract:**   
BACKGROUND: Apoptosis is a form of programmed cell death essential for the
maintenance of homeostasis and the removal of potentially damaged cells in
multicellular organisms. By binding its cognate membrane receptor, TNF
receptor type 1 (TNF-R1), the proinflammatory cytokine Tumor Necrosis Factor
(TNF) activates pro-apoptotic signaling via caspase activation, but at the
same time also stimulates nuclear factor kappaB (NF-kappaB)-mediated survival
pathways. Differential dose-response relationships of these two major TNF
signaling pathways have been described experimentally and using mathematical
modeling. However, the quantitative analysis of the complex interplay between
pro- and anti-apoptotic signaling pathways is an open question as it is
challenging for several reasons: the overall signaling network is complex,
various time scales are present, and cells respond quantitatively and
qualitatively in a heterogeneous manner. RESULTS: This study analyzes the
complex interplay of the crosstalk of TNF-R1 induced pro- and anti-apoptotic
signaling pathways based on an experimentally validated mathematical model.
The mathematical model describes the temporal responses on both the single
cell level as well as the level of a heterogeneous cell population, as
observed in the respective quantitative experiments using TNF-R1 stimuli of
different strengths and durations. Global sensitivity of the heterogeneous
population was quantified by measuring the average gradient of time of death
versus each population parameter. This global sensitivity analysis uncovers
the concentrations of Caspase-8 and Caspase-3, and their respective inhibitors
BAR and XIAP, as key elements for deciding the cell's fate. A simulated
knockout of the NF-kappaB-mediated anti-apoptotic signaling reveals the
importance of this pathway for delaying the time of death, reducing the death
rate in the case of pulse stimulation and significantly increasing cell-to-
cell variability. CONCLUSIONS: Cell ensemble modeling of a heterogeneous cell
population including a global sensitivity analysis presented here allowed us
to illuminate the role of the different elements and parameters on apoptotic
signaling. The receptors serve to transmit the external stimulus; procaspases
and their inhibitors control the switching from life to death, while NF-kappaB
enhances the heterogeneity of the cell population. The global sensitivity
analysis of the cell population model further revealed an unexpected impact of
heterogeneity, i.e. the reduction of parametric sensitivity.

**Note:** SBML model generated from Matlab system description on 12-July-2011 21:08:15 by exportSBML Copyright Eric Bullinger 2007-2011 


