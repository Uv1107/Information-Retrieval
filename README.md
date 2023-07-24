Search Engine for Movies


Problem Statement:

Building a search engine that will serve a certain domain's
demands is the work at hand. Documents providing data about the
specified domain must be fed to your IR model. The data will then
be processed, and indexes created. The user will then type a query
when this is finished. The top 10 pertinent papers should be
returned as the output.


Project By:
    Utkarsh Verma: Roll No- S20200010215

How to run the code

Before running install the modules: 

              pip install nltk
              pip install pandas
              pip install flask



Run files in the order: 

              py preprocess.py
              py tfidf.py
              py server.py
In your browser go to `http://localhost:3000/`
Type your query in the search bar and wait till it returns the relevant documents.

---------------------------------------------------------------------------------------------------
Dependencies/modules used

nltk
pandas
pickle
Numpy
heapq
flask
os
