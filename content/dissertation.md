+++
date = "2018-02-17T00:00:00Z"
lastmod = "2018-02-18T00:00:00Z"
+++

Dissertation
============

> *Provisioning Computational Resources Using Virtual Machines and Leases*
  Borja Sotomayor, University of Chicago, August 2010
 
[Updated PDF](borja_sotomayor_dissertation_updated_20100825.pdf) (08/25/2010), with errata corrected

[Original PDF](borja_sotomayor_dissertation_original.pdf), as published
 
My dissertation deals, in a nutshell, with how to schedule virtual machines in a distributed system (such as a cluster) to support multiple resource provisioning scenarios (such as the combination of best-effort provisioning and advance reservations) simultaneously and efficiently. For more details, read the [abstract](http://people.cs.uchicago.edu/~borja/dissertation/abstract.txt) or Chapter 1 ("Introduction") of the dissertation. The introduction provides a high-level overview of the research questions I address in my doctoral work, and should (hopefully) be readable by any technical layperson.

Besides the PDF of my dissertation, in this page you will find a list of errata and all the data and scripts necessary to reproduce the results presented in my dissertation (the process to do this is described in Appendix A of the text). The open source project developed during my PhD, [Haizea](http://haizea.cs.uchicago.edu/), lives on a separate page.

If you have any questions on my dissertation, or are interested in addressing some of the future work described in it, please don't hesitate to [contact me]({{< relref "contact" >}}).

Experimental data
-----------------

The following are the files referenced in Appendix A of the dissertation:

- Scripts to reproduce simulated results
- Experimental data [257 MB]
- Scripts and data to reproduce non-simulated results [10.3 MB]

Errata
------

**Chapter 5 - Scheduling Disk Image Transfers**

*Page 100* - Figure 6.2. An older version of the figure was mistakenly used that was missing three data points (for the experiments with "small" nodes, "1h" leases, in configurations "VM-MULT", "VM-REUSE-UNIFORM", and "VM-REUSE-SKEWED"). Compare [original figure](figure-6.2_original.pdf) with [correct figure](figure-6.2_fixed.pdf).

**Appendix A - Reproducibility of Results**

*Page 154*. The last sentence in the page:

> The configuration files Annotation files are generated in the configs diractory:

Should read:

> The configuration files are generated in the configs/4pricing directory:

The list of files in the following page should show the files in the "configs/4pricing" directory, not in the "configs/" directory.

*Page 160*. The list of configuration files should show them in the "configs/4pricing" directory, not in the "configs/" directory.

*Page 162*. The following text still contains placeholders:

- data/1scheduling+2imagetransfer/: Should contain XXX files.
- data/3suspendresume/: Should contain XXX files.

It should read:

- data/1scheduling+2imagetransfer/: Should contain 450 files.
- data/3suspendresume/: Should contain 148 files.

*Page 176*. In the arguments to the run.py the run.local and run.global should be called torun.local and torun.global, respectively.





