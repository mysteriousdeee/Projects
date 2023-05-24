# Projects
just a project completed during study year. a lot of improvement to be done.

Scenario
A SMB (small-to-medium business), Laurel Technology Solutions Ltd., has recently begun to
utilise the data they obtain from their customers. They are currently based within the UK with
a singular office location. Their IT systems are off-the-shelf components for their specific
areas (Finance, HR, etc), requiring manual intervention if any data needs to be compared /
crossed between those systems. Their customer data is split across these various systems.
E.g Credit card data is only stored by the financial systems, Employment is only within the
HR systems, etc. They do not currently have a single cohesive record representing all of
their customer data. They are looking to unify these ahead of further data investigation and
exploitation, and to pool these data together into a central database.

In the last financial year they have found huge success, with a large influx of new customers;
therefore, they are looking to expand. This expansion will allow them to take on even more
customers, and to expand their offerings/operations to include more social media aspects.

As part of this expansion, Laurel Technology Solutions Ltd., is looking at foreign markets
(East Asia), with an aim of setting up an office space initially located in Seoul, South Korea.
The Seoul office would be responsible for customers in that region; however, the main
company will still be based within the UK, and require regular communication back-and-forth,
including customer data. The company’s eventual goal is to improve their core infrastructure
by combining their different data streams with an aim to analyse, and then exploit their data.

Employees which are part of the UK branch will remain employed in the UK. New
Employees will be hired in South Korea for that office location. It is expected that there will
be executives of the company regularly travelling to the new office and needing to conduct
work from that location involving the UK branch.

3
Tasks
Tasks
In this assignment you are required to produce a Python program for combining multiple
data sources provided, and pushing these to a central organisational data store. This will
also involve a critical report, reflecting on the practical component, as well as
recommendations and critical evaluation of suitable technologies for the provided expansion
scenario above.

Task 1: Python ETL
For this component, you are provided data records from the given SMB. These data involve
customer attributes such as names, banking credentials, family attributes, etc. These data
files are provided as a mixed modality in a variety of formats (CSV, JSON, XML, and TXT).
The work herein requires the processing of these data into a homogenous record, aligning
the same customers from different sources together, which are then automatically entered
into a Relational Database System using modern tools & libraries.

4
You are expected to read and extract data from these various formats, wrangle the data -
solving inconsistencies if present - and bring data together into a singular format (See Figure
1 as an example). These unified records are then to be mapped to a relational database
using PonyORM, with all unified records being entered into the database. It is expected that
your code is sufficiently commented, especially where any documentation is referenced.
Your solution must ONLY make use of stock Python (including any libraries as part of
the standard library: E.g csv, xml, json), and PonyORM.

Any work utilising libraries not stated above will be ignored and awarded a mark of 0.
You shall NOT utilise libraries such as the Pandas library, all code should be standard
python you have written to perform these functions with the exception of PonyORM.
For a complete list of the standard Python Libraries please consult the documentation
available at https://docs.python.org/3.10/library/ (or 3.9 / 3.8, depending on the version
you are utilising).

As part of this task, and in addition to the Python solution, you will produce a 10-15 minute
recorded presentation reflecting on the types of data provided and the challenges with
combining them. In particular, you should reflect on this from a data perspective as well as a
personal perspective (the process of you undertaking the task itself, any difficulties faced,
challenges overcome, etc.); within this you are expected to walk through your solution as
part of this process.

The final part of the presentation should cover any difficulties the company may have in
automating such a process, and/or any future considerations given the scenario provided.
The structure and style of this presentation is at your discretion. You may wish to use a
mixture of voice-over, presentation slides, and direct oration.
