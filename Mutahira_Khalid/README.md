Working on these things...

1. Our Idea is to provide a paltform which can take an input and can automatically create a Knowledge Graph within few seconds-->Web Application with user Interface.
2. The Graph will be created in all formats such RDF-->(Rescoure Description Framework), OWL-->(Web Ontology Language), XML, CSV, Cypher, etc.  (We can do that in cypher right now).
3. There will be lot of duplicates and it is expected to have enrichment in multiple languages--> Using the translator Libraries and just skip if you can't.
4. For Duplicates we are currently exploring the pre-trained embeddings--> Using literature and observations we will set a threshold. These embeddings will also be used for finding unknown connections among Nodes of Knowledge Graph.
5. Riahana and I are working on testing these pretrained embeddings and finding a way to fine-tune them maybe for specific medical side--> ClinicalBERT, MedBERT, SMedBERT, PubMedBERT, BioLinkBERT.
6. After finding the best one, we will complete the first flow of Graph Creation and will start the creation of web application--> Meanline will enhance each step--> Increase the ontologies, Graph creation in mutiple formats, deep learning methods for finding the best connections for answering multiple questions, etc.
7. Exploring the KG embeddings will be Next step...
![5th_paper](https://github.com/bukharilab/xplainablityinhealthcare/assets/45236572/e96687e8-b649-4733-8aba-2c7693614626)

Possible venues to submit to:
* 20th IEEE Conference on Computational Intelligence in Bioinformatics and Computational Biology (https://cmte.ieee.org/cis-bbtc/cibcb2023/)
  *   Conference is on August 29-31, 2023. Short papers are due *July 2nd*. 
* 15th Annual Conference on Bioinformatics Models, Methods, and Algorithms (https://bioinformatics.scitevents.org)
  *   Conference is on February 21st-23rd, 2023. Regular paper submission due *October 9th*, abstracts due *January 1st*
* The 38th Annual AAAI Conference on Artificial Intelligence (https://aaai.org/aaai-conference/#)
  *   The special track on robust and safe AI appears to be most suitable for this project. Conference is on February 20-27, 2024. Abstracts due *August 8th*, papers due *August 15th*
* 22nd International Conference on Machine Learning and Applications (https://icmla-conference.org/icmla23/keydates.html)
  *   Conference is on December 15-17, 2023. Main conference papers due *July 15th*
* 18th International Conference on Emerging Technologies (https://www.icet.org.pk/2023/index.php)
  *   Conference is on November 6-7, 2023. Papers due *July 28th*
* 35th IEEE International Conference on Tools with Artificial Intelligence (https://ictai.computer.org/2023/)
  *   Conference is on November 6-8, 2023. Papers due *June 25th*

Here are some conferences which have not been updated yet for 2024 or are currently ongoing, but I think might be valuable to look at in the future since they align with our project well. 
* The 11th IEEE International Conference on Healthcare Informatics (https://ieeeichi.github.io/ICHI2023/)
* IEEE Conference on Secure and Trustworthy Machine Learning (https://satml.org/#)
