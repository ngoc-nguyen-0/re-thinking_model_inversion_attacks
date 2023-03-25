<h1 align="center">Re-thinking Model Inversion Attacks Against Deep Neural Networks</h1>
<p align="center">
 <a href="mailto: thibaongoc_nguyen@mymail.sutd.edu.sg">Ngoc-Bao Nguyen(*),</a> |
 <a href="mailto: keshigeyan@sutd.edu.sg">Keshigeyan Chandrasegaran(*)</a> |
 <a href="mailto: milad_abdollahzadeh@sutd.edu.sg">Milad Abdollahzaden</a> |
 <a href="mailto: ngaiman_cheung@sutd.edu.sg">Ngai-Man Cheung</a> 
 </p>
<p align="center">
Singapore University of Technology and Design (SUTD) 
</p>
<p align="center">
<a href="https://github.com/ngoc-nguyen-0/Re_thinking_MI">Paper</a> |
<a href="https://github.com/ngoc-nguyen-0/Re_thinking_MI">Github</a> 
</p>

<p style="center">
<img width="1000" src="./docs/assets/images/framework_v3_page-0001.jpg">
</p>

<h2 align="center">Abstract</h1>
<table align="center" width="850px">
<tbody>
<tr><td>
Model inversion (MI) attacks aim to infer and reconstruct private training data by abusing access to a model. MI attacks have raised concerns about the leaking of sensitive information (e.g. private face images used in training a face recognition system). Recently, several algorithms for MI have been proposed to improve the attack performance. In this work, we revisit MI, study two fundamental issues pertaining to all state-of-the-art (SOTA) MI algorithms, and propose solutions to these issues which lead to a significant boost in attack performance for all SOTA MI. In particular, our contributions are two-fold: 1) We analyze the optimization objective of SOTA MI algorithms, argue that the objective is sub-optimal for achieving MI, and propose an improved optimization objective that boosts attack performance significantly. 2) We analyze “MI overfitting”, show that it would prevent reconstructed images from learning semantics of training data, and propose a novel “model augmentation” idea to overcome this issue. Our proposed solutions are simple and improve all SOTA MI attack accuracy significantly. E.g., in the standard CelebA benchmark, our solutions improve accuracy by 11.8% and achieve for the first time over 90% attack accuracy. Our findings demonstrate that there is a clear risk of leaking sensitive information from deep learning models. We urge serious consideration to be given to the privacy implications.
</td> </tr>
</tbody></table>



