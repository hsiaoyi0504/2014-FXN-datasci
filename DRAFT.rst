.. contents::
    :local:
    :depth: 3
    :backlinks: none

******
AGENDA
******

Abstract
========

本講題首先簡介資料科學，接著針對處理流程中每個階段，討論常見的步驟與可能問題。接著將對數據量多、視覺化議題進行專題敘述。最後以 Python 和 R 語言介紹常用的工具與實際分析流程。

- Data science introduction
- Data processing workflow
    - ETL
    - Analysis
    - Visualization
    - Report
- Big data issue
- Back on visualization
- Data Sci-related society introduction
- Data Analysis in Python and R

ETL
===

- g0v
- 分身伐樹
- 服貿詞頻
- 鄉民 OCR (用的是 PHP)
- 找你寫得順的資料就好
- scrapy selenium
- leave Big Data

Analysis (Model)
================

- all model is wrong
- statistics, machine learning
- ML roadmap(scikit-learn)
- Evaluate model (cross validation/ train-test data)
- Update data
- dimension reduction


Data Science 簡介
=================


- |DataSci-Intro-Johnson|_ by Johnson Hsieh, DSP

.. |DataSci-Intro-Johnson| replace:: *Data Science - 從學校到社會 資料科學計劃的成果與展望*
.. _DataSci-Intro-Johnson: http://www.slideshare.net/euler96/ss-35513599



資料處理流程
============

- Data ETL
    - ETL = Extract, Transform, Loading
    - keyword: data warehouse, data mart
- Data Analysis
- Data Visualization
- Data Report
    - slidify
    - knitr

Big(Large) Data
===============

- `Big data is like teenage sex <fb.me/1r54f62oU>`_

Hadoop / Spark
--------------

- HDF5 https://www.youtube.com/watch?v=wZEFoVUu8h0


Data Visualization
==================

Abstraction
-----------

- Nature graphics http://naturegraphics.tumblr.com/

Interactive
-----------

- |montyhall-vis|_
- hard to understand: `We Need to Talk About TED`__

- |coastline-pop|_

.. |montyhall-vis| replace:: Monty Hall Explained
.. _montyhall-vis: http://blog.vctr.me/monty-hall/

.. |coastline-pop| replace:: Coastline County Population
.. _coastline-pop: http://www.census.gov/dataviz/visualizations/039/

__ http://www.bratton.info/projects/talks/we-need-to-talk-about-ted/

- CSS guru https://pattle.github.io/simpsons-in-css/


- FBI Crime Statistics http://nbviewer.ipython.org/github/ChrisBeaumont/crime/blob/master/glue_plotly_fbi.ipynb

Demo using Python and R
=======================

Pandas
------

R ggplot2
---------

Orange
------

開上次的 VM 來講


pyR
---


Data Science 相關社群
=====================


G0V 開放政府計畫
----------------

- http://gov.tw


DSP 資料科學計畫
----------------

- Code for Tomorrow
- http://datasci.co
- Commercial training program


台灣資料科學愛好者年會 2014
===========================

- Aug 30-31, 2014 @人社館
- http://twconf.data-sci.org/
- 贊助請直接與我聯絡，會再提供窗口

.. >>>>>>>> END OF AGENDA <<<<<<<<

*********
REFERENCE
*********

Example
=======

有趣的例子
----------

- |surv-oscar|_
- |instant-pudding|_
- |interested-datasets|_
- |media-social-movement|_
- |rap-vocab|_
- |plane-search|_
- |helicopter-signal|_
- |google-home-number|_
- |world-cup-pred|_

.. |surv-oscar| replace:: Survival analysis of Oscar Nominees
.. _surv-oscar: http://www.tandfonline.com/doi/abs/10.1198/tast.2010.08259

.. |instant-pudding| replace:: 評估泡麵添加布丁之非典型飲食研究：雙盲、隨機對照交叉試驗
.. _instant-pudding: http://cestlapharm.blogspot.tw/2014/06/evaluation-of-atypical-diet-style-of.html

