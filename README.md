# manchu-mt

### Manchu-English Machine Translation

- course: Neural Networks and Deep Learning
- author: Christy Hsu

This project consider machine translation in a low resource setting: Manchu-English. Using a small parallel corpus, I experimented with baseline Seq2Seq model, transfer learning and LLM in-context learning.

### Data

- Manchu-English parallel sentence pairs
- Manchu-English dictionary entries used as lexical information
- Train, validation, and test splits for hyper-parameter selection and performance evaluation

### Methods

- Trained stacked GRUs with attention
- Used the pretrained ManchuBERT language model for transfer learning
- Evaluated translation quality using sentence BLEU
- Experimented with LLM in-context learning with prompting assisted with dictionary entries as an alternative approach for low-resource translation
