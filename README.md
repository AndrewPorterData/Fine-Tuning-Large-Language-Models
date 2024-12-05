# Fine-Tuning-Large-Language-Models
Fine tuning large language models for text classification within niche domains (as part of my final MSc project).
The focus of my work was to fine tune large language models which had been trained on a wealth of unlabelled data for text classification in niche domains with relatively smaller datasets. This is the prevalent methodology in contemporary automated text classification. The domain selected was video game 'loot box' purchasing reasons in survey responses. The aim was to allow researchers to streamline manual categorisation of responses. 
In recent years, we have seen drastic developments in Natural Language Processing (NLP), particularly with the development of various transformer-based deep learning models. As such, these models are being applied to a host of varied text classification tasks across a host of varied industries. My paper investigated the efficacy of language model automated qualitative data analysis within a niche domain, loot-box survey responses. I fine-tuned three pre-trained language models for this context: ELECTRA, RoBERTa, and XLNet. Furthermore, I explored the use of GPT-4 for classification and dataset augmentation, although I have not included this part of the research here. My intention was to highlight both the potential and challenges of applying these models and techniques to these fields with unique, varied qualitative data, domain-specific jargon, polysemy and ambiguous sentiment.
The code included in this repository is the final forms of these models, modified for this domain with the inclusion of additional layers and regularisation techniques. Furthermore, the data used is the result of extensive data collection, manipulation/augmentation and uncertain sample handling; all of which is discussed in detail in the paper.
