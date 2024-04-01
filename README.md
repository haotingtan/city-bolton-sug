# GSoC City of Boston Model Improvement Suggestion

## 1. Data Quality and Augmentation
* **Increase Dataset Size:** More data can help the model learn a broader vocabulary and more complex sentence structures. 
* **Data Cleaning:** Ensure the dataset is clean and free of errors. For example, correcting typos, removing duplicates, or ensuring the translations are accurate.
* **Data Augmentation:** Translate from English to Spanish then tranlste back to English using Spanish sentence just generated to see if matches.
  
## 2. Hyperparameter Tuning
* **Learning Rate:** Adjust the learning rate and learning rate schedule. Sometimes, a lower learning rate with a decay over time can lead to better convergence.
* **Batch Size and Epochs:** Experiment with different batch sizes and numbers of epochs. A larger batch size can provide more stable gradients, while more epochs give the model more time to learn.
