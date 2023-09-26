# Two Applications of EM Algorithm and its Expansion

## Description
* Analyzed two applications of the EM algorithm, i.e., Gaussian Mixture Model and HMM, and its expansion (convex optimizing GMM with CVaR constraints), while discussing the pros and cons in reflecting risk.

## Abstract
* This article mainly analyzes the effectiveness of EM algorithm in handling log-likelihood functions of some classic models like Hidden Markov Model and Gaussian Mixture Model, which are very difficult to optimize when using other techniques. Besides, another methodology which sets up constrains on tail behavior will be introduced to fit the parameters in Gaussian Mixture model, where CVaR-distance will be mentioned. Finally, evaluations about these techniques will be carried out.
* In the part of empirical study, 1min and 30min frequency returns of Apple stock in the dynamic time period of 2020 will be used to fit these three types of model respectively and then the results and conclusion will be shown.

## Notes
* Please visit <a style='color: black;' href='http://aorda.com/index.php/portfolio-safeguard/' target='_blank'> to download the corresponding data used in this project.
* In the code, Python API of PSG was used to convex optimize Gaussian Mixture Model. Please visit <a href='http://aorda.com/index.php/portfolio-safeguard/' target='_blank'>Portfolio Safeguard</a> for more infomation.

## Main Reference
* <a href='http://www.tup.tsinghua.edu.cn/booksCenter/book_08132901.html' target='_blank'>http://www.tup.tsinghua.edu.cn/booksCenter/book_08132901.html</a>
* <a href='https://ieeexplore.ieee.org/document/18626?arnumber=18626' target='_blank'>https://ieeexplore.ieee.org/document/18626?arnumber=18626</a>
* <a href='https://www.semanticscholar.org/paper/Fitting-Mixture-Models-with-CVaR-Constraints-Pertaia-Uryasev/99f4eed30b9fca3fe8dcba5154709372094ccd54' target='_blank'>https://www.semanticscholar.org/paper/Fitting-Mixture-Models-with-CVaR-Constraints-Pertaia-Uryasev/99f4eed30b9fca3fe8dcba5154709372094ccd54</a>
* <a href='http://uryasev.ams.stonybrook.edu/index.php/research/testproblems/advanced-statistics/fitting-mixture-models-with-cvar/' target='_blank'>http://uryasev.ams.stonybrook.edu/index.php/research/testproblems/advanced-statistics/fitting-mixture-models-with-cvar/</a>
