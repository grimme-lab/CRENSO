|GitHub release| |DOI|

.. |GitHub release| image:: https://img.shields.io/github/v/release/grimme-lab/CRENSO
   :target: https://github.com/grimme-lab/CRENSO/releases/latest


.. |DOI| image:: https://img.shields.io/badge/DOI-10.1021/acs.jpca.1c00971-blue
   :target: https://doi.org/10.1021/acs.jpca.1c00971


====================
CRENSO / CREST_COMBI
====================

Introduction
============

``crenso`` and ``crest_combi`` are designed to automate ``CREST`` and ``CENSO`` 
for calculating properties like: pka, logP, OR and NMR.

``crest_combi`` uses ``CREST`` to efficiently create structure ensembles (SE) 
from several PES.

``crenso`` uses ``crest_combi`` for the SE generation and ``CENSO`` for the high 
level free energy sorting and property calculation.

Setup:
======

Download scripts and make them executable:

.. code:: bash

    $ chmod u+x crenso
    $ chmod u+x crest_combi


Usage example:
==============

.. code:: bash

    $ crenso -l1opt -kow 

For information on command line arguments use:

.. code:: bash

    $ crenso -h
    $ crest_combi -h


Citation
========

How to cite:

Title: Efficient quantum chemical calculation of structure ensembles and free energies for non-rigid molecules

Authors: Grimme, Stefan; Bohle, Fabian; Hansen, Andreas; Pracht, Philipp; Spicher, Sebastian; Stahn, Marcel

General reference:

S. Grimme, F. Bohle, A. Hansen, P. Pracht, S. Spicher, and M. Stahn 
*J. Phys. Chem. A* **2021**, XXXX, XXX, XXX-XXX.

DOI: `10.1021/acs.jpca.1c00971 <https://doi.org/10.1021/acs.jpca.1c00971>`_. 

License
=======

``crest_combi`` and ``crenso`` are free software: you can redistribute it 
and/or modify it under the terms of the GNU Lesser General Public License 
as published by the Free Software Foundation, either version 3 of the License, 
or (at your option) any later version.

``crest_combi`` and ``crenso`` are  distributed in the hope that they will be 
useful, but without any warranty; without even the implied warranty of
merchantability or fitness for a particular purpose. See the
GNU Lesser General Public License for more details.

