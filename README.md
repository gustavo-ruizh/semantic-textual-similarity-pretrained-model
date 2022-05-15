# Semantic textual similarity with pretrained model

This project performs an STS task using the Sentence-Transformer framework for sentence embeddings (see more at https://www.sbert.net/).

The corpus used in this project is the wiki-split dataset found on HuggingFace (see https://huggingface.co/datasets/wiki_split), with a few modifications, noted in the Jupyter Notebook file.

The pre-trained model chosen for this project was the sentence-transformers/all-distilroberta-v1 from HuggingFace, a Pytorch model which maps sentences & paragraphs to a 768 dimensional dense vector space and can be used for tasks like clustering or semantic search (see https://huggingface.co/sentence-transformers/all-distilroberta-v1).
