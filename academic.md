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
The IEEE/WIC/ACM International Conference on Web Intelligence (WI) (Accepted)  <br>
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
<li>Proposed a lock free strategy for training knowledge graph embedding in parallel.</li>
<li>Parallelized the computation modules that are based on knowledge graph embedding, including entity alignment, relation extraction and tag inference.</li>
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
The project aims to make a GUI web tool for data scientists to make workflows of various machine learning and data mining algorithms fast and easily.<br>
My Work : <!-- <li>Implemented various machine learning and preprocess algorithms in spark. </li> -->
<li>Implemented GBDT (Gradient Boosting Decision Tree) algorithm in Spark.</li>
<li>Optimized the GBDT algorithm above to run faster than Spark MLlib.</li>
<li>Optimized the IO cost and storage cost of the workflow using parquet.</li>
</ul>

<ul>
<b>Agricultural Product Price Prediction Program</b><br>
This project aims to predict the future price of certain agricultural products in China, based on the historical price data. We ranked top two in CCF BigData & Computing Intelligence Contest on Agricultural Product Price Prediction among more than 500 teams.<br>
My work:
<li>Implemented GBDT Model and Random Forest for ensemble.</li>
<li>Designed the loss function by weighting more to the data with lower price according to this specific problem, which lead to a great promotion in accuracy.</li>
</ul>

<ul>
<b>Commodity Demand Prediction Program</b><br>
This project aims to predict the future sales of certain products in TaoBao, using the historical sales data and user behavior data. We ranked 13 in AliBaba Tianchi BigData Contest on CaiNiao Supply Chain Prediction among more than 2800 teams.<br>
My work:
<li>Implemented GBDT algorithm using Java in MapReduce framework to make it run in AliBaba’s bigdata platform ODPS.</li>
<li>Designed the loss function by predicting a higher price for the data with higher cost of low prediction, and predicting a lower price for the data with higher cost of high predition, which lead to a great promotion in accuracy.</li>
</ul>
</div>

<div class='section'>
<h1 id='2014'>2014</h1>
<ul>
<b>Computer Program "ConnectSix" to Play Connect Six Game</b><br>
The project aims to develop a computer program to play the board game Connect Six. We won the first prize in National Computer Game Championships.
<br>
My Work :
<li>Implemented Alpha-Beta Search algorithm to search the game tree of Connect Six.</li>
<li>Optimized the search algorithm by adding VCF(Victory of Continuous Four) strategy.</li>
</ul>
</div>
