<div align="center">
    <h1>Awesome Data-Centric AI</h1>
    <img src="./static/dcai-full-RGB-2400px.png" style="width: 200px;"/>
</div>

# Table of Contents

- [Table of Contents](#table-of-contents)
- [Data Augmentation](#data-augmentation)
- [Data Cleansing](#data-cleansing)
- [Data Labeling](#data-labeling)
- [Data Selection](#data-selection)
- [End of modelitis](#end-of-modelitis)
- [Self-Supervision](#self-supervision)
- [Case studies](#case-studies)

# Data Augmentation

General:

- 2021-CVPR - Augmentation Strategies for Learning with Noisy Labels. [Paper](https://arxiv.org/abs/2103.02130) [Code](https://github.com/KentoNishi/Augmentation-for-LNL)
- Fast AutoAugment. In comparison to AutoAugment, the proposed algorithm speeds up the search time by orders of magnitude. [paper](https://arxiv.org/pdf/1905.00397.pdf) [code](https://github.com/kakaobrain/fast-autoaugment)

Image:

- CutMix. It pastes a random patch from one image onto the other and updates the label to be weighted sum of the two image labels proportional to the size of the cutouts. [Paper](https://arxiv.org/abs/1905.04899) [Code](https://github.com/clovaai/CutMix-PyTorch)
- ReMixMatch. It extends image augmentation to a semi-supervised setup. [Paper](https://arxiv.org/abs/1911.09785) [Code](https://github.com/google-research/remixmatch)

Text:

- Neighbors in a word embedding space [Paper](https://aclanthology.org/D15-1306.pdf) [Code](https://github.com/makcedward/nlpaug)
- Probable words according to a language model that takes the sentence context into account [Paper](https://aclanthology.org/N18-2072.pdf) [Code](https://github.com/pfnet-research/contextual_augmentation)
- Backtranslation [Paper](https://arxiv.org/abs/1904.12848) [Code](https://github.com/google-research/uda)

Audio:

- Audio Augmentation for Speech Recognition [paper](https://www.danielpovey.com/files/2015_interspeech_augmentation.pdf)  [code](https://github.com/iver56/audiomentations)


# Data Cleansing

- Generalized Label Shift Correction via Minimum Uncertainty Principle: Theory and Algorithm [Paper](https://arxiv.org/pdf/2202.13043.pdf)
- Resolving label uncertainty with implicit posterior models, a method for jointly inferring labels across a collection of data samples, where each sample consists of an observation and a prior belief about the label [Paper](https://arxiv.org/abs/2202.14000)
- [A Realistic Simulation Framework for Learning with Label Noise](https://arxiv.org/pdf/2107.11413v1.pdf) and [code](https://github.com/deepmind/deepmind-research/tree/master/noisy_label)
- [A Survey on Deep Learning with Noisy Labels: How to train your model when you cannot trust on the annotations?](https://arxiv.org/abs/2012.03061) and [code](https://github.com/filipe-research/tutorial_noisylabels)
- From cleaning before ML to cleaning for ML - Félix Neutatz, Research Associate at Technische Universität Berlin
  https://youtu.be/RN8zpdIO4f4
- 2021-CVPR - Jo-SRC: A Contrastive Approach for Combating Noisy Labels. [Paper](https://arxiv.org/abs/2103.13029) [Code](https://github.com/NUST-Machine-Intelligence-Laboratory/Jo-SRC)
- 2020 - Learning from Noisy Labels with Deep Neural Networks: A Survey. [Paper](https://arxiv.org/abs/2007.08199)


# Data Labeling

- [Human in the loop: Lessons learned from AI projects in enterprise - Khemon Beh, Managing Data Scientist at Capgemini](https://youtu.be/qyTC8PSPuAw)
- [Learning Language-Conditioned Robot Behavior from Offline Data and Crowd-Sourced Annotation](https://arxiv.org/abs/2109.01115) - Stanford University paper detailing a method to use crowdsourced language descriptions of videos to train robots on different tasks

# Data Selection

- [Group fairness: recent developments and challenges - Evgenii Chzhen, Research scientist at CNRS/Université Paris-Saclay](https://youtu.be/0AEzkyYVk_s)
- [Human-in-the-Loop Machine Learning - Robert Munro](https://www.amazon.fr/Human-Loop-Machine-Learning/dp/1617296740)

# End of modelitis

- [Changing the world by changing the data](https://bit.ly/3HoNDXJ) and [video](https://youtu.be/rh7eV8KZEZ4) - Anna Rogers, Postdoctoral Researcher at the University of Copenhagen
- [Why and how to care about ML ethics - Clement Delangue, Hugging Face CEO and co-founder](https://youtu.be/ZflLClLnnLw)
- [Limitations of Autoregressive Models and Their Alternatives - Chu-Cheng Lin, Research Assistant at Carnegie Mellon University](https://youtu.be/SCanHYvPRvY)

# Self-Supervision

- [FNet: Mixing Tokens with Fourier Transforms](https://arxiv.org/abs/2105.03824) - Transformer encoder architectures can be sped up, with limited accuracy costs, by replacing the self-attention sublayers with simple linear transformations that "mix" input tokens.
- [Resources for multilingual NLP in the neural era: the examples of OSCAR and CamemBERT](https://youtu.be/5T-TxQqAYJo) - Benoît Sagot, Research Director at Inria
- [Training language models to follow instructions with human feedback](https://cdn.openai.com/papers/Training_language_models_to_follow_instructions_with_human_feedback.pdf) - OpenAI paper detailing InstructGPT, a transformer model that surpassed GPT-3 in following natural language instructions and is claimed to be less toxic
- 2021-MM - Co-learning: Learning from Noisy Labels with Self-supervision. [Paper](https://arxiv.org/abs/2108.04063) [Code](https://github.com/chengtan9907/co-training-based_noisy-label-learning)
- data2vec: A General Framework for Self-supervised Learning in Speech, Vision and Language [paper](https://ai.facebook.com/research/data2vec-a-general-framework-for-self-supervised-learning-in-speech-vision-and-language) [code](https://github.com/pytorch/fairseq/tree/main/examples/data2vec)


# Case studies

- [Augmenting bladder cancer diagnostic utilizing unstructured data](https://youtu.be/1SlO5UdYL28) - Thibaut Troude, CTO at VitaDX. How to integrate create a feedback loop between annotation and training models.
- [The role of data in end-to-end learned autonomy - Fergal Cotter, Head of the Perception team at Wayve](https://youtu.be/0Dt0lHLaAX0)
