# Re-thinking Model Inversion Attacks Against Deep Neural Networks
<p align="center">
 <a href="thibaongoc_nguyen@mymail.sutd.edu.sg">Ngoc-Bao Nguyen(*),</a> |
 <a href="keshigeyan@sutd.edu.sg">Keshigeyan Chandrasegaran (*)</a> |
 <a href="milad_abdollahzadeh@sutd.edu.sg">Milad Abdollahzaden</a> |
 <a href="ngaiman_cheung@sutd.edu.sg">Ngai-Man Cheung</a> 
 </p>
<!-- [Ngoc-Bao Nguyen(*)](thibaongoc_nguyen@mymail.sutd.edu.sg), [Keshigeyan Chandrasegaran (*)](keshigeyan@sutd.edu.sg), [Milad Abdollahzaden](milad_abdollahzadeh@sutd.edu.sg), [Ngai-Man Cheung](ngaiman_cheung@sutd.edu.sg) -->
<p align="center">
Singapore University of Technology and Design (SUTD) 
</p>
<p align="center">
<a href="https://github.com/ngoc-nguyen-0/Re_thinking_MI">Paper</a> |
<a href="https://github.com/ngoc-nguyen-0/Re_thinking_MI">Github</a> 

</p>
 <p align="center">
    <img width="1000" src="./docs/assets/docs/framework_v3_page-0001.jpg" alt="Our proposed method">
</p>

<h1 align="center">Abstract</h1>

Model inversion (MI) attacks aim to infer and reconstruct private training data by abusing access to a model. MI attacks have raised serious concerns of leaking of sensitive information (e.g. private face images used in training a face recognition system). Recently, several algorithms
for MI have been proposed to improve the attack performance. In this work, we revisit MI, study two fundamental issues pertaining to all state-of-the-art (SOTA) MI algorithms, and propose solutions to these issues which lead to
significant boost in attack performance for all SOTA MI. In particular, our contributions are 2-fold: (1) We analyze the optimization objective of SOTA MI algorithms, argue
that the objective is sub-optimal for achieving MI, and propose an improved optimization objective which boosts attack performance significantly. (2) We analyze “MI overfitting”, show that it would prevent reconstructed images from
learning semantics of training data, and propose a novel “model augmentation” idea to overcome this issue. Our proposed solutions are simple and improve all SOTA MI attack accuracy significantly. E.g., in the standard CelebA
benchmark, our solutions improve accuracy by 11.8% and achieve for the first time over 90% attack accuracy. Our results highlight rising threats based on MI and prompt serious consideration on privacy of machine learning


