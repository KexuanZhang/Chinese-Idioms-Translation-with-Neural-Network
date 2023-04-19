# Chinese-Idioms-Translation-with-Neural-Network
**This is a project for the course CSC413 2023 Winter, taught by Jimmy Ba and Bo Wang, at the University of Toronto, produced by Kexuan Zhang and William Zhang**

With the advent of large language models like GPT-3, BERT, we have achieved remarkable performance in natural language processing. However, when it comes to the task regarding picking up the underlying meanings, most of the language models fail to maintain a good accuracy. One such example is the translation of idiom in Chinese language which has a compact representation (normally 4 characters), while contains deep-seated metaphorical meanings. Therefore, in this project, we fine-tuned two pre-trained models, Davinci and M2M100, to perform language translation that aims to pick up the underlying meanings of Chinese idioms, and then analyze the performance of each based on various metrics: BLEU, METEOR, and COMET.

## Quick Guide
- The Models folder contains the ipynb files that demonstrate the process of fine-tuning Davinci and M2M100 models 
- The Evaluation folder contains the ipynb file that demonstrate the process of testing the two fine-tuned model, and calculate BLEU, METEOR, and COMET metrics
- The link to the dataset we use to train the models: [PETCI data](https://raw.githubusercontent.com/kt2k01/petci/main/data/json/filtered.json)
- The report file is the paper that summarize this project
