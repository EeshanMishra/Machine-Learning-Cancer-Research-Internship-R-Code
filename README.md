# Machine-Learning-Cancer-Research-Internship-R-Code
This repo was made to give context to the code used. In order to request access to the code, which has been made private because the research has yet to be completed, please email cameeshan@gmail.com.

The code given in this repository is the R code used during my 2017 machine-learning internship, a collaboration between researchers for the University of Missouri-Columbia and MD Anderson Cancer Center. The branch of the research that I contributed to uses the NEJM dataset, which contains the attributes, such as gene expression values, of the cancer patients (X), and the DLBCL dataset, which contains the respective cancer survival times (Y).

Observable in "main.r" and "readData.r", the code uses a sample size of n = 100 individuals (cancer patients) and p = 1000 covariates, randomly assigning 67 individuals to the training set and 33 to the test set. The concordance error rates, which "measure a procedure’s probability of incorrectly ranking the failure times of two randomly chosen individuals", are calculated in "error.rates.r" and the number of predictors is calculated in "num.pred.r".

There were 3 techniques for gene selection with survival outcomes that were used: elastic net, L2-boosting, and supervised principal components (superpc). Their respective R implementations are in "glmnet.r", "mboost.r", and "spc.r".

The information given above is an overview to help understand the premise of the code and the research. For more specific information on my contributions to the research, or any general questions, email me at cameeshan@gmail.com
