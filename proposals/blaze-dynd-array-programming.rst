Blaze and DyND: Large Scale Array Programming in Python
-------------------------------------------------------

Summary:

Blaze is a large scale array programming system being developed at
Continuum Analytics. It implements a data structure similar to
NumPy and Pandas, but working with data distributed across multiple
sources viewed as a coherent array. Expressions on these tables and
arrays are created as a deferred graph, which are run on servers near
the data. Supporting Blaze is DyND, a C++ dynamic array programming
library, built to support the in-memory data structure needs. It
generalizes the data model of NumPy and Python's buffer protocol,
dynamically composing data types and associated array metadata.
Supported, for example, are ragged arrays as a variable-sized dimension.

Intended audience:

Scientists, Engineers, and others using the scientific and data
analysis Python software stack based on NumPy, SciPy, Pandas, etc.

Given before?:

Related talk at SciPy 2013:
http://conference.scipy.org/scipy2013/presentation_detail.php?id=175

About you:

Mark is part of the Continuum Analytics team, helping build Blaze,
an array programming platform for Python. He comes from the visual
effects industry, where he led the R&D department at Frantic Films.
Mark has used Python as the basis for Flood, a fluid simulator for
VFX, as well as contributed to the NumPy project.
