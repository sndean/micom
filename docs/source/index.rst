.. micom documentation master file, created by
   sphinx-quickstart on Thu Mar  9 13:00:06 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to micom
================

|travis status| |appveyor status| |coverage| |pypi status|

*Please note that this is still a pre-release and might still lack
functionalities.*

`micom` is a Python package for metabolic modeling of microbial
communities developed in the
`Human Systems Biology Group <https://resendislab.github.io>`_ of
Prof. Osbaldo Resendis Antonio at the `National Institute of Genomic
Medicine Mexico <https://inmegen.gob.mx>`_.

`micom` allows you to construct a community model from a list on input
COBRA models and manages exchange fluxes between individuals and individuals
with the environment. It explicitly accounts for different abundances of
individuals in the community and can thus incorporate data from 16S rRNA
sequencing experiments. It allows optimization with a variety of algorithms
modeling the trade-off between egoistic growth rate maximization and
cooperative objectives.


Attribution
-----------

If you want to use micom in a scientific publication the attribution clause in
the license is covered by citing our relevant publication. However, we are still
in the process in pairing micom with validations so that publication still
**does not exist**. If you want to use micom before that article is published please
contact us at `oresendis (at) inmegen.gob.mx`. Thanks :D

To get an idea which assumptions and strategies `micom` uses we recommend
to start with some background on the :doc:`methods <logic>`.

Contents
--------
.. toctree::
   :maxdepth: 1

   Methods used by micom <logic>
   Installing micom <installing>
   Building communities <community>
   Growth rates and fluxes <growth_fluxes>
   Growth media <media>
   Knockouts <taxa_knockouts>
   Intervention studies <elasticities>
   Analyzing many samples in parallel <workflows>
   API <micom>


Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

.. |travis status| image:: https://travis-ci.org/resendislab/micom.svg?branch=master
   :target: https://travis-ci.org/resendislab/micom
.. |appveyor status| image:: https://ci.appveyor.com/api/projects/status/m9d8v4qj2o8oj3jn/branch/master?svg=true
   :target: https://ci.appveyor.com/project/resendislab/micom/branch/master
.. |coverage| image:: https://codecov.io/gh/resendislab/micom/branch/master/graph/badge.svg
   :target: https://codecov.io/gh/resendislab/micom
.. |pypi status| image:: https://img.shields.io/pypi/v/micom.svg
   :target: https://pypi.org/project/micom/
