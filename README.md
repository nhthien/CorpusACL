CorpusACL
=========

This corpus contains the technical papers in the proceedings of the Annual Meeting of the Association for Computational Linguistics (ACL) from 2000 to 2011.
The categories of a given paper are the research topics in Natural Language Processing (NLP) such as Named Entity Recognition, Summarisation, Machine Translation and so on.
The total number of papers in the collection: 1972.
The total number of categories: 38.

======================
File "category.txt":
This file contains a list of categories with the format:

    ID    CategoryName

ID: the ID of the current category.
CategoryName: the category name of the current ID.
======================
File "papers.txt":
This file contains 1972 papers with the following information:

    ID    Title    Authors    URL    Session    Categories

ID: the ID of the current paper.
Title: the title of the current paper.
Authors: the authors of the current paper.
URL: the URL of this paper in the ACL Anthology website.
Session: In the conference program, scientific papers are divided into session titles based on their research topics. These session titles are useful information to determine the categories (research fields) of papers.
Categories: the research fields of the current paper.

=======================
File "StatisticalCorpus.txt:
This file contains the 38 categories with the corresponding number of papers.

	ID	#ofpapers

ID: ID of the current category.
#ofpapers: the number of papers in the current category.

=======================
Folder "TXT"
This folder contains the 1972 papers under the text format.
We convert the PDF files to text files using pdftotext tool.
