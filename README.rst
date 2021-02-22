====================
CRENSO / CREST_COMBI
====================

Introduction
============

``crenso`` and ``crest_combi`` are designed to automate ``CREST`` and ``CENSO`` for calculating
properties like: pka, logP, OR and NMR.

``crest_combi`` uses ``CREST`` to efficiently create structure ensembles (SE) from 
several PES.

``crenso`` uses ``crest_combi`` for the SE generation and ``CENSO`` for the high level
free energy sorting and property calculation.

Setup:
======

Download scripts and make it executable:

.. code:: bash

    $ chmod u+x crenso
    $ chmod u+x crest_combi


Usage example:
==============

.. code:: bash

    $ crenso -l1opt -kow 

