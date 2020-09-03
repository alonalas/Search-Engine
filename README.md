# Search-Engine

The document retrieval process is done as follows:
-Perform a parsing and normalization operation on the documents in the document repository.
-Create posting files that contain the words after performing the normalization operations.
-"Stop words" filtering.
-Each posting file contains words sorted in alphabetical order for quick word retrieval.


The query or query file is parsed in a manner similar to how documents are parsed.
The matching between the query to the words in the document repository is computed by BM25 formule.
In the end, documents are sorted from the most similiar document (high ranked) to the lowest.
Return to the user the 50 highest rated articles


To create a dictionary:

Insert a path to the folder that contains articles where you want to search in.
Insert a path where you want the posting files to be saved.
Choose whether you want to perform stemming or not.


To find the most relevant articles for you:

Insert a single query or choose a query file that you want to search.
Choose whether you want to perform stemming on your query (choosing yes is recommended if your dictionary was built with stemming)
Choose whether you want to show entities that included in the results (such as cities, countries, names, etc.)
Choose whether you want to perform a semantic model on your search.
Choose whether to save the results or not.


This search engine was designed and created by third year ISE students Alona Lasry and Chen Shoresh as part of Information retrieval course.
