Goal: Determine which pre-trained embedding model would be most effective in our project on KGs. 

Models Considered:  
* MedBERT
  Paper: https://arxiv.org/abs/2005.12833   
  Con: Trained on patient EHR data. We will be passing in medical concepts, so being fine tuned to patient symptoms/conditions isn’t aligned with our inputs. On the other hand, EHR data can provide a wider and more diverse source of information compared to medical data
* ClinicalBERT <br />
  Paper: https://arxiv.org/abs/1904.03323   
  Pro: Trained on medical data such as medical conditions, treatments, clinical data, which is more in line with our purposes than MedBERT and SMedBERT.    
* SMedBERT  
  Paper: https://arxiv.org/abs/2108.08983   
  Con: Was trained on Chinese medical data. The paper mentions that you can train their model on English data as well, but I am having difficulty finding the exact way to do so.   
* PubMedBERT      
  Paper: https://arxiv.org/pdf/2007.15779.pdf   
  Pro: Trained on a collection of PubMed abstracts. This is similar to what we will be passing into the embedding model.   
* BioLinkBERT   
  Paper: https://arxiv.org/pdf/2203.15827.pdf   
    Note: This paper is generally on LinkBERT, but there is a specific version for the biomedical domain located here: https://huggingface.co/michiyasunaga/BioLinkBERT-large   
  Pro: Visualizes a set of documents as a graph, utilizing links (either hyperlinks, or links based on lexical or topical similarity between documents) to generate connections between concepts. It then processes these relationships to create the contextualized embeddings. This seems most similar in structure to what we will be passing into the embeddings (the KG, its nodes).   

The BLURB (https://microsoft.github.io/BLURB/models.html) leaderboard evaluates various embedding models on six different tasks within the biomedical domain, including named entity recognition, relation extraction, etc. It appears that BioLinkBERT has better performance on the various tasks compared to PubMedBert and ClinicalBERT. MedBERT and SMedBERT are trained on data that aren’t aligned with our specific tasks, so it seems that BioLinkBERT is more ideal compared to those two methods.      

Future Steps: Implement these various embedding models and then compare their performance based on how they represent connections between topics and how effective they are at determining synonyms. 

