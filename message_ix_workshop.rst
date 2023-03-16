.. _messageix workshop:

MESSAGEix Workshop
^^^^^^^^^^^^^^^^^^

The aim of the workshops is to help new users of the MESSAGEix
modelling framework getting started with their modelling work.
The main features of the “framework” are introduced, and the
use cases of some features are shown. The users can learn how
to build an energy model and how to represent some policy
constraints in their energy scenarios.
For information about the model, its structure, mathematical
formulation and much more, please see the `documentation <https://docs.messageix.org>`_.

.. contents:: Table of Content
   :local:

Upcoming events
""""""""""""""""

* 5-7 and 12-13 June 2023 - MESSAGEix Workshop
* 24-25 May 2023 - MESSAGEix Community Meeting (`more info and the agenda <https://iiasa.ac.at/events/may-2023/messageix-community-meeting-2023>`_)

Past workshops and seminars
""""""""""""""""

* 7-13 June 2022
* 7-8 May 2022 - 1st Annual MESSAGEix Community Meeting (`more info and the agenda <https://iiasa.ac.at/events/may-2022/messageix-community-meeting>`_)
* 7-11 June 2021 (`download <http://pure.iiasa.ac.at/id/eprint/17318/>`_)
* 7-10 September 2020
* 8-12 June 2020

Learning objectives
"""""""""""""""""""

The learning objectives of the workshops are the following:

* Gaining a good understanding of energy systems modelling.
* Getting to know the main features of MESSAGEix.
* Building an energy model and solving it.
* Applying further policy constraints to the model.
* Getting insights on version control, testing and documentation in
  software development.
* Understanding collaborative model development and continuous
  integration (GitHub).

Needed requirements
"""""""""""""""""""

Each workshop is designed to be accessible for users with different
backgrounds and levels of experience with the modelling. However, there
are some pre-requisite knowledge and skills which you should
go through before getting started, including:

* Elementary computer programming (preferably in the Python or R language);
* Fundamental concepts of mathematical modelling, optimization,
  and data analysis; and
* Energy systems (e.g., energy supply, energy conversion
  technologies, and demand sectors and their linkages).

For a complete list, plus links to learning resources, see
`“Pre-requisite knowledge & skills" repo <https://docs.messageix.org/en/stable/prereqs.html>`_
in the documentation.

Installation of MESSAGEix
""""""""""""""""""""""

Installing MESSAGEix before you're getting started with the workshop is highly
recommended. Complete instructions are provided in the documentation on the
`“Installation” <https://docs.messageix.org/en/stable/install.html>`_
page of the documentation.

To successfully work through this workshop, we emphasize a few points
from the instructions:

* If you are not already familiar with the other installation methods,
  you should use Anaconda to install the framework.

* Under the `“Tutorials” <https://docs.messageix.org/en/stable/tutorials.html>`_
  page, you can download some simple models developed using MESSAGEix. To run these
  sample models, you need to install the Jupyter notebook software from Anaconda
  Navigator.

You can check our GitHub pages, where common issues and solutions are discussed:
https://github.com/iiasa/message_ix/discussions

Agenda
""""""

**Section I: Introduction to MESSAGEix modelling framework**

* Introduction to the MESSAGEix modelling framework and its components.
* Troubleshooting of the installation.

**Section II: Building a simple MESSAGEix model**

* Brief introduction to linear optimization.
* A review of energy systems modelling.
* Building a simple model of a coffee machine from scratch using MESSAGEix
  (step-by-step hands on guide).
* Discussing some main parameters/equations of the mathematical model.

**Section III: Energy system modelling with MESSAGEix**

* Building a single region energy model using MESSAGEix (step-by-step guide,
  going through MESSAGEix online tutorial: `Westeros Baseline <https://github.com/iiasa/message_ix/blob/v3.3.0/tutorial/westeros/westeros_baseline.ipynb>`_)
* Modelling some energy and environmental policies (share of
  renewables and emission targets).
* Discussing dynamic constraints and related parameters/equations in MESSAGEix.

**Section IV: Postprocessing and model software development**

* Introduction to MESSAGEix reporting and post-processing tools.
* Version control, testing, documentation in software development.
* Brief intro to collaborative model development and continuous integration
  (GitHub).

**Section V: Modelling forum**

In this free-format session, different modelling topics asked by the latest
workshop participants will be discussed.
