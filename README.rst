############################################
Automated Data Inquiry for Oil Spills: ADIOS
############################################

This repository serves as a communication center for the NOAA Oil Library Project:

**Automated Data Inquiry for Oil Spills: ADIOS**

`See the Project Documentation Here <https://noaa-orr-erd.github.io/ADIOS/>`_


NEWS
====

NOAA/ADIOS will be at `Interspill <https://www.interspillevent.com/>`_ in London, England, 12-15 March, 2018.

If you have an interest in the project, please find Chris Barker (look for the NOAA Logo on his shirt). Or drop him an email to arrange a meeting:

Chris.Barker@noaa.gov


Project goals
=============

The goal of this project is to provide a publicly available library of oil chemistry data that can be used to support oil spill response, planning, and preparedness.

We aim to provide not just data itself, but software to make it easy to access and manipulate the data.

NOTE: We apologize for possible naming confusion -- this project is about only the oil database, not the oil weathering/fate model known as ADIOS2. In ADIOS2, the oil database was embedded in the Fate model. With this new effort, we are separating the oil database and associated tools from the model, as a stand alone product, so that it can be used on its own as a source of data about oils for responders, and even as a data source for other models.

For fate modeling, we have merged (and updated) the ADIOS2 weathering algorithms in our new version of GNOME, which is managed in gitHub here:

https://github.com/NOAA-ORR-ERD/PyGnome


ADIOS Components
================

The project will consist of multiple integrated components:

* Publicly accessible database of oils and their properties suitable for oil spill planning, response, modeling (and environmental impact analysis and injury assessment?).

* User interface software for viewing and manipulating the database (web based and desktop).

* Web API for accessing the data over the Internet (hosted by NOAA).

* Software library (in the Python language) for working with the data via code.

* Data and file format standards for data import / export and interchange.


Open Source:
------------

All data and software will be openly available and unencumbered by licensing restrictions.

Software source code will be published (probably on gitHub) -- open source license or public domain.

Oil Data will be available via a public Web API.


Proprietary data:
-----------------

There is a need for spill responders and government agencies to occasionally work with business proprietary data. No such data will be in the public database hosted by NOAA. But the software and data interchange formats will be independent of the data itself. Any organization will be able to use the software to manage their own data as they see fit. The database software will be able to export and import full data records (or multiple records), if there is a need to transfer data from one database to another, or use a database record to initialize an oil spill model, such as NOAA's GNOME model.


Contacts
========

For collaboration opportunities and project level information:

Chris.Barker@noaa.gov

For oil chemistry / assay questions:

Robert.Jones@noaa.gov


License
=======

This repository is a scientific product and is not official communication of the National Oceanic and Atmospheric Administration, or the United States Department of Commerce. All NOAA GitHub project code is provided on an 'as is' basis and the user assumes responsibility for its use. Any claims against the Department of Commerce or Department of Commerce bureaus stemming from the use of this GitHub project will be governed by all applicable Federal law. Any reference to specific commercial products, processes, or services by service mark, trademark, manufacturer, or otherwise, does not constitute or imply their endorsement, recommendation or favoring by the Department of Commerce. The Department of Commerce seal and logo, or the seal and logo of a DOC bureau, shall not be used in any manner to imply endorsement of any commercial product or activity by DOC or the United States Government.


Software code created by U.S. Government employees is not subject to copyright in the United States (17 U.S.C. §105). The United States/Department of Commerce reserve all rights to seek and obtain copyright protection in countries other than the United States for Software authored in its entirety by the Department of Commerce. To this end, the Department of Commerce hereby grants to Recipient a royalty-free, nonexclusive license to use, copy, and create derivative works of the Software outside of the United States.
