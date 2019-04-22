# pagerank_uiowa_domain

This project was developed as part of my Large Data Analysis course.

My objective was to implement Google's pagerank algorithm in the www.uiowa.edu domain and determine which urls are most important and which are least important. Additionally most common words in each url were extracted to simulate a search engine.

For more information about Google's pagerank alogorithm see [here](https://en.wikipedia.org/wiki/PageRank).

## Approach
1) Development of a web crawler to extract links and top 9 common words
  - Removed stop words
  - Considered only the root words
2) Storing links and urls(along with top common words in each url) in an SQLite database and 2 csv files
3) Preparing dataframes and running the algorithm
4) Filter out most important and least important urls

## Technologies
1) Python3
2) pandas
3) numpy
4) beautifulsoup
5) sklearn
6) nltk

## Outcome
### Most important urls

1) https://admissions.uiowa.edu/apply/apply?utm_source=uiowa&utm_campaign=homepage_header
2) http://www.uiowa.edu
3) https://iam.uiowa.edu/whitepages
4) https://www.uiowa.edu/students
5) https://now.uiowa.edu
6) https://now.uiowa.edu/media-relations
7) https://now.uiowa.edu/staff-list

### Least important urls

1) http://hris.uiowa.edu/classcomp/merit/descr_docs/GC75.doc
2) https://education.uiowa.edu/person/
3) http://www2.education.uiowa.edu/directories/
4) https://belinblank.education.uiowa.edu/students/
5) https://transportation.uiowa.edu/
6) https://uc.uiowa.edu/file/
7) http://www.lib.uiowa.edu/locations/main
