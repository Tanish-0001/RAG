RAG model that uses the university's SI and Placement chronicles to answer a related query.

The question is first decomposed into 5 related sub-questions. HyDE (Hypothetical Document Embedding) is used to retrieve context in order to answer each sub-question. Finally, each sub-question and its answer is used as context to answer the main question.
