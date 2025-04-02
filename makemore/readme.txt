This file contains my implementation of the models inspired by Andrej karpathy's makemore project: https://github.com/karpathy/makemore/blob/master/README.md
The project focuses on building autoregressive character-level language models that generate text resembling the input data.
Here we use the names.txt dataset which contains around 32,000 names where each name is treated as a sample and the model tries to generate name-like words.


The following neural network architectures have been implemented, each corresponding to foundational research papers:

- **Bigram Model** : Predicts the next character based on the previous one using a simple look up table of counts.
- **Multilayer Perceptron (MLP)** : following [Bengio et al. 2003](https://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf).
- **Recurrent Neural Network (RNN)** : following [Mikolov et al. 2010](https://www.fit.vutbr.cz/research/groups/speech/publi/2010/mikolov_interspeech2010_IS100722.pdf) (in progress...)
- **Long Short-Term Memory (LSTM)**: following [Graves et al. 2014](https://arxiv.org/abs/1308.0850) (in progress...)
- **Gated Recurrent Unit (GRU)**: following [Kyunghyun Cho et al. 2014](https://arxiv.org/abs/1409.1259) (in progress...)
- **Transformer**: following [Vaswani et al. 2017](https://arxiv.org/abs/1706.03762) (in progress...)
 
