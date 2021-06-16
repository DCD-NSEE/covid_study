.. Covid_data documentation master file, created by
   sphinx-quickstart on Wed Jun 16 10:40:26 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Predicting COVID-19 in very large countries: the case of Brazil
===============================================================

Authors
-------
V.C.Parro¹, M.L.M.Lafetá¹, F. Pait², F.B.Ipólito¹, T.N.Toporcov³

**1** Instituto Mauá de Tecnologia, Electrical Engineering, São Caetano do Sul, 09580-900, Brazil.

**2** Escola Politácnica da Universidade de São Paulo, São Paulo, 05508-900, Brazil.

**3** Faculdade de Sáude Pública da Universidade de São Paulo, São Paulo, 01246-904, Brazil.

Abstract
--------

This work presents a practical proposal for estimating health system utilization for COVID-19 cases. The novel methodology developed is based on the dynamic model known as Susceptible, Infected, Removed and Dead (SIRD). The model was modified to focus on the healthcare system dynamics, rather than modeling all cases of the disease. It was tuned using data available for each Brazilian state and updated with daily figures. A figure of merit that assesses the quality of the model fit to the data was defined and used to optimize the free parameters. The parameters of an epidemiological model for the whole of Brazil, comprising a linear combination of the models for each state, were estimated considering the data available for the 26 Brazilian states. The model was validated, and strong adherence was demonstrated in most cases.

Complete and detailed documentation is available on `Epidemic Models <https://epidemicmodels.readthedocs.io/en/latest/>`_.

Data
----

Download de data :download:`until June 30, 2020 <cases-brazil-states-june30.xlsx>`

Download de data :download:`after June 30, 2020 <cases-brazil-states-after-june30.xlsx>`


.. toctree::
   :maxdepth: 2
   :caption: Covid Data from Brazil

   Covid_Data