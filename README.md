# Hierarchical Attention Networks for Document Classification

### Getting Started
To install all libraries/dependencies used in this project, run
```bash
brew install graphviz
pip3 install -r requirement.txt
```

For Windows or Linux users, it is recommended to use [Conda](https://docs.conda.io/en/latest/) to install [graphviz](https://graphviz.org/) in order to save model structures to `.png` files.

`preprocess.ipynb` generates training, validation, test data, tokenizer, and word embedding weights. `model.ipynb` trains, saves, and evaluates models with words' and sentences' weights visualization. Slight modifications were made in `model.ipynb` as compared to the original paper settings.