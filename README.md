<p align="center"><strong>An Automated AI Coding Approach for Autobiographical Memory Research</strong></p>

This repository is for the AI coding project at Con Amore, Aarhus University.

- The prompts used in our AI coding project can be found in the Supplemental Material of the article.  
- The Python code for executing the fine-tuning job and model performance evaluation can be found in the notebook files: 'AI_coding.ipynb'.
- The folder "synthetic data" contains datasets with synthetic memory examples. They are designed to illustrate the structure and the format of training, validation, and test datasets used in the coding-moral-theme and coding-moral-role fine-tuning jobs.
- You can use the synthetic datasets to run the code. However, they are not intended to train a functional model. We provide the synthetic data examples because the data used in the current research can not be publicly shared due to GDPR.


Before running the code:  
- First, export your OPENAI API key as an environment variable in your terminal as instructed on the OpenAI website: https://platform.openai.com/docs/libraries.  
- Second, run the following commands in the terminal to install OpenAI and the required packages:

```bash

python.exe -m pip install --upgrade pip 

pip install openai    

pip install -r install_packages.txt
```


If you have any questions regarding this project, feel free to contact: jiaqi@psy.au.dk.
