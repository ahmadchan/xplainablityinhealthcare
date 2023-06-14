Working on these things...

1. Our Idea is to provide a paltform which can take an input and can automatically create a Knowledge Graph within few seconds-->Web Application with user Interface.
2. The Graph will be created in all formats such RDF-->(Rescoure Description Framework), OWL-->(Web Ontology Language), XML, CSV, Cypher, etc.  (We can do that in cypher right now).
3. There will be lot of duplicates and it is expected to have enrichment in multiple languages--> Using the translator Libraries and just skip if you can't.
4. For Duplicates we are currently exploring the pre-trained embeddings--> Using literature and observations we will set a threshold. These embeddings will also be used for finding unknown connections among Nodes of Knowledge Graph.
5. Riahana and I are working on testing these pretrained embeddings and finding a way to fine-tune them maybe for specific medical side--> ClinicalBERT, MedBERT, SMedBERT, PubMedBERT, BioLinkBERT.
6. After finding the best one, we will complete the first flow of Graph Creation and will start the creation of web application--> Meanline will enhance each step--> Increase the ontologies, Graph creation in mutiple formats, deep learning methods for finding the best connections for answering multiple questions, etc.
7. Exploring the KG embeddings will be Next step...
![5th_paper](https://github.com/bukharilab/xplainablityinhealthcare/assets/45236572/e96687e8-b649-4733-8aba-2c7693614626)

