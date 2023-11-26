# Methodology Assignment 5

**Name:** Yutian Shi, **Email:** yus029@ucsd.edu <br />

**Section:** A07, **Mentor:** Mikio Aoi

## Questions

**1. What is the most interesting topic covered in your domain this quarter?** <br />
In this quarter, the most interesting topic covered in our domain is the new method I learnt for dimension reduction. Specifically, the gaussian-process factor analysis (GPFA)  method. This method works well for visualizing and analyzing neural activities. Compared to the PCA method we learnt in previous machine learning courses, GPFA is a more general method that considers time dependence of neural activities. Additionally, it also includes an explicit noise model. Moreover, it performs smoothing and dimension reduction simultaneously. These properties enable it to perform better than the traditional methods, including better performance in adjusting degree of smoothness, taking account of various timescale, and distinguishing spike noises.

**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.** <br />
In this quarter, we mainly learnt to be familiar with methods such as EM algorithms and GPFA by applying them to randomly generated data. In the Quarter 2 Project, I would like to investigate how to apply methods we learned in this quarter to solve specific problems about mice’ neural activity in response to different visual cues. In addition, I would also like to explore the potential of modifying the GPFA method to better fit our question with mice neural activities.

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?** <br />
Currently, we completed our first approach of calculating the maximum likelihood function and using gradient descent to find an estimated parameter to derive our estimated beta, and we are working on the second approach with GPFA. Our example code for GPFA is in Matlab, a potential change we want to make to change it to python, ideally with Pytorch to speed up the code.

**4. What other techniques would you be interested in using in your project?** <br />
I would also like to learn techniques to write more efficient dimension reduction code (perhaps with existing packages and machine learning algorithm knowledge). It is also great to learn about how to plot/ visualize neural data. 
