# Gammapy - present status and future roadmap

## Authors: A. Sinha, R. Terrier, A. Donath, B. Khelifi, Q. Remy .... for the gammapy dev team

Since the first release of Gammapy v0.1 in 2014, 
this light-weight open source python library has come a long way to 
become a popular data analysis package for high energy astrophysics. 
Selected as the official CTA Science Analysis tool, it is also an
approved analysis s/w within the H.E.S.S. and MAGIC collaborations. 
The first long-term version, Gammapy v1.0 was released last year. 
It is compliant with several well-established data conventions in 
high-energy astrophysics, and provides serialised data products that
are interoperable with other softwares. Event lists and instrument 
response functions at the common "DL3" format from various instruments
can be reduced to data binned in energy, time or spatial coordinates. 
Thereafter, the flux and morphology of one or more 
γ-ray sources can be estimated using Poisson maximum 
likelihood fitting and assuming a variety of spectral, 
temporal and spatial models. Flux points, 
likelihood profiles and light curves extractions are supported. 
Complex user defined likelihoods and models can also be implemented.

In this contribution we will highlight the main features of Gammapy v1.0,
including data reduction and analysis examples from different space 
and ground based instruments, applications of various background 
rejection techniques, and a simultaneous fitting across multiple
instruments with astrophysical models. 
We will also present our plans for the future, with new features 
like support for different event types, unbinned likelihood analysis,
spectral unfolding and transient source detections, an
improved API with distributed computing for scalable analysis, 
and enhanced support for all sky instruments like Fermi-LAT and HAWC.