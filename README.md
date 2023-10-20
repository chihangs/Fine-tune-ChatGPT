# Fine-tune-ChatGPT
## Fine-tune ChatGPT to Identify Fake News
1. Prepare data and convert to jsonl
2. Check data format / structure
3. Use OpenAI API to fine-tune model
### Quick Start: 
Use your own OpenAI API key in your environment variable or as hard-coding. 
Change the file IDs according to your own upload to OpenAI. Use fine-tuned model number of your own after fine-tuning.
### Notebooks:
fine_tune_ChatGPT.ipynb: preprocess data and fine-tune model by OpenAI API (validation test included)
fine_tune_use_evaluate.ipynb: use or evaluate the fine-tuned model

<img src="fine_tune_results.png?raw=true"/>

#### Data source: CNN.com, theOnion.com
