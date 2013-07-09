Service-level Aware Cloud Resource Manager
==========================================

This project contains source code associated to the following article submitted to [SoCC2013](http://www.socc2013.org):

> Cristian Klein, Martina Maggio, Karl-Erik Årzén, Francisco Hernández-Rodriguez,
> "Introducing Service-level Awareness in the Cloud"

The branches of this repository are orginazed as follows:

* `actuator`: author version of the article, prototype implementation of the workload generator, the resource manager and the scripts that have been used to conduct experiments and plot the results;
* `rubis`: service-level-aware extension of RUBiS and its local controller;
* `rubbos`: service-level-aware extension of RUBBoS and its local controller.

Usage
-----

To conduct the experiments, we used Ubuntu 12.04.2 LTS. Other software has been installed from the official repositories, specifically:

* Linux 3.2.0
* Xen 4.1.2
* GNU compiler collection 4.6.3
* GNU make 3.81
* Boost C++ libraries 1.48
* libvirt 0.9.8
* TinyXml 2.6.2
* libcurl 7.22.0
* Python 2.7.3
* Apache 2.2.22
* PHP 5.3.10
* MySQL 5.5.31

Installing this software on top of Ubuntu can be achieved using the following commands:

    sudo apt-get install xen-hypervisor-4.1-amd64 build-essential \
		libboost1.48-all-dev libvirt-dev libtinyxml-dev libcurl4-openssl-dev \
		python apache2 libapache2-mod-php5 mysql-client mysql-server

For questions or comments, please contact Cristian Klein <firstname.lastname@cs.umu.se>.