.. |interested-datasets| replace:: 100+ Interesting Data Sets for Statistics
.. _interested-datasets: http://rs.io/2014/05/29/list-of-data-sets.html

.. |media-social-movement| replace:: Data science and ECFA media analysis
.. _media-social-movement: http://www.slideshare.net/euler96/data-science-and-ecfa-media-analysis

.. |rap-vocab| replace:: The Largest Vocabulary in Hip Hop
.. _rap-vocab: http://rappers.mdaniels.com.s3-website-us-east-1.amazonaws.com/

.. |plane-search| replace:: Modeling the Last Flight of MH370 with a Markov Chain Monte Carlo Method (by Conor L. Myhrvold)
.. _plane-search: http://nbviewer.ipython.org/github/myhrvold/MH370_MCMC/blob/master/MH370_MC_ConorMyhrvold-V3.ipynb

.. |helicopter-signal| replace:: Mystery signal from a helicopter
.. _helicopter-signal: http://www.windytan.com/2014/02/mystery-signal-from-helicopter.html

.. |google-home-number| replace:: How Google Cracked House Number Identification in Street View (MIT Tech Rev)
.. _google-home-number: http://www.technologyreview.com/view/523326

.. |world-cup-pred| replace:: Prediction model for the FIFA World Cup 2014
.. _world-cup-pred: http://grollchristian.wordpress.com/2014/06/12/world-cup-2014-prediction/


視覺化例子
----------

- |cat-guide|_
- |myueh-d3js|_
- |highway-traffic|_
- |fb-princeton|_
- |google-ddos|_
- |world-cup-vis|_

.. |myueh-d3js| replace:: 回顧與展望 李慕約（2013-2014）
.. _myueh-d3js: http://muyueh.com/1314/

.. |cat-guide| replace:: Guide to Housecat Coat Colors and Patterns
.. _cat-guide: http://majnouna.com/creation/catstut6.html

.. |highway-traffic| replace:: Re: [問卦] 有高速公路為什麼會塞車的八卦嗎？
.. _highway-traffic: http://disp.cc/b/27-3ple

.. |fb-princeton| replace:: Facebook 駁普林斯頓研究：按照你們的算法，貴校到了 2021 年就會沒有學生囉
.. _fb-princeton: http://www.inside.com.tw/2014/01/24/facebook-data-scientist-do-not-agree-to-pristine-research

.. |google-ddos| replace:: Google 公布 DDoS 網路攻擊即時地圖
.. _google-ddos: http://technews.tw/2013/10/22/google-digital-attack-map/

.. |world-cup-vis| replace::  Simple Analysis of a Few Aspects of the Wikipedia World Cup 2014 Squads Data
.. _world-cup-vis: http://rscriptsandtips.blogspot.tw/2014/05/simple-analysis-of-few-aspects-of.html

For Myself
----------

- `The Type of Learners`__
- `Why Python is Better than Matlab for Scientific Software`__
- `The Curse of Dimensionality in classification`__
- `My Job is done`__
- `PyCon Infographic`__
- `Solve the problem in a engineering way`__
- `p-value and statisical errors`__
- `UX Crash Course`__
- `HN like website specific for data science: DataTau`__
- `Data is Beautiful subreddit on Reddit`__

__ http://9gag.com/gag/aPvVrbR
__ http://metarabbit.wordpress.com/2013/10/18/why-python-is-better-than-matlab-for-scientific-software/
__ http://www.visiondummy.com/2014/04/curse-dimensionality-affect-classification/
__ http://9gag.com/gag/arprPv7
__ https://tw.pycon.org/2014apac/en/blog/PyCon-Infographic/
__ http://9gag.com/gag/aD0bdvO
__ http://www.nature.com/news/scientific-method-statistical-errors-1.14700
__ http://thehipperelement.com/post/75476711614/ux-crash-course-31-fundamentals
__ http://www.datatau.com/
__ http://www.reddit.com/r/dataisbeautiful/
