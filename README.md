
Blue P.E.A.R (in progress)
====
Packet-capture, Enrichment, Analysis, and Reporting
---
<p align="center" style="width:400px"><img src="https://github.com/Sean-Donnelly/blue-pear/blob/master/bluepear-diagram.PNG" style="width:400px"></p>

---
Blue P.E.A.R is a network security monitoring (NSM) toolset for use by a deploying blue team.  It is similar to other NSM platforms (ROCK NSM, CozyNSM, Security Onion, etc.) but differs in the following ways:
* emphasis on deeper and more efficient analysis of full packet capture
* designed to be a one-person deployment (personnel constrained teams); the toolset lacks access control and collaboration tools
* built to operate on a hardware constrained network (minimal deployed assets)
* incorporates logstash configs developed by Justin Henderson (H&A Security Solutions) and myself for data enrichment
* takes advantage of various open-source analytic frameworks (by Austin Taylor and Mark Baggett)
* employs up-to-date versions of Elastic applications
* includes training aids (workflows and hunt matrix templates) 

