Hierarchical Interest Graph datasets
==========

This repository comprises of the datasets that are created for our approach that generates 
Hierarchical Interest Graph for Twitter users.

The two datasets are zipped files and their description are as follows:

1. wikipedia-hierarchy-priority -- This dataset comprises of the Wikipedia Hierarchy as a tab seperated file. The format of
              the tsv is <br>
              \<sub-category\>\<tab\>\<category\>\<tab\>\<priority\><br>
              \<sub-category\> and <category> are labels of Wikipedia categories<br>
              \<priority\> is an integer value that reflects the suitability of the <category> being a category of <sub-category>

              Numbers: 802,194 Categories 
                       1,177,558 Category-Subcategory relationships
2. irrelevant-wiki-categories -- This dataset comprises of the list of Wikipedia Admin Categories that are removed
              from the Wikipedia Category Graph before creation of the Wikipedia Hierarchy. 

              Numbers: 64,362 Categories

      
