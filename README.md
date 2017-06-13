# EntityLinkingRetrieval-ELR for PyLucene 6
A slightly modified version of EntityLinkingRetrieval-ELR that works for PyLucene 6  

Original version: https://github.com/hasibi/EntityLinkingRetrieval-ELR

Mainly rewrite some functions in nordlys/retrieval/lucene_tools.py  

Only for index of original version. If you want to use your own index, use term vector to store string value instead of textfield (or you can rewrite some functions (mainly about computing term frequencies in a document) in lucene_tools.py to support lucene 6 fields).  


# License

No copyright for modified part

The copyright of unmodified part is owned by the original authors:  

Faegheh Hasibi (faegheh.hasibi@idi.ntnu.no)  

Krisztian Balog (krisztian.balog@uis.no)  

