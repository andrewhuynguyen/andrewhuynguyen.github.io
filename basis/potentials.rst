1D Quantum Potentials
=====================

The basis solution requires the knowledge of the potential, defined in a potential
config file.

Configuration section
---------------------

A potential is defined using the section '[parameters]' and
'[regions]'


-  **[parameters]** has a list of "lowercase" parameters names as 
  options with default values.
-  **[regions]** opttion are region number, values have the form:

  --code-block: bash


  --code-block: python
	lambda x: v0*(x-shift)**2 -numpy.nd(x)
 function can use numpy or operator module in addition to parametes

API Documentation
-----------------

	synposis: How to config a 1D quantum solver.
