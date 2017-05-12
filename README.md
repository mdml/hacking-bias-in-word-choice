# Hacking bias in word choice

This is a preliminary version of a tool to help you discover gender bias in your text. All you have to do is type or paste your text in the box below. Our algorithm will then alert you if any of your word choices are associated with gender by highlighting the words in your text that are "close" to a "male" or "female" direction in the [https://www.tensorflow.org/tutorials/word2vec](word2vec) word embedding. Blue words are stereotypically male, and pink words are stereotypically female (we are aware this is a stereotype in its own right). Ideally you can improve your text by rewriting it to avoid gender biased words.

This tool was built at the 2017 [Hacking Bias in Machine Learning hackathon](https://www.eventbrite.com/e/new-england-machine-learning-hackathon-hacking-bias-in-ml-tickets-32951771636?aff=NEML).

### Usage

Visit [https://mdml.github.io/hacking-bias-in-word-choice/](https://mdml.github.io/hacking-bias-in-word-choice/), or clone this repository and run a web server in the root of the repository (e.g. Python's [`SimpleHTTPServer`](https://docs.python.org/2/library/simplehttpserver.html)).

### Contributors
* Elena Jakubiak
* Elliot Creager
* Himtanaya Bhadada
* Jason Cardinal
* Kai-wei Chang
* Max Leiserson
* Purva Kamat
* Roman Lutz
* Shana Opperman
