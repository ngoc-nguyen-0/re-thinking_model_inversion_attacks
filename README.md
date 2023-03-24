Model inversion (MI) attacks aim to infer and reconstruct private training data by abusing access to a model. MI attacks have raised serious concerns of leaking of sensitive information (e.g. private face images used in training a face recognition system). Recently, several algorithms
for MI have been proposed to improve the attack performance. In this work, we revisit MI, study two fundamental issues pertaining to all state-of-the-art (SOTA) MI algorithms, and propose solutions to these issues which lead to
significant boost in attack performance for all SOTA MI. In particular, our contributions are 2-fold: (1) We analyze the optimization objective of SOTA MI algorithms, argue
that the objective is sub-optimal for achieving MI, and propose an improved optimization objective which boosts attack performance significantly. (2) We analyze “MI overfitting”, show that it would prevent reconstructed images from
learning semantics of training data, and propose a novel “model augmentation” idea to overcome this issue. Our proposed solutions are simple and improve all SOTA MI attack accuracy significantly. E.g., in the standard CelebA
benchmark, our solutions improve accuracy by 11.8% and achieve for the first time over 90% attack accuracy. Our results highlight rising threats based on MI and prompt serious consideration on privacy of machine learning


[Paper](https://github.com/ngoc-nguyen-0/Re_thinking_MI)
[Code](https://github.com/ngoc-nguyen-0/Re_thinking_MI)
