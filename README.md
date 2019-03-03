
# Text-Classification---Sentence-Similarity
An approach for classification of text using Cosine Similarity

Here we measure the similarity between the sentences. 

## Goal :
To classify sentences of a "Scientific Paper" in abstract into Aim, Introduction , Background and Conclusion.  

## Steps :  

* Read a scientific paper and break the paper into different sections based on name of sections.  
  Ex -  Abstract, Background, Introduction, Method, Conclusion.  
* Summarize the text from different sections other than Abstract.  
* Tokenize the sentence in abstract. 
* Vectorization - Transform the text in document sections into a vector form.  
* Distance Computation - Compute the cosine similarity between the document vector.

## Cosine Similarity :

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size.  
Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.  
The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together.  
The smaller the angle, higher the cosine similarity.

## Example Paper : 

A_semantic-based_workflow_for_biomedical_literature_annotation.  

https://www.researchgate.net/publication/321763844_A_semantic-based_workflow_for_biomedical_literature_annotation

## Classification : 

Compared a sentence of abstract with introduction.
