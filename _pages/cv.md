---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


<style>
.tooltip {
    position: relative;
    cursor: pointer;
}
.tooltip .tooltiptext {
    visibility: hidden;
    width: 20vw;
    background-color: rgba(192,192,192,1);
    color: rgba(255,255,255,1);
    text-align: left;
    border-radius: 10px;
    padding: 10px;
    position: absolute;
    z-index: 1;
    bottom: 125%;
    left: 0%;
    margin-left: 10vw;
    opacity: 0;
}
.tooltip.show .tooltiptext {
    visibility: visible;
    opacity: 1;
}
</style>


<script>
function toggleTooltip(element) {
    element.classList.toggle('show');
}
</script>


<h2>EDUCATION</h2>
<div class="tooltip" onclick="toggleTooltip(this)">
<ul>
<li>B.S. in Mathematics and Physics, Tsinghua University, 2022 - Present</li>
<li>B.E. in Energy and Power Engineering, Tsinghua University, 2022 - Present</li>
</ul>
<span class="tooltiptext">Double major</span>
</div>



<h2>ACADEMIC EXPERIENCES</h2>

<ul>
    <li>
        <strong>Data-driven Operational Quality Modeling of Civil Aircraft</strong>
        <div style="font-style: italic;">Supervisor: Xiaowei Yue, Department of Industrial Engineering, Tsinghua University<span style="float: right;">Oct. 2023 - Jul. 2024</span></div>
        <ul>
            <li>Developed time-series forecasting algorithms for flight data, implementing linear, CNN-based, RNN-based, Transformer-based, and other recent/hybrid approaches.</li>
            <li>Developed variational autoencoder based anomaly detection algorithms for data cleaning and wind shear detection.</li>
            <li>Developed uncertainty quantification methods for flight data, with a focus on Bayesian Neural Network.</li>
        </ul>
    </li>
    <li>
        <strong>AI for Complex Network Science: Generative Models and Control Theory</strong>
        <div style="font-style: italic;">Supervisor: Jingtao Ding, Department of Electronic Engineering, Tsinghua University<span style="float: right;">Nov. 2024 - Present</span></div>
        <ul>
            <li>Developed imitation learning and offline reinforcement learning approaches like BC and BPPO for control tasks on complex network datasets.</li>
            <li>Developed PID-controlled Langevin dynamics algorithm for efficient sampling of generative models, involved in early stage idea verification, algorithm design, mass experimentation, manuscript writing, and author rebuttal.</li>
            <li>Developing diffusion-based Koopman learning approaches for model predictive control.</li>
        </ul>
    </li>
    <li>
        <strong>Adversarial Robust Online Reinforcement Learning with Human Feedback</strong>
        <div style="font-style: italic;">Supervisor: Lifeng Lai, Department of Electrical and Computer Engineering, UC Davis<span style="float: right;">Jul. 2025- Present</span></div>
        <ul>
            <li>Developed robust RLHF algorithm under label flipping attack, incorporating approaches like preference to reward interface (P2R) and upper confidence bound value iteration with Bernstein-Freedman bonus (UCBVI-BF).</li>
            <li>Gave theoretical proofs of the unbiasedness and error bound of the proposed algorithm.</li>
            <li>Designed grid world experiments to validate the effectiveness of the proposed algorithm.</li>
        </ul>
    </li>
</ul>


<h2>PROJECT EXPERIENCES</h2>

<ul>
    <li>
        <strong>Development of Data-driven Soft Monitoring Technology for Energy-saving and Environmental Protection</strong>
        <div style="font-style: italic;">Supervisor: Yang Zhang, Department of Energy and Power Engineering<span style="float: right;">Jul. 2024 - May. 2025</span></div>
        <ul>
            <li>Developed time-series forecasting algorithms for boiler gas emission monitoring, highlighting accurate prediction near environment protection policy thresholds.</li>
            <li>Developed an online platform with web front-end technology to display boiler gas emission data for environmental monitoring.</li>
        </ul>
    </li>
</ul>



<h2>PUBLICATIONS</h2>

<ul>
    <li><a href="https://arxiv.org/abs/2502.17893" title="Arxiv preprint"><strong>Sample-efficient Diffusion-based Control of Complex Nonlinear Systems</strong></a> (Arxiv, under review)<br/>Hongyi Chen, Jingtao Ding†, <strong>Jianhai Shu</strong>, Xinchun Yu, Xiaojun Liang, Yong Li, Xiao-Ping Zhang†</li>
    <li><a href="https://openreview.net/pdf/ca538d7942e9fcfe6e80d727a1f12a3ae09e34b9.pdf" title="NeurIPS2025"><strong>PID-controlled Langevin Dynamics for Faster Sampling of Generative Models</strong></a><br/>Hongyi Chen*, <strong>Jianhai Shu*</strong>, Jingtao Ding†, Yong Li, Xiao-Ping Zhang†. 2025. Advances in Neural Information Processing Systems.</li>
</ul>



<h2>SKILLS</h2>
<ul>
    <li>C++</li>
    <li>Python
        <ul>
            <li>numpy & matplotlib & pandas</li>
            <li>pytorch</li>
            <li>keras/tensorflow</li>
            <li>scikit-learn</li>
        </ul>
    </li>
    <li>MATLAB & Simulink</li>
    <li>Web Front-End Development
        <ul>
            <li>HTML & CSS & JavaScript</li>
            <li>Vue.js</li>
        </ul>
    </li>
    <li>LaTeX & Beamer</li>
</ul>

<h2>CAMPUS EXPERIENCE</h2>
<ul>
    <li>Member, Student Right Department, <strong>Student Union of Weiyang College</strong><span style="float: right; font-style: italic;">Mar. 2023 - Dec. 2023</span>
        <ul>
            <li>Help organize daily activities and events for the department, e.g. annual student festival.</li>
        </ul>
    </li>
    <li>Member, Academic Department, <strong>Association of Science and Technology of Weiyang College</strong><span style="float: right; font-style: italic;">Mar. 2024 - Dec. 2024</span>
        <ul>
            <li>Design and give lectures of useful academic-related skills, i.e., MATLAB operations in probability and statistics, Simulink operations, and personal webpage development.</li>
        </ul>
    </li>
</ul>
