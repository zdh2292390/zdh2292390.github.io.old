---
layout: page
title: "Research"
description: ""
---
{% include JB/setup %}

## Publication

<!-- ## Conference Papers -->
<div class='zdh'>
<b>Efficient Parallel Translating Embedding For Knowledge Graphs.</b>  <br>
<b>Zhang Denghui</b>, Li Manling, Jia Yantao, Wang Yuanzhuo  <br>
The IEEE/WIC/ACM International Conference on Web Intelligence (WI) (Submitted)  <br>
<!-- [arXiv:1703.10316](https://arxiv.org/abs/1703.10316)   -->
<!-- {[PDF](https://arxiv.org/pdf/1703.10316.pdf), [Code](https://github.com/zdh2292390/ParTrans-X)} -->
{<a href='https://arxiv.org/pdf/1703.10316.pdf'>PDF</a>, <a href='https://github.com/zdh2292390/ParTrans-X'>Code</a>}<br>
</div>
<!-- ## Journal Papers -->
<div class='zdh'>
<br/>
<b>Link Prediction in Knowledge Graphs: A Hierarchy-Constrained Approach.</b>  <br>
Li Manling, <b>Zhang Denghui</b>, Jia Yantao, Wang Yuanzhuo, Cheng Xueqi  <br>
IEEE Transaction on Big Data Special Issue on "Knowledge Graphs: Techniques and Applications" (Submitted)  <br>
<!-- {[PDF](https://zdh2292390.github.io/TBD-2017-02-0077_v3.pdf)} -->
{<a href='https://zdh2292390.github.io/TBD-2017-02-0077_v3.pdf'>PDF</a>}<br>
</div>
## Project
<div class='section'>
<h1 id='kb'>Knowledge Graph</h1>
<ul>
<!-- <a href='https://github.com/zdh2292390/ParTrans-X'>ParTrans-X: An efficient parallel lib for translating embedding algorithms. </a>
The main adavantage of our lib is that our algorithms are totally lock-free multithreading, which enables the algorithms to be highly efficient, and we give some theoretical guarantees in our paper.
Up to now, we implemented the parallel version of TransE, AdagradTransE, and TransH. Named ParTransE, ParAdagradTransE, ParTransH respectively. -->
<b>A Knowledge Graph Computation Platform for Video Field</b><br>
Advisor: Jia Yantao, Wang Yuanzhuo, Institute of Computing Technology, Chinese Academy of Sciences (cooperate with Huawei Inc.)<br>
This project aims to construct a knowledge graph for videos, including movies, series, carton, etc., without involving too much manual work. Furthermore, the knowledge graph can be enriched and updated automatically from different data source, and supports a plenty of computation modules, such as relation extraction, relation prediction, tag inference, etc.<br>
My work 1:
<li>analyzed the parallel methods, including Hogwild!, DistBelief, etc., for the sake of accelerating the supported computation modules.</li>
<li>proposed and verified the feasibility of lock free strategy in training knowledge graph embedding in parallel.</li>
<li>paralleled the computation modules that are based on knowledge graph embedding, including entity alignment, relation extraction and tag inference.</li>
My work 2:
<li>proposed to explore the rich information of hierarchical structures in knowledge graph to promote the relation prediction performance. </li>
<!-- <li>proved the convergence of the proposed method.</li> -->
<li>experimented the strategy of integrating hierarchical structures on three data sets, and demonstrate the superiority of proposed method.</li>
</ul>
</div>

<div class='section'>
<h1 id='bigdata'>BigData</h1>

<ul>
<b>A Big Data Analysis Platform</b><br>
Advisor: Lei Cao, Jun Xu, Institute of Computing Technology, Chinese Academy of Sciences<br>
The project aimed to make a GUI web tool for data scientists to make workflows of all kinds of machine learning and data mining algorithms fast and easily.<br>
My Work : <!-- <li>Implemented various machine learning and preprocess algorithms in spark. </li> -->
<li>Implemented GBDT algorithm in spark and optimized it to run faster than MLlib.</li>
<li>Optimized the IO cost and storage cost of the workflow using parquet.</li>
</ul>
</div>

