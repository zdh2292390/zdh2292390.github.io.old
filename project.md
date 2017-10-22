---
layout: page
title: "Projects"
description: ""
---
{% include JB/setup %}

<!-- ## Project -->
<div class='section'>
<h1 id='2017'>01/2017-04/2017</h1>
<ul>

<b>Knowledge Graph Computation Platform for Video Field</b><br>
Advisor: Jia Yantao, Wang Yuanzhuo, Institute of Computing Technology, Chinese Academy of Sciences (cooperate with Huawei Inc.)<br>
This project aims to construct a knowledge graph for videos, including movies, series, etc. The knowledge graph can be enriched automatically from different data source, and supports a plenty of applications such like relation extraction, tag inference.<br>
My work:
<li>Implemented the parallel version of key knowledge graph construction modules,  including ontology alignment algorithm, relation extraction algorithm and tag inference algorithm, which are based on knowledge graph embedding.</li>
<li>Shorted the whole updating procedure to 5-6 hours from 3 days with 60k video entities, which was regarded as one of the main innovations by Huawei Inc.</li>


</ul>
</div>

<div class='section'>
<h1 id='2016'>09/2016-12/2016</h1>
<ul>
<b>Big Data Analysis Platform</b><br> 
Advisor: Lei Cao, Jun Xu, Institute of Computing Technology, Chinese Academy of Sciences<br>
The project aims to provide a GUI web tool and Machine Learning library for data scientists to make workflows of various data mining applications fast and easily. <br>
The demo paper was accepted by CIKM 2016. (online demo: http://159.226.40.104:18080/dev/)<br>
My Work : <!-- <li>Implemented various machine learning and preprocess algorithms in spark. </li> -->
<li>Implemented GBDT (Gradient Boosting Decision Tree) algorithm in Spark.</li>
<li>Optimized the GBDT algorithm in Spark, and it runs faster than Spark MLlib, e.g. 2.4 times faster with 100GB data.</li>
<li>Optimized the IO cost and storage cost of the workflow using parquet file format.</li>
</ul>
</div>

<div class='section'>
<h1 id='2014'>01/2017-04/2017</h1>
<ul>
<b>Agricultural Product Price Prediction Program</b><br>
This project aims to predict the future price of certain agricultural products in China, based on the historical price data. We ranked top two in CCF BigData & Computing Intelligence Contest on Agricultural Product Price Prediction among more than 500 teams.<br>
My work:
<li>Implemented GBDT Model and Random Forest for ensemble.</li>
<li>Designed the loss function by weighting more to the data with lower price according to this specific problem, which lead to a great promotion in accuracy.</li>
</ul>
</div>

<div class='section'>
<h1 id='2014'>04/2016-06/2016</h1>
<ul>
<b>Commodity Demand Prediction Program</b><br>
This project aims to predict the future sales of certain products in TaoBao, using the historical sales data and user behavior data. We ranked 13 in AliBaba Tianchi BigData Contest on CaiNiao Supply Chain Prediction among more than 2800 teams.<br>
My work:
<li>Implemented GBDT algorithm using Java in MapReduce framework to make it run in AliBaba’s bigdata platform ODPS.</li>
<li>Designed the loss function to assign different loss to lower and higher prediction, which lead to a great promotion in accuracy.</li>
</ul>
</div>

<div class='section'>
<h1 id='2014'>07/2014-09/2014</h1>
<ul>
<b>Computer Program "ConnectSix" to Play Connect Six Game</b><br>
The project aims to develop a computer program to play the board game Connect Six. We won the first prize in National Computer Game Championships.
<br>
My Work :
<li>Implemented Alpha-Beta Search algorithm to search the game tree of Connect Six.</li>
<li>Optimized the search algorithm by adding VCF(Victory of Continuous Four) strategy.</li>
</ul>
</div>
