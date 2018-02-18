+++
date = "2018-02-17T00:00:00Z"
lastmod = "2018-02-18T00:00:00Z"
+++

Research
========

I am not actively involved in research at the moment, but my research interests have mostly revolved around virtual machine-based resource provisioning models (where "resource" includes hardware, software, and time) using a leasing abstraction. Most of my research work was relevant to Infrastructure-as-a-Service (IaaS) cloud computing, since IaaS clouds often use virtual machines to provision computational resources and my work deals with how to (1) map heterogeneous user requests (best effort, advance reservations, immediate availability, etc.) to virtual machines and (2) provision those virtual machines efficiently. Since a lot of my work involves writing resource scheduling code, my secondary interests include parallel job scheduling and scheduling performance metrics.

You can read more about this work in my [publications]({{< relref "publications.md" >}}) (and in my [dissertation]({{< relref "dissertation.md" >}}))

Since I have a teaching-focused position, my more recent publications have been in the field of Computer Science Education. I have also become more interested laterly in classical distributed systems problems, specially revolving around distributed consensus, but I have not done any work in that area.


Past Projects
-------------

The following are research projects I have been involved in:

### [Haizea](http://haizea.cs.uchicago.edu/)

Haizea is an open-source VM-based lease management architecture (if that sounds like a mouthful, take a look at the [What is Haizea?](http://haizea.cs.uchicago.edu/whatis.html/) page). In a nutshell, Haizea is a piece of software that, in combination with the [OpenNebula](http://opennebula.org/) virtual infrastructure manager, can be used to manage a Xen or KVM cluster, allowing you to deploy different types of leases that are instantiated as virtual machines (VMs). Haizea can also be run in simulation, providing a platform for experimenting with scheduling algorithms that depend on VM deployment or on the leasing abstraction. I was the lead developer for the Haizea project, but it is now effectively unmaintained.

### Reservoir (EU FP7 project)

In 2008 and 2009 I did summer internships for Reservoir, a project to "enable massive scale deployment and management of complex IT services across different administrative domains, IT platforms and geographies". As part of my internships, I worked with the [Distributed Systems Architecture](https://dsa-research.org/) group at the [Universidad Complutense de Madrid](http://www.ucm.es/). My work revolved mainly around the Haizea project mentioned above.

### Workspace Service

I was part of the group that develops the Workspace Service component of the Globus Toolkit 4 (the Workspace Service is now known as [Nimbus](http://www.nimbusproject.org/)). In particular, I was involved in VM-based virtual workspaces, "an abstraction of an execution environment that can be made dynamically available to authorized clients by using well-defined protocols. The abstraction captures resource quota assigned to such execution environment on deployment (such as CPU or memory share) as well as software configuration aspects of the environment (such as operating system installation or provided services). The Workspace Service allows a Grid client to dynamically deploy and manage workspaces."

### CrossGrid

I was a Research Associate for a short while (with affiliation to the [Instituto de Física de Cantabria](http://www.ifca.unican.es/) in Santander, Spain). My main job was writing and proofreading tutorial material.

### [BOOLE-DEUSTO](http://weblab.deusto.es/website/boole_deusto.html)

BOOLE-DEUSTO is a software aid for Digital Electronics courses. It helps and guides the student through typical exercises: minimization of boolean functions, Veitch-Karnaugh maps, design and simulation of finite-state machines, circuit diagrams (combinational and sequential), etc. I was involved in this project from 2000 to 2004 as Lead Programmer. The project was developed at the University of Deusto and lead by Professor Javier García Zubía.
