# Proton structure at the LHC

This repository contains the source files for my PhD Thesis, submitted and defended in 2014. The source
should be straightforward to compile with `latexmk` and a reasonably modern
TeXLive distribution.

PDF versions of this thesis are available on the [arXiv](https://arxiv.org/abs/1411.0259)
and from the [Edinburgh Research Archive](https://www.era.lib.ed.ac.uk/handle/1842/9930).

## Abstract

A determination of Parton Distribution Functions (PDFs) from a global fit to a
dataset including measurements from the LHC has been performed for the first
time. The determinations have been performed according to the NNPDF methodology,
leading to a fit relatively free of parametrisation bias and with an accurate
account of PDF uncertainty.

In this thesis the importance of QCD measurements at the LHC to PDF extraction
are discussed, and we summarise some of the technical difficulties in their
inclusion into PDF fits. A number of methods are presented that permit the
efficient inclusion of these observables into PDF determinations.

Firstly a Bayesian reweighting procedure taking advantage of the Monte Carlo
representation of PDF uncertainties in NNPDF sets is discussed. The utility of
the Bayesian reweighting method is demonstrated by a study of the impact of
early *W*-boson production asymmetry measurements from ATLAS, CMS and LHCb upon an
earlier PDF set.

A package for the fast computation of observables in an automated NLO framework
is presented, providing an interface between Monte Carlo event generators and
NLO interpolation tools.

A new method of combining PDF evolution with interpolating codes for hadronic
observable computation is also described. This method largely overcomes the
computational difficulties in performing fast perturbative QCD predictions for
collider observables. The method has been applied to the determination of PDFs
from a global dataset including electroweak vector boson production data from
LHCb, ATLAS and CMS along with inclusive jet data from ATLAS. The resulting set,
NNPDF2.3 provides the most accurate determination of parton distributions via
the NNPDF methodology to date.

Finally, the method of closure testing is introduced, and the method is applied
to the study of the NNPDF methodology. A number of improvements are found in the
minimisation and stopping procedures, which are adopted for the development of
the next NNPDF release, NNPDF3.0. Alongside the improved methodology, the
NNPDF3.0 PDF set will provide a determination based upon an expanded dataset in
order to produce a comprehensive upgrade to the NNPDF2.3 family of fits.
