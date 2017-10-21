---
layout: page
title: "Publication"
description: ""
---
{% include JB/setup %}

## Path-Based Attention Neural Model for Fine-Grained Entity Typing

<img class='inset right' title='PAN' src='./images/PAN.jpg' alt='The Architecture of PAN' width='270px' />

<div class='section'>
<h1> Date </h1>
<ul>
06/2017 - 09/2017
</ul>
<h1>Authors:</h1> <ul><b>Denghui Zhang</b>, Pengshan Cai, Yantao Jia, Manling Li, Yuanzhuo Wang</ul>
<h1> Paper </h1>
<ul>
[<a href='docs/PAN.pdf'>PDF</a>]
</ul>
<h1>Problem:</h1> <ul>
Fine-grained entity typing aims to assign entity mentions in the free text with types (e.g., person, politician, etc.), which are arranged in a hierarchical structure. Traditional distant supervision based methods employ a structured data source as a weak supervision and do not need hand-labeled data, but they neglect the label noise in the automatically labeled training corpus. Although recent studies prune wrong data ahead of training, they suffer from error propagation and bring much parameter and computation complexity.</ul>
<h1>This paper</h1>
<ul>
Proposed an end-to-end typing model, called the Path-based Attention Neural model (PAN), by leveraging the hierarchical structure of types to learn a noise-robust performance.
</ul>
<h1>Major Work</h1> 
<ul>
<li> Came up with the idea to use attention model to reduce noise in the training data, and designed the architecture of PAN. </li>
<li> Implemented baseline (Shimaoka et al. 2016) by PyTorch, and then conducted experiments on two datasets to demonstrate the superiority of PAN in reducing noise. </li>
<li> This paper was submitted as a poster to AAAI 2018. </li>
</ul>
</div>


<!--<div class='zdh'>
<b>Date:</b> <br>
06/2016 - 07/2017  <br>
<!--Submitted to AAAI 2018 poster <br>
<b>Advisor:</b> <br>Yantao Jia, Yuanzhuo Wang<br>
<b>Problem:</b> <br>
Fine-grained entity typing aims to assign entity mentions in the free text with types (e.g., person, politician, etc.), which are arranged in a hierarchical structure. Traditional distant supervision based methods employ a structured data source as a weak supervision and do not need hand-labeled data, but they neglect the label noise in the automatically labeled training corpus. Although recent studies prune wrong data ahead of training, they suffer from error propagation and bring much parameter and computation complexity.<br>
<b>My Work</b>:
<li> Came up with the idea to use attention model to reduce noise in the training data, and participated in proposing an end-to-end typing model, called the Path-based Attention Neural model (PAN), by leveraging the hierarchical structure of types to learn a noise-robust performance. 
<li> Implemented PAN by PyTorch, and then conducted experiments on two datasets to demonstrate the superiority of PAN in reducing noise. </li>
<li> Co-authored paper was submitted as a poster to AAAI 2018. </li>
</div>
-->