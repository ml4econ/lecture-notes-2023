Machine Learning for Economists
================

### Spring 2021 @ Hebrew University of Jerusalem

Instructor: [Itamar Caspi](https://itamarcaspi.rbind.io)

Teaching assistant: David Harar

:spiral_calendar: Spring semester, 2021
:alarm_clock:     17:30 - 20:15
:hotel:           There's no place like home...
:writing_hand:    [github.com/ml4econ](https://github.com/ml4econ/lecture-notes-2021)

:family:          [Moodle Discussion Forum](https://moodle2.cs.huji.ac.il/nu20/mod/forum/view.php?id=342325)

-----

## Overview

This course covers topics that range between data science, machine learning, and econometrics. In particular, it introduces concepts from the world of ML that can potentially contribute to empirical economics. The course exposes the students to popular supervised and unsupervised machine learning methods, with an emphasis on the challenges and opportunities of integrating these methods in empirical economics, and the relevance of ML to policy analysis and causal inference. The various topics are illustrated through applications, reading empirical articles, and doing applied work.

## Learning objectives

Course participants will learn to:

1. Apply best-practices for data science in the context of empirical research in economics.

2. Develop an in-depth and practical knowledge of the challenges and opportunities that arise in applied empirical work that involves high dimensional data.

3. Integrate techniques and insights from the world of machine learning into applied empirical research in economics.


## Prework

Course participants are expected to:

1. Have R, RStudio, and Git installed on their own computers.
2. Sing up for a (free) GitHub, Kaggle accounts.


## Schedule

The schedule below is tentative and subject to change, depending on time and class interests. We will move at a pace dictated by class discussions.  Please check this page often for updates.

| Week                  | Topic                                               |
|:----------------------|:----------------------------------------------------|
| [**1**](#week-1)      | Course Overview & Basic ML Concepts                 |
| [**2**](#week-2)      | Reproducibility & ML Workflow                       |
| [**3**](#week-3)      | Regression and Regularization                       |
| [**4**](#week-4)      | Classification                                      |
| [**5**](#week-5)      | Trees and Forests                                   |
| [**6**](#week-6)      | Causal inference                                    | 
| [**7**](#week-7)      | High-Dimensional Counfounding Adjustment            |
| [**8**](#week-7)      | High-Dimensional Heterogeneous Treatment Effects    |
| [**9**](#week-8)      | Prediction Policy Problems                          |
| [**10**](#week-9)     | Unsupervised Learning                               |
| [**11**](#week-10)    | Text Analysis                                       |
| [**12**](#week-11)    | TBA                                                 |


## Slides

### Part I: Supervised Machine Learning

1. Course Overview [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/01-overview/01-overview.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/01-overview/01-overview.pdf) 

2. Basic ML Concepts [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/02-basic-ml-concepts/02-basic-ml-concepts.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2020/master/02-basic-ml-concepts/02-basic-ml-concepts.pdf) 

3. R, Tidyverse, and Reproducible Projects [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/03-reprod-vc/03-reprod-vc.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/03-reprod-vc/03-reprod-vc.pdf)  

4. A Typical (Supervised) ML Workflow [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/04-ml-workflow/04-ml-workflow.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/04-ml-workflow/04-ml-workflow.pdf)

5. Regression and Regularization
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/05-regression-regularization/05-regression-regularization.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/05-regression-regularization/05-regression-regularization.pdf)  
  5.1 [Prepare browser data](https://raw.githack.com/ml4econ/lecture-notes-2021/master/05-regression-regularization/05-prepare-browser-data.html)  
  5.2 [Ridge and lasso simulation](https://raw.githack.com/ml4econ/lecture-notes-2021/master/05-regression-regularization/05-simulations.html)  
  5.3 [Ridge, lasso, PCR and PLS: A Tidymodels Workflow](https://raw.githack.com/ml4econ/lecture-notes-2021/master/05-regression-regularization/05-tidymodels-workflow.html)  

6. Classification
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/06-classification/06-classification.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/06-classification/06-classification.pdf)  
  6.1[Classification: A Tidymodels workflow](https://raw.githack.com/ml4econ/lecture-notes-2021/master/06-classification/06-tidymodels-workflow-covid.html)

7. Trees and Forests
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/07-trees-forests/07-trees-forests.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/07-trees-forests/07-trees-forests.pdf)  

### Part II: Causal Inference and ML

8. Causal Inference
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/08-causal-inference/08-causal-inference.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/08-causal-inference/08-causal-inference.pdf)

9. High-Dimensional Confounding Adjustment
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/09-lasso-ate/09-lasso-ate.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/09-lasso-ate/09-lasso-ate.pdf)

10. High-Dimensional Heterogeneous Treatment Effects
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/10-trees-cate/10-trees-cate.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/10-trees-cate/10-trees-cate.pdf)

### Part III: Unsupervised Learning

11. Text Mining
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/11-text-mining/11-text-mining.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/11-text-mining/11-text-mining.pdf)

### Part IV: Miscellaneous

12. Prediction Policy and Algorithmic Bias
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/12-pred-policy/12-pred-policy.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/12-pred-policy/12-pred-policy.html)


### Projects

A. Kaggle competition [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/a-kaggle/a-kaggle.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2021/master/a-kaggle/a-kaggle.pdf)

## Readings

Can be found [here](https://github.com/ml4econ/lecture-notes-2021/blob/master/resources.md).

## People

+ [**Itamar Caspi**](https://itamarcaspi.rbind.io) is Head of the Monetary Analysis Unit in the Research Department of the Bank of Israel, and an adjunct lecturer at the Hebrew University, having started off in 2010 as an Economist at the Ministry of Finance. In 2012 he moved to the Bank of Israel, and was promoted in 2018 to Senior Economist and elected to represent the Bank as a Research Fellow for three months at the Bank for International Settlements in Switzerland. He holds a BA in Economics and Business Administration from Ben-Gurion University, MA in Economics from the joint research program at Hebrew University and Tel-Aviv University, and a PhD in economics from Bar-Ilan University.

+ **David Harar** is a research fellow at the IEP and former economist in the Israeli Antitrust Authority's research department. He holds an MA in Economics and is currently pursuing an MA in Statistics, both from the Hebrew University of Jerusalem. David's interests include competition economics, demand estimation, machine learning and econometrics.

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).

