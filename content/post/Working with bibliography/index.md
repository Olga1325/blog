---
title: Working with bibliography 
subtitle: Use of atomic energy. Among them, it is necessary to highlight the tasks designed to ensure the safety of personnel during the performance of radiation but-dangerous work of great social and practical importance.

# Summary for listings and search engines
summary: Welcome 👋 We know that first impressions are important, so we've populated your new site with some initial content to help you get familiar with everything in no time.

# Link this post with a project
projects: []

# Date published
date: '2023-03-13T00:00:00Z'

# Date updated
lastmod: '2023-03-13T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - admin

tags:
  - Working with bibliography

categories:
  - post 3
---

```python
import libr
print('hello')
```

## Overview

In the report questions of use of control systems are considered by the biblio
graphic information at carrying out of scientific researches. Comparative characteris
tics of known systems are resulted. On an example of one of them (Zotero) the deci
sion of problems of creation of the list of the used sources in accordance with GOST
7.1-2003 is considered. all this without any additional effort.

In the course of scientific research, it is necessary to carry out
a review of many published works in the field under study. At
This accumulates a large number of references to documents, saves them
full texts in electronic (and sometimes in paper) form. When it comes
time of writing a scientific report, monograph or article, there are many
in questions. How to navigate in the accumulated amount of information? How to make a list of used sources in the presence of times
ny state standards and requirements of publishers?

Solving the problem of systematic work with bibliography allows
bibliographic information management systems (BIS, reference man
age software). Bibliographic information management systems for
allow to create, store and reuse bibliographic
references, forming lists of sources used in scientific articles,
monographs, books and reports.

The use of SUBI is justified, since when studying the ratio
the number of published scientific papers to the number of downloaded full texts from
electronic periodicals signed by universities (according to the statistics of the leading euro
Russian, American and Russian universities), per scientific publication with
there are from 90 to 120 uploaded articles. Number of libraries viewed
there are even more graphic descriptions as a result of searching and reading information.
In the process of comprehending the information found, a large set of
notes that can be used to write scientific articles. Ve
Note-taking can be done in SUBI and obtained from the collected records
article drafts.

You can enter bibliographic information about documents manually.
But most search engines for scientific resources (Google Scholar, SCOPUS,
WoK, etc.) and e-journal access platforms (ScienceDirect, Sprin-
gerLink, etc.) allow you to get a bibliographic description in a format up to
allowing direct import to SUBI.

SUIS includes a database and a system for generating selected references in
formats defined by the standards or rules adopted by the publisher
properties. Integration with well-known word processors allows you to
arrange links according to the text of a scientific work and automatically generate
tion of the list of sources used. A number of systems have the ability to
port (export) elements of bibliographic references from the biblio
graphical databases and websites, enable collaboration and
access to the database from any computer connected to the Internet.

At present, many such systems are known;
some of them for a number of parameters. The first to appear were
nye proprietary (proprietary, non-free) library management systems
graphic information:
- Bookends (appeared in 1983, developer Sonny Software, price $99);
- Reference Manager (appeared in 1984, developed by Thomson Reuters,
price $239.95);
- EndNote (appeared in 1988, developed by Thomson Reuters, price
$299.95);
- Biblioscape (appeared in 1998, developer CG Information, price $79-
$299);
- RefWorks (appeared in 2001, developer RefWorks, price $100 for
year).

There are much more free (free) systems (about 20). Some of
they appeared just a few years ago and, in terms of their capabilities, are not
blunt proprietary.
Let's dwell on the two most popular systems in recent times.
bibliographic information management: Zotero (introduced in 2006,
developer Center for History and New Media at GMU, site www.zotero.org) and
Mendeley (appeared in 2008, developed by Mendeley, website
www.mendeley.com). The advantages of Zotero and Mendeley include
following:
- free to use (although Mendeley, unlike Zotero,
proprietary system due to closed source code);
- saving bibliographic information "on the fly" when viewing
sites (you can automatically add bibliographic elements to the database)
information, for example, through the RIS or BibTeX format);
- automatic saving together with the bibliography of the full text of a hundred
tii in PDF or HTML formats (if available);
- the ability to create a bibliography in MS Word, OpenOffice Writer and
other word processors;
- multi-platform (the ability to work under different operating
systems);
- the ability to synchronize with the server to store the database.

Both SUBIs use style files in csl format configured for
different requirements of publishers for the design of the bibliography. There is even food
A.A. Chetverikov style files according to GOST R 7.0.5-2008. However
for scientific reports and works, GOST 7.1-2003 should be used.
There are differences between the SUBI data. In favor of Zotero at the moment there is
three arguments:
- more stable operation (this is indirectly indicated by the numbers of current
versions: Zotero has version 2.09, Mendeley has version 0.9.8.1);
- open source code, which allows (if desired and knowledge of the basics of
gramming) customize the SUBI to fit your needs;
- the presence of a Russian-language interface and a support site
(http://www.zotero.org/support/ru/start).

What makes it difficult for these systems to create a style that complies with GOST
7.1-2003? A number of features of the formatting language used by systems
citations CSL (Citation Style Language), developed on the basis of XML. It is open and
is an international standard independent of any specific
application, document format, or programming language. However
there are a number of growth issues: getting to some of the bibliography fields from Zote
ro is impossible.

The presentation of bibliographic records within Zotero is based on
uses the MODS standard (Metadata Object Description Schema,
http://www.loc.gov/standards/mods/) which contains all fields required
mye for the formation of bibliographic records. However, in the module, answer
For formatting citations in CSL in Zotero, not all fields are available
or displayed correctly.

The openness of the Zotero code makes it easy to fix incomplete or inconsistent
the correctness of mapping the MODS format to CSL objects, since, unfortunately, it is very
it is difficult to achieve quick changes in officially supported
my code in the Zotero project. For example, accessibility at the formatting level
the book page number field was officially added a year after the
a remote request on the support forum. Therefore, it takes a gene to work.
Publish the corrected version when new versions of Zotero are released. Fixed
Newer versions are available under the same license. Fixed
Newer versions are available under the same license. They can be downloaded from the website
GOST 7.1 bibliography support project for the Russian style at
http://code.google.com/p/zotero-gost-rus-bibliography/. On the download page
instructions for installing Zotero, filling in the fields, and a style file are available.
In the future, it is planned to make all changes to the main branch of development
the Zotero project and add the created style to the official sti repository
lei.

Corrections that are related to the incompleteness or incorrectness of the
Fermentations in CSL are listed below:
- added access to the date field of the last page availability check
site, accessDate field;
- to support the correct display of documents in different languages
made available the language field, which allows, in particular, in English
lingual links use formatting elements on the same
language
- for a complete presentation of patent descriptions and official publications
added support for the following fields: assignee, patentNumber,
priorityNumbers, legalStatus, and applicationNumber;
- fixed display of record type report, because in the original version
a report is treated as a book entry.

A number of other changes have also been made. In particular, the formation
information about the first author and fields of responsibility that are created in
depending on the number of authors.
The changes made to Zotero and the style developed will allow scientific
employees, teachers, graduate students and students to reduce the time for
preparation of scientific publications and competently draw up a list of used materials
exacters.



















































































