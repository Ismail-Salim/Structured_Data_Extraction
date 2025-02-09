# Structured_Data_Extraction
- This is a code to access journal articles and extract the text, then search the text for interesting information by choosing your topic's keywords, and search year(s). 
- The capabilities of this approach are shown by data extraction for the "Dry Methane Reforming" (DMR) reaction.
- The code compromise of two files of 4 different parts:
  * Parts 1 and 2 apply three filters (on the title, the keywords, and the abstract). The result of these parts is an Excel file with (n) rows for articles and (  DOI ----- Title --- Abstract --- publication date keywords ) for each article, as columns.
  * Parts 3 and 4 apply the first 3 applications, then extract the full text of the articles, then apply the last two applications

1: Access the publications using your own API and institution keys.

2: The text is filtered by a four-stage screening approach; the title, the article keywords, the abstract, and finally the body text of the article.

3: Define your topic by choosing appropriate search words for each filter stage. 

4: Define your search year(s), that is article publication year.

5: The "topic_analysis" parameter is a string used to name the results, so it is advised to choose a representative name for your topic.

6: The results of the applications are automatically saved into your folder, choose the application of interest from below five applications.
  6.1	Application 1: Analyze the abstract.
  6.2	Application 2: Targeted search of the abstract.
  6.3	Application 3: Targeted search of the titles and keywords.
  6.4	Application 4: Full-text: Characterization techniques search.
  6.5	Application 5: Full-text: Extract a particular section of the articles.

This code is part of the journal article publication ...... Please cite according to the following .... ### (Edit line after publication) ###
