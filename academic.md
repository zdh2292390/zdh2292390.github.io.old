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
<h1 id='2017'>2017</h1>
<ul>

<b>Knowledge Graph Computation Platform for Video Field</b><br>
Advisor: Jia Yantao, Wang Yuanzhuo, Institute of Computing Technology, Chinese Academy of Sciences (cooperate with Huawei Inc.)<br>
This project aims to construct a knowledge graph for videos, including movies, series, carton, etc. Furthermore, the knowledge graph can be enriched automatically from different data source, and supports a plenty of applications such like relation extraction, relation prediction.<br>
My work 1:
<li>Analyzed the parallel methods, including Hogwild!, DistBelief, etc., for the sake of accelerating the supported computation modules.</li>
<li>Proposed and verified the feasibility of lock free strategy in training knowledge graph embedding in parallel.</li>
<li>Paralleled the computation modules that are based on knowledge graph embedding, including entity alignment, relation extraction and tag inference.</li>
My work 2:
<li>Proposed to explore the rich information of hierarchical structures in knowledge graph to promote the relation prediction performance. </li>
<!-- <li>proved the convergence of the proposed method.</li> -->
<li>Experimented the strategy of integrating hierarchical structures on three data sets, and demonstrate the superiority of proposed method.</li>
</ul>
</div>

<div class='section'>
<h1 id='2016'>2016</h1>
<ul>
<b>Big Data Analysis Platform</b><br>
Advisor: Lei Cao, Jun Xu, Institute of Computing Technology, Chinese Academy of Sciences<br>
The project aimed to make a GUI web tool for data scientists to make workflows of all kinds of machine learning and data mining algorithms fast and easily.<br>
My Work : <!-- <li>Implemented various machine learning and preprocess algorithms in spark. </li> -->
<li>Implemented GBDT algorithm in Spark and optimized it to run faster than MLlib.</li>
<li>Optimized the IO cost and storage cost of the workflow using parquet.</li>
</ul>

<ul>
<b>CCF BDCI Agricultural Products Predict Contest</b><br>
This contest aimed to predict the future price of certain agricultural products in China, using the history price data. I used GBDT(Gradient Boosting Decision Tree) Model and Random Forest for ensemble, proposed a loss optimal function for the problem and got a great promotion in accuracy.<br>
My work:
<li>Feature engineering</li>
<li>Loss function design</li>
</ul>

<ul>
<b>AliBaba Tianchi BigData: CaiNiao Supply Chain Predict Contest</b><br>
This contest aimed to predict the future sales of certain products in TaoBao, using the history sales data and user behavior data. I used GBDT(Gradient Boosting Decision Tree) Model, analyzed the target cost fucntion, then modified the loss function of the GBDT model and got a great promotion in accuracy.<br>
My work:
<li>Feature engineering</li>
<li>Loss function implementation</li>
<li>Implemented GBDT algorithm using Java in MapReduce framework to make it run in AliBaba’s bigdata platform ODPS.</li>
</ul>
</div>

<div class='section'>
<h1 id='2014'>2014</h1>
<ul>
<b>National Computer Game Championships (Connect Six)</b><br>
The contest aimed to ask players to play against each other, using their own Connect Six program
<br>
My Work :
<li>Implemented the game tree search algorithm to play Connext Six.</li>
<li>Optimized the search algorithm.</li>
</ul>
</div>

