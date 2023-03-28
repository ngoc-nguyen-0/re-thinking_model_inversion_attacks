
<div class="container" style="background-color:#e0edf9">   
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
</div>

<p style="text-align:center;">
<img width="700" src="./docs/assets/images/framework_v3_page-0001.jpg">
</p>

<div class="container" >   
        <h2 align="center">Abstract</h2>
        <hr style="border-top: 1px solid #000000;background:33475b;" class="my-4">
        <table align="center" width="850px">
        <tbody>
        <tr><td>
        Model inversion (MI) attacks aim to infer and reconstruct private training data by abusing access to a model. MI attacks have raised concerns about the leaking of sensitive information (e.g. private face images used in training a face recognition system). Recently, several algorithms for MI have been proposed to improve the attack performance. In this work, we revisit MI, study two fundamental issues pertaining to all state-of-the-art (SOTA) MI algorithms, and propose solutions to these issues which lead to a significant boost in attack performance for all SOTA MI. In particular, our contributions are two-fold: 1) We analyze the optimization objective of SOTA MI algorithms, argue that the objective is sub-optimal for achieving MI, and propose an improved optimization objective that boosts attack performance significantly. 2) We analyze “MI overfitting”, show that it would prevent reconstructed images from learning semantics of training data, and propose a novel “model augmentation” idea to overcome this issue. Our proposed solutions are simple and improve all SOTA MI attack accuracy significantly. E.g., in the standard CelebA benchmark, our solutions improve accuracy by 11.8% and achieve for the first time over 90% attack accuracy. Our findings demonstrate that there is a clear risk of leaking sensitive information from deep learning models. We urge serious consideration to be given to the privacy implications.
        </td> </tr>
        </tbody></table>        
        <hr style="border-top: 1px solid #000000;background:33475b;" class="my-4">
</div>


<div class="container">  
        <h2 align="center">Citation</h2>
        <hr style="border-top: 1px solid #000000;background:33475b;" class="my-4">
        <table style="background-color:#d1d2d3" width="850px">
                <pre class="lead" style="text-align:left;font-size:1.0em;white-space: pre-line;">            
                        <code>@inproceedings{
                                anonymous2023rethinking,
                                title = {Re-thinking Model Inversion Attacks Against Deep Neural Networks},
                                author = {Ngoc-Bao Nguyen, Keshigeyan Chandrasegaran, Milad Abdollahzadeh, Ngai-man Cheung},
                                booktitle = {Conference on Computer Vision and Pattern Recognition 2023},
                                year = {2023}
                        }</code>
                </pre>
        </table>
        
        <hr style="border-top: 1px solid #000000;background:33475b;" class="my-4">
</div>


<div class="container">    
        <h2 align="center">Acknowledgements</h2>
        <hr style="border-top: 1px solid #000000;background:33475b;" class="my-4">
        This research is supported by the National Research Foundation, Singapore under its AI Singapore Programmes (AISG Award No.: AISG2-RP-2021-021; AISG Award No.: AISG2-TC-2022-007). 
        This project is also supported by SUTD project PIE-SGP-AI-2018-01. We thank reviewers for their valuable comments.
        
        <hr style="border-top: 1px solid #000000;background:33475b;" class="my-4">
</div>
