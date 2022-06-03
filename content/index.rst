Introduction to Quantum Computing and hybrid HPC-QC systems
===========================================================

Recent developments in quantum technology are bringing the world
closer to a new technological revolution – the advent of usable
quantum computers able to provide enormous acceleration to important
computational tasks. In coming years, quantum computing is expected to
have a huge impact on practically all areas of research that can
utilise computational modelling.

Starting operations in April this year, the NordΙQuEst project brings
together a consortium of seven partners from five Nordic and Baltic
countries to connect world-leading traditional HPC resources and
quantum computers across national borders with the aim to establish a
quantum computing platform customised to the needs of the region.


ENCCS is now joining forces with NordIQuEst to deliver two-day
training workshops covering the fundamentals of quantum computing (QC),
including:

- Introduction to key concepts: quantum states, qubits, quantum algorithms
- QC programming in high-level languages for use cases in
  optimisation, finance and quantum chemistry followed by testing
  quantum programs to esure their correctness
- Overview of the main QC hardware approaches
- Integration of QC with classical computing: hybrid classical/quantum
  algorithms and HPC-QC systems.
- Introduction to quantum software testing with Quito tool
  

.. prereq::

   For the hands-on training sessions, basic familiarity with Python
   and some experience working in a Unix environment are desirable. No
   previous experience with quantum computers expected.

.. callout:: Run on Binder

   All notebooks contained in this material can be launched on
   `mybinder.org <https://mybinder.org/>`__ for interactive exploration
   and exercise work. Click the badge below to spin up
   an instance in the cloud.

   .. image:: https://mybinder.org/badge_logo.svg
	      :target: https://mybinder.org/v2/gh/ENCCS/NordIQuEst-workshop/HEAD	       
	       

.. csv-table::
   :widths: auto
   :delim: ;

   45 min ; :doc:`landscape`
   45 min ; :doc:`introduction`   
   20 min ; :doc:`quantum_states`
   45 min ; :doc:`hybrid_algorithms`
   45 min ; :doc:`programming_qc`
   
.. toctree::
   :maxdepth: 1
   :caption: Preparation

   setup

.. toctree::
   :maxdepth: 1
   :caption: Day 1 lectures

   landscape
   introduction
   qc_hardware
   programming_qc

.. toctree::
   :maxdepth: 1
   :caption: Day 1 hands-on

   E1_qc-1
   E1_qc-2
   E1_qc-3
   
.. toctree::
   :maxdepth: 1
   :caption: Day 2 lectures

   hybrid_algorithms
   
.. toctree::
   :maxdepth: 1
   :caption: Day 2 hands-on

   quito	    

	     
.. toctree::
   :maxdepth: 1
   :caption: Reference

   example
   quick-reference
   guide



.. _learner-personas:

Who is the course for?
----------------------

This training material is for anyone interested in learning the basics
of Quantum Computing.




About the course
----------------







See also
--------





Credits
-------

The lesson file structure and browsing layout is inspired by and
derived from `work <https://github.com/coderefinery/sphinx-lesson>`_
by `CodeRefinery <https://coderefinery.org/>`_ licensed under the `MIT
license <http://opensource.org/licenses/mit-license.html>`__. We have
copied and adapted most of their license text.

Instructional Material
^^^^^^^^^^^^^^^^^^^^^^

This instructional material is made available under the
`Creative Commons Attribution license (CC-BY-4.0) <https://creativecommons.org/licenses/by/4.0/>`_.
The following is a human-readable summary of (and not a substitute for) the
`full legal text of the CC-BY-4.0 license
<https://creativecommons.org/licenses/by/4.0/legalcode>`_.
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit (mentioning that your work
  is derived from work that is Copyright (c) ENCCS and individual contributors and, where practical, linking
  to `<https://enccs.github.io/sphinx-lesson-template>`_), provide a `link to the license
  <https://creativecommons.org/licenses/by/4.0/>`_, and indicate if changes were
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits.

With the understanding that:

- You do not have to comply with the license for elements of the material in
  the public domain or where your use is permitted by an applicable exception
  or limitation.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  publicity, privacy, or moral rights may limit how you use the material.


Software
^^^^^^^^

Except where otherwise noted, the example programs and other software provided
with this repository are made available under the `OSI <http://opensource.org/>`_-approved
`MIT license <https://opensource.org/licenses/mit-license.html>`__.
