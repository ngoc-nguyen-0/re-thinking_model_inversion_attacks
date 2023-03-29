<!doctype html>
<title>Re-thinking Model Inversion Attacks Against Deep Neural Networks</title>
    <html lang="en">

<head>
    <meta charset="UTF-8">
    <!-- If IE use the latest rendering engine -->
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <!-- Set the page to the width of the device and set the zoon level -->
    <link rel="stylesheet" type="text/css" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="style.css">
</head>


<body>
    <!-- page-header-->
    <div class="jumbotron" style="background-color:#e0edf9">
    <div class="container" style="font-family:'Times New Roman',serif">
        <h1 class="display-1" style="text-align:center; font-weight:bold; font-size:2.0em;letter-spacing:2.0px;">
            Re-thinking Model Inversion Attacks Against Deep Neural Networks</h1>
        <hr style="border-top: 1px solid #000000; background: transparent;" class="my-4">
        
        <p class="lead" style="text-align:center;font-size:1.25em;">
            <a href="mailto: thibaongoc_nguyen@mymail.sutd.edu.sg">Ngoc-Bao Nguyen(*)</a> |
            <a href="mailto: keshigeyan@sutd.edu.sg">Keshigeyan Chandrasegaran(*)</a> |
            <a href="mailto: milad_abdollahzadeh@sutd.edu.sg">Milad Abdollahzaden</a> |
            <a href="mailto: ngaiman_cheung@sutd.edu.sg">Ngai-Man Cheung</a> </br>
        Singapore University of Technology and Design (SUTD)<br/>
        <em>CVPR-2023</br></em>
        </p>
            
            
        <p class="lead" style="text-align:center;font-size:1.25em;"> 
            <a href="https://drive.google.com/file/d/14jzdPKvJ7BVntYdptWmGAPxiVau2TI9e/view?usp=share_link">Paper</a> |
            <a href="https://github.com/sutd-visual-computing-group/Re-thinking_MI">Github</a> |
            <a href="https://drive.google.com/drive/folders/1kq4ArFiPmCWYKY7iiV0WxxUSXtP70bFQ?usp=sharing">Models</a> |            
            <a href="https://colab.research.google.com/drive/1k3ml6cRV0jBZyIKbu8CTBcbraSeNP3w1?usp=sharing">Demo</a> 
            
        </p>         
            
    </div>
    </div>

    <div class="container" style="font-family:'Times New Roman',serif">
        <p style="text-align:center;">
        <img width="850" src="./docs/assets/images/framework_v3_page-0001.jpg">
        </p>
    </div>
    
    <!-- Abstract -->
    <div class="container" style="font-family:'Times New Roman',serif">
        <h2 class="display-1" style="text-align:center; font-weight:bold; font-size:1.5em;letter-spacing:2.0px;">Abstract</h2>
        <hr style="border-top: 1px solid #000000; background: transparent;" class="my-4">
            <p class="lead" style="text-align:left;font-size:1.25em;">
                Model inversion (MI) attacks aim to infer and reconstruct private training data by abusing access to a model. MI attacks have raised concerns about the leaking of sensitive information (e.g. private face images used in training a face recognition system). Recently, several algorithms for MI have been proposed to improve the attack performance. In this work, we revisit MI, study two fundamental issues pertaining to all state-of-the-art (SOTA) MI algorithms, and propose solutions to these issues which lead to a significant boost in attack performance for all SOTA MI. In particular, our contributions are two-fold: 1) We analyze the optimization objective of SOTA MI algorithms, argue that the objective is sub-optimal for achieving MI, and propose an improved optimization objective that boosts attack performance significantly. 2) We analyze “MI overfitting”, show that it would prevent reconstructed images from learning semantics of training data, and propose a novel “model augmentation” idea to overcome this issue. Our proposed solutions are simple and improve all SOTA MI attack accuracy significantly. E.g., in the standard CelebA benchmark, our solutions improve accuracy by 11.8% and achieve for the first time over 90% attack accuracy. Our findings demonstrate that there is a clear risk of leaking sensitive information from deep learning models. We urge serious consideration to be given to the privacy implications.

            </p>

    </div>



    <!-- Citation -->
    <div class="container" style="font-family:'Times New Roman',serif">
        <h2 class="display-1" style="text-align:center; font-weight:bold; font-size:1.5em;letter-spacing:2.0px;">Citation</h2>
        <hr style="border-top: 1px solid #000000; background: transparent;" class="my-4">
            
        <pre class="lead" style="text-align:left;font-size:1.0em;white-space: pre-line;">
            <code>@inproceedings{anonymous2023rethinking,
                title     = {Re-thinking Model Inversion Attacks Against Deep Neural Networks},
                author    = {Ngoc-Bao Nguyen, Keshigeyan Chandrasegaran, Milad Abdollahzadeh, Ngai-man Cheung},
                booktitle = {Conference on Computer Vision and Pattern Recognition 2023},
                year      = {2023}</br>}</code>
        </pre>
    </div>


    <!-- Acknowledgements -->
    <div class="container" style="font-family:'Times New Roman',serif">
        <h2 class="display-1" style="text-align:center; font-weight:bold; font-size:1.5em;letter-spacing:2.0px;">Acknowledgements</h2>
        <hr style="border-top: 1px solid #000000; background: transparent;" class="my-4">
            
            <p class="lead" style="text-align:left;font-size:1.25em;">
                This research is supported by the National Research Foundation, Singapore under its AI Singapore Programmes (AISG Award No.: AISG2-RP-2021-021; AISG Award No.: AISG2-TC-2022-007). 
        This project is also supported by SUTD project PIE-SGP-AI-2018-01. We thank reviewers for their valuable comments. We also thank Loo Yi and Kelly Kuo for helpful discussion.
            </p>

    </div>
    
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.5/js/bootstrap.min.js"></script>

</body>
</html>
