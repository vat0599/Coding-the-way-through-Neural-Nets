# Coding-the-way-through-Neural-Nets

## A small talk:
This repository contains my learnings of neural networks since I started learning about them in 2018 and tried visualizing them through coding. I believe the best way to learn something is by actually having a hands-on experience. We generally have one idea while programming, but end up getting multiple errors. These errors generally help us in understanding quite a lot more than what we planned and helps us more than what we expected. Thus on that note, I have tried to hard code a lot of concepts from scratch using basic numpy implementation. Many worked after a lot of effort and I thought of sharing my work to the community, so that new learners have a better understanding of the building blocks of neural nets.

It is a general practice to download a pretrained network on a famous dataset and get a pinnacle accuracy, but this process heavily limits us to tweak the model and understand the foundation. The math is not completely understood in implementing models from pytorch or tensorflow, or even how a simple gradient descent and optimizers like SGD, Adam work. Thus this repository covers from scratch to finally implementing models from torch (because these models are super optimized and necessary when we go to bigger tasks). The idea is to understand the math and how things work in neural net before jumping to direct application of torch models. I have to thank Ian Goodfellow's book of Deep Learning from which I gained theoretical knowledge about DL, and countless medium blogs and ofcourse the best teacher Youtube (seriously world is a better place because of you xD), finally Stack Overflow for my uncountable error support.

This is my entire work from 2018 until now, a small collection having basic implementations of key concepts of DL. I'll be adding if I implement any tutorial related material, into this repository. All the contents will be mostly in PyTorch because I am most comfortable with it.

## Order of uploads (Please learn in the same order because many notebooks are related to the previous notebooks):
1. [Vectors.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/Vectors.ipynb) - explains blahhhhh
2. [MPNeuronAndPerceptron.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/MPNeuronAndPerceptron.ipynb)
3. [SigmoidNeuron.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/SigmoidNeuron.ipynb)
4. [SigmoidNeuron_RealWorldData.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/SigmoidNeuron_RealWorldData.ipynb) (keep mobile_cleaned.csv in same directory)
5. [FeedForwardNetwork_new.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/FeedForwardNetwork_new.ipynb) (check out FFNetworkMultiClass.png, FFNetworkSingle.png, SimpleNetwork.png for understanding the architecture implemented)
6. [ScalarBackpropagation.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/ScalarBackpropagation.ipynb) (check out FirstNetwork.png, SecondNetwork.png for understanding the architecture implemented)
7. [VectorizedFeedForwardNetworks.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/VectorizedFeedForwardNetworks.ipynb) (check out FirstNetwork.png, SecondNetwork.png for understanding the architecture implemented)
8. [GDAlgorithms.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/GDAlgorithms.ipynb)
9. [GDAlgorithms_cont.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/GDAlgorithms_cont.ipynb)
10. [VectorizedGDAlgorithms.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/VectorisedGDAlgorithms.ipynb)
11. [InitialisationActivationFunctions.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/InitialisationActivationFunctions.ipynb)
12. [OverfittingAndRegularisation.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/OverfittingAndRegularisation.ipynb)
13. [PytorchIntro.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/PytorchIntro.ipynb)
14. [FFNetworksWithPyTorch.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/FFNetworksWithPyTorch.ipynb)
15. [PyTorchCNN.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/PyTorchCNN.ipynb)
16. [LargeCNNs.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/LargeCNNs.ipynb)
17. [CNNVisualisation.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/CNNVisualisation.ipynb) (keep data.zip in same directory)
18. [BatchNorm_Dropout.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/BatchNorm_Dropout.ipynb)
19. [HyperparameterTuning_MLFlow.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/HyperparameterTuning_MLFlow.ipynb)
20. [RNNs.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/RNNs.ipynb) (keep name2lang.txt)
21. [BatchSeqModels.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/BatchSeqModels.ipynb)
22. [EncoderDecoderArchitecture.ipynb](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/blob/main/EncoderDecoderArchitecture.ipynb) (keep NEWS2012RefEnHi.xml, NEWS2012TrainingEnHi.xml in same directory)

## Contributions
Do not hesitate to contribute by [filling an issue](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/issues) or [a PR](https://github.com/vat0599/Coding-the-way-through-Neural-Nets/pulls) !
