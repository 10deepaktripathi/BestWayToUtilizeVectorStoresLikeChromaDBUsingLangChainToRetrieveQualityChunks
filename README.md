# BestWayToUtilizeVectorStoresLikeChromaDBUsingLangChainToRetrieveQualityChunks
Notebook contain code related to how to chunk yourknowedge base and store that in a VectoreStore. Once done, how to untilize different ways of querying the vectorstore for most relevent chunk retrieval.

# Task Description:

In this assignment you are asked to build a semanic search engine, able to search a collecion of PDF documents on a paragraph-by-paragraph basis. To achieve this goal, you should use Python, the SentenceTransformers library (https://www.sbert.net/) and any other generally accessible Python libraries. Your code should allow to:

    Download k PDFs from hAps://arxiv.org following a user- specified search query and chunk them into individual paragraphs
    Encode/embed each paragraph using SentenceTransformers and store these encodings
    Search for the paragraphs most relevant to a user-specified query and show the results
    For bonus points, perform topic modelling on the paragraphs and present the results

