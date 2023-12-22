This project explores the NLP task of converting Text or Natural Language to Python Code. 
We tried to use Transfer learning on CodeT5-base (pre-trained model) and Fine-Tune our model on NL to Python code datasets and we can see amazing results.
The key idea is that we can see the importance of fine-tuning or the recency effect as the model starts producing astonishingly good code or results with proper indentation and minor mistakes.
This LLM just consisted of a 220M token model which is smaller than its competitors.
One of the key learnings has been the use of Mixed Precision Training(on GPUs) as it helps better manage resources for our training loop reducing the training time by approximately 50%.
The report for this paper/project is attached to the repository. Please refer [here](https://github.com/devyanimardia/Text_to_code/blob/main/Project%20Report%20-%20Team%205%20Final.pdf)
