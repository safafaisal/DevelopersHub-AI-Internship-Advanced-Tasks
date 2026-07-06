# News Topic Classifier Using BERT

Fine-tuned `bert-base-uncased` to classify news headlines into 4 categories: 
**World, Sports, Business, Sci/Tech**, using the AG News dataset.

## Dataset
[AG News](https://huggingface.co/datasets/fancyzhx/ag_news) — sourced from Hugging Face Datasets

## Results
- Trained on 8,000 examples, validated on 2,000, tested on 7,600 (unseen)
- **Test Accuracy: 91.72%**
- **Test F1-score: 91.72%**
- Most confusion occurs between Business and Sci/Tech (realistic overlap in real news)

## Tech Stack
- Hugging Face Transformers (BERT)
- PyTorch
- scikit-learn (evaluation)
- Gradio (deployment)

## Demo
Deployed with Gradio for live headline classification. Try example headlines and see 
predicted category in real time.
