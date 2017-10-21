---
layout: page
title: "Publication - Paper"
description: ""
---
{% include JB/setup %}

## Link Prediction in Knowledge Graphs: A Hierarchy-Constrained Approach

<img class='inset right' title='The adaptive margin in hTransA' src='./images/hTransM.jpg' alt='The adaptive margin in hTransA' width='370px' />

<div class='section'>
<h1> Date </h1>
<ul>2016/10 - 2017/03</ul>
<h1>Authors</h1> <ul>Manling Li, <b>Denghui Zhang</b>, Yantao Jia, Yuanzhuo Wang, Xueqi Cheng</ul>
<h1>Paper</h1>
<ul>
[<a href='docs/TBD-2017-02-0077.pdf'>PDF</a>]
</ul>
<h1>Problem</h1> 
<ul>
50% triples in knowledge graphs are organized in hierarchical structures, which also contain rich inference patterns to predict links but do not be fully used. A main feature of hierarchical structure is multi-layer, which traditional methods fails to make use of.
</ul>
<h1>My Work</h1> 
<ul>
<li> Came up with the idea to divide the hierarchical structures into two categories, i.e., single-step hierarchical structures and multi-step hierarchical structures.</li>
<li> Proposed multi-step specific margin, and the link prediction method based on detecting single-step and multi-step hierarchical structures, called <b>hTransM</b>. It can adaptively determine the optimal margin to separate positive and negative triples. </li>
<li> Proved the convergence of hTransM by demonstrating its uniform stability and provide the upper bound of the error of the proposed model.</li>
<li> Experimented hTransM over 3 datasets of 2 sub-tasks, i.e., entity prediction task and relation prediction task, which demonstated that hTransM can achieve better prediction performance. </li>
<li> Studyed the variation of the optimal margin value along with the optimization process, and compared with the methods withnot considering hierarchical information. It validated the superiority of hierarchy-constrained margin. </li>
<li> The paper was submitted to IEEE Transaction on Big Data (Lead Author) and under review now. </li>
</ul>
</div>