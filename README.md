# Combating-Human-Trafficking-via-Automatic-OSINT-Collection
Combating Human Trafficking via Automatic OSINT Collection, Validation and Fusion

One of the major challenges in combating global human trafficking is the availability of actionable intelligence about trafficking events and operations. The lack of timely and structured data has always been the bottleneck in the analysis and mitigation of human trafficking. In this work, we aim to address this issue by developing an automated pipeline based on recent advances in natural language processing and machine learning to streamline the curation, analysis, and extraction of actionable intelligence from multi-sourced news media as Open-Sources of Intelligence (OSINT). In our solution, we utilize and enhance the BERT Question Answering language model for information extraction from unstructured text of the news. Furthermore, we develop algorithms for measuring the relevance and novelty of curated news articles to reduce the computation cost and redundant processing. Moreover, we evaluate the proposed pipeline on a dataset of annotated news articles containing actionable intelligence about victims and perpetrators of human trafficking.



# 1. Countries in which LoveJustice Work
country_list=[" ","Nepal", "India", "Bangladesh", "South Africa",
              "Zimbabwe", "Malawi", "Kenya", "Uganda", "Benin", 
              "Tanzania"," Sierra Leone", "Ghana",
              "Rwanda", "Namibia",  "Cambodia"]
# 2. Top keywords from overall collected news articles' 
searchPhrases=['human trafficking ',
               'child trafficking',
               'labor trafficking',
               'women rescued, trafficking',
               'children rescued, trafficking',
               'girls rescued, trafficking',
               'child traffickers arrested'
               'human trafficking suspect',
               'human traffickers arrested'
               ]
