# Take Inspo

**Take Inspo** is a simple generative model that learns from a text dataset and creates new outputs inspired by it. The project takes a single text file as input, where each line represents one training example, and generates new samples that resemble the patterns found in the dataset.

At its core, **Take Inspo** is an autoregressive character-level language model. It learns the statistical structure of the training data and predicts one character at a time to produce entirely new sequences. Depending on the implementation, the underlying model can range from simple bigrams to advanced Transformer architectures similar to those used in GPT.

The name **Take Inspo** reflects its purpose—it doesn't copy the dataset but instead **takes inspiration from it** to create original content. For example:

* Train it on a list of baby names to generate fresh, realistic-sounding names.
* Train it on company names to brainstorm unique startup or brand names.
* Train it on a dictionary of words to produce English-like gibberish that follows the language's character patterns.

Rather than being a large, feature-heavy library with countless configuration options, **Take Inspo** is designed to be lightweight, easy to understand, and highly hackable. The codebase is intentionally kept simple, making it an excellent educational project for anyone interested in learning how modern language models work from the ground up.

The only required dependency is **PyTorch**.
