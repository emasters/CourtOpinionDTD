CourtOpinionDTD
===============

Some very early work on a DTD for court opinions. This DTD was developed in 1999-2000 to markup the opinions issued 
by the US Circuit Court of Appeals. Work was done with an eye toward generalized use to mark up any court opinions. Though some testing was carried out with opinions from the 11th circuit, AFAIK the DTD was never implemented by any court. I am providing it now for the curious and because I still hear from people who are interested in marking up court opinions.

---

## Files
*CourtOpinion.dtd* is the original DTD that was developed for marking up court opinions. It was put together using a package called Near & Far Designer. For many years only this DTD existed.

*CourtOpinion.rng* is an intermediary RELAX NG file that I generated from the DTD using [dtdinst](http://www.thaiopensource.com/dtdinst/) so that I could generate the W3C XML Schema file.

*CourtOpinion.xsd* is an W3C XML Schema file that I generated from the RELAX NG file using [Trang](http://www.thaiopensource.com/relaxng/trang-manual.html). 

---

All of this code is provided as is. This is a personal project and it is not endorsed or supported by my employer.





