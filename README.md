# Awesome Deep Learning [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![GitHub Sponsors](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/awesomelistsio) &nbsp; 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; 
[![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; 
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of awesome frameworks, libraries, tools, tutorials, research papers, and resources for deep learning. This list covers neural networks, model optimization, NLP, computer vision, and other deep learning applications.

## Contents

- [Frameworks and Libraries](#frameworks-and-libraries)
- [Tools and Utilities](#tools-and-utilities)
- [Neural Network Architectures](#neural-network-architectures)
- [Optimization and Training](#optimization-and-training)
- [Natural Language Processing (NLP)](#natural-language-processing-nlp)
- [Computer Vision](#computer-vision)
- [Generative Models](#generative-models)
- [Learning Resources](#learning-resources)
- [Research Papers](#research-papers)
- [Books](#books)
- [Community](#community)
- [Contribute](#contribute)
- [License](#license)

## Frameworks and Libraries

- [TensorFlow](https://www.tensorflow.org/) - An end-to-end open-source platform for machine learning and deep learning.
- [PyTorch](https://pytorch.org/) - A popular open-source deep learning framework that offers dynamic computation graphs.
- [Keras](https://keras.io/) - A high-level neural networks API, running on top of TensorFlow.
- [MXNet](https://mxnet.apache.org/) - A deep learning framework known for its efficiency and scalability.
- [JAX](https://jax.readthedocs.io/) - A library for high-performance numerical computing and automatic differentiation.
- [Caffe](https://caffe.berkeleyvision.org/) - A deep learning framework focused on convolutional neural networks (CNNs).
- [Theano](https://github.com/Theano/Theano) - A historical deep learning library for mathematical computations, now deprecated but influential.

## Tools and Utilities

- [TensorBoard](https://www.tensorflow.org/tensorboard) - A visualization toolkit for TensorFlow.
- [Weights & Biases](https://www.wandb.com/) - A tool for experiment tracking, model monitoring, and hyperparameter optimization.
- [PyTorch Lightning](https://www.pytorchlightning.ai/) - A lightweight PyTorch wrapper for scalable deep learning.
- [DeepSpeed](https://www.deepspeed.ai/) - An optimization library for training large deep learning models.
- [ONNX](https://onnx.ai/) - An open format to represent deep learning models, enabling interoperability across frameworks.

## Neural Network Architectures

- [Convolutional Neural Networks (CNNs)](https://cs231n.github.io/convolutional-networks/) - A popular architecture for image and video analysis.
- [Recurrent Neural Networks (RNNs)](https://www.coursera.org/learn/nlp-sequence-models) - A neural network architecture for sequence data, such as time series and text.
- [Long Short-Term Memory (LSTM)](https://colah.github.io/posts/2015-08-Understanding-LSTMs/) - A special type of RNN capable of learning long-term dependencies.
- [Transformers](https://arxiv.org/abs/1706.03762) - The architecture that introduced self-attention mechanisms and revolutionized NLP.
- [Autoencoders](https://www.deeplearningbook.org/) - Neural networks designed for unsupervised learning of efficient codings.
- [Graph Neural Networks (GNNs)](https://distill.pub/2021/gnn-intro/) - A type of neural network for learning from graph-structured data.

## Optimization and Training

- [Adam Optimizer](https://arxiv.org/abs/1412.6980) - An adaptive learning rate optimization algorithm.
- [Stochastic Gradient Descent (SGD)](https://towardsdatascience.com/stochastic-gradient-descent-with-momentum-a84097641a5d) - A popular optimization method for training deep learning models.
- [Batch Normalization](https://arxiv.org/abs/1502.03167) - A technique to stabilize and accelerate the training of deep networks.
- [Dropout](https://jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf) - A regularization technique to prevent neural networks from overfitting.
- [Learning Rate Schedulers](https://pytorch.org/docs/stable/optim.html#how-to-adjust-learning-rate) - Techniques to adjust the learning rate during training for better convergence.

## Natural Language Processing (NLP)

- [Hugging Face Transformers](https://huggingface.co/transformers/) - A library for state-of-the-art NLP models like BERT, GPT, and RoBERTa.
- [spaCy](https://spacy.io/) - An NLP library for fast processing of text data.
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding (2018)](https://arxiv.org/abs/1810.04805) - A transformer model for NLP tasks.
- [GPT-3: Language Models are Few-Shot Learners (2020)](https://arxiv.org/abs/2005.14165) - A large-scale generative language model.
- [Seq2Seq Models](https://arxiv.org/abs/1409.3215) - A neural network architecture for sequence-to-sequence learning tasks.

## Computer Vision

- [YOLO (You Only Look Once)](https://pjreddie.com/darknet/yolo/) - A state-of-the-art real-time object detection system.
- [ResNet: Deep Residual Learning for Image Recognition (2015)](https://arxiv.org/abs/1512.03385) - A neural network architecture known for its deep residual learning approach.
- [VGGNet](https://arxiv.org/abs/1409.1556) - A convolutional neural network known for its simplicity and performance in image classification.
- [DeepLab](https://github.com/tensorflow/models/tree/master/research/deeplab) - A model for semantic image segmentation.
- [Detectron2](https://github.com/facebookresearch/detectron2) - A high-performance framework for object detection and segmentation.

## Generative Models

- [GANs: Generative Adversarial Networks (2014)](https://arxiv.org/abs/1406.2661) - A model architecture for generating realistic data.
- [BigGAN: Large-Scale GAN Training for High-Fidelity Natural Image Synthesis (2018)](https://arxiv.org/abs/1809.11096) - A generative model for producing high-resolution images.
- [VAE: Variational Autoencoders (2013)](https://arxiv.org/abs/1312.6114) - A model architecture for generating data through variational inference.
- [StyleGAN](https://arxiv.org/abs/1812.04948) - A GAN model for high-quality image synthesis.
- [Diffusion Models](https://arxiv.org/abs/2006.11239) - A generative model framework for image synthesis.

## Learning Resources

- [Deep Learning Specialization on Coursera](https://www.coursera.org/specializations/deep-learning) - A series of courses by Andrew Ng on deep learning.
- [Stanford CS230: Deep Learning](https://cs230.stanford.edu/) - A comprehensive course on deep learning.
- [The Deep Learning Book](https://www.deeplearningbook.org/) - A foundational book by Ian Goodfellow, Yoshua Bengio, and Aaron Courville.
- [PyTorch Tutorials](https://pytorch.org/tutorials/) - Official tutorials for learning deep learning with PyTorch.
- [TensorFlow Tutorials](https://www.tensorflow.org/tutorials) - Official TensorFlow tutorials for building deep learning models.

## Research Papers

- [Attention Is All You Need (2017)](https://arxiv.org/abs/1706.03762) - The paper that introduced the Transformer architecture.
- [Deep Residual Learning for Image Recognition (2015)](https://arxiv.org/abs/1512.03385) - The introduction of ResNet.
- [Generative Adversarial Nets (2014)](https://arxiv.org/abs/1406.2661) - Ian Goodfellow’s original GAN paper.

## Books

- *Deep Learning* by Ian Goodfellow, Yoshua Bengio, and Aaron Courville - A comprehensive textbook on deep learning.
- *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron - A practical guide to deep learning.
- *Neural Networks and Deep Learning* by Michael Nielsen - An introduction to deep learning.

## Community

- [Reddit: r/MachineLearning](https://www.reddit.com/r/MachineLearning/) - A subreddit for discussing machine learning and deep learning.
- [PyTorch Forums](https://discuss.pytorch.org/) - A forum for discussing PyTorch-related topics.
- [TensorFlow Community](https://www.tensorflow.org/community) - A place for TensorFlow users to connect.

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
