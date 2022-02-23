# Language Translator

[LIVE DEVELOPMENT NOTEBOOK](https://seanvonb.github.io/language-translator/)

This project was part of my [Natural Language Processing Nanodegree](https://www.udacity.com/course/natural-language-processing-nanodegree--nd892), which I completed in late 2020. This particular Nanodegree – in fact, this particular *project* – had been my goal throughout my studies of machine learning. I was just so excited to work on it back then, and I'm still excited to share the work with you now. Machine translation has a long and fascinating history that involved [many](https://en.wikipedia.org/wiki/Rule-based_machine_translation) [different](https://en.wikipedia.org/wiki/Statistical_machine_translation) [approaches](https://en.wikipedia.org/wiki/Example-based_machine_translation) before the widespread commercial adoption of [Neural Machine Translation](https://en.wikipedia.org/wiki/Neural_machine_translation) (NMT) around 2016 or so. The following NMT pipeline, that I created with TensorFlow via Keras, reflects some of the most state-of-the-art practices from that time period, but it was already somewhat outdated when I built it in 2020, thanks largely to [Google Brain](https://research.google/teams/brain/)'s [Transformer](https://en.wikipedia.org/wiki/Transformer_(machine_learning_model)) model with attention.

The development notebook examines and preprocesses the data, tests a couple RNN architecture features, and finally assembles a bidirectional RNN model with embedding for training and prediction of English to French text, which reaches a pretty reasonable validation accuracy of 95% after just 10 training epochs.

## Features

-   Translate English text into French text
-	Create a pipeline that could be modified to translate between any languages
-	Test the performance difference between word IDs and embeddings
-	Test the performance difference and training needs of simple and bidirectional RNNs

## Credits

-   This project was part of [Udacity's Natural Language Processing Nanodegree](https://www.udacity.com/course/natural-language-processing-nanodegree--nd892).
-   Language data was provided by Udacity as a select subset of [WMT](https://www.statmt.org/)'s machine translation dataset.

## License

Copyright © 2020-2022 Sean von Bayern  
Licensed under the [MIT License](LICENSE.md)
