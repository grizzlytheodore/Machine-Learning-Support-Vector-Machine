# Machine-Learning-Support-Vector-Machine

In depth documentation in ex6.pdf

In this exercise, I use support vector machines (SVM) to build a spam classifier.
First I implement the gaussian kernel. Once the kernel is implemented, it can create decision boundaries. 
I, then, implement processEmail and also create a voccabulary list of words that are used more than 100 times in all the emails. 
Then using those words, you can train the system to recognize spam email using the SVM. 

I contributed large to the following files:
gaussianKernel.m - gaussian kernel for SVM
dataset3Params.m - parameters to use for Dataset3
processEmail.m 0 email processing
emailFeatures.m - feature extraction from emails
