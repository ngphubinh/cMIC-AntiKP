# cMIC-AntiKP: Calculating MICs of Antibiotics towards Klebsiella Pneumoniae
#### H. H. Ngo, T-H. Nguyen-Vo, T. T. T. Do, M. T. Do, Q. H. Nguyen, and [B. P. Nguyen](https://homepages.ecs.vuw.ac.nz/~nguyenb5/about.html)∗


![alt text](cMIC-AntiKP_abs.svg)

## Motivation
Nowadays, antibiotic resistance has become one of the most concerning problems which directly affect the recovery process of patients. 
For years, numerous efforts have been made to efficiently use antimicrobial drugs with appropriate doses not only to exterminate 
microbes but also stringently constrain any chances for bacterial evolution. However, choosing proper antibiotics is not a 
straightforward and time-effective process because well-defined drugs can only be given to patients after determining microbic taxonomy 
and evaluating minimum inhibitory concentrations (MICs). Besides conventional methods, numerous computer-aided framework has been 
recently developed using computational advances and public data sources of clinical antimicrobial resistance. In this study, 
we introduce cMIC-AntiKP, a computational framework specifically designed to predict MIC values of 20 antibiotics 
towards *Klebsiella pneumoniae*. Our prediction models were constructed using convolutional neural networks and k-mer 
counting-based features. 

## Results
The model for cefepime has the most limited performance with a test accuracy of 0.49 while the model for 
ampicillin has the highest performance with a test accuracy of 1.00. Most of the rest of the model have satisfactory performances 
with test accuracies ranging from about 0.7 to 0.90. The significance of cMIC-AntiKP is the effective utilization of 
computing source to make it become a compact and portable tool for most moderately configured computers. We provide users with 
two options, including an online web-server for basic analysis and an offline package for deeper analysis and technical modification. 

## Availability and implementation
Source code and data are available at [GitHub](https://github.com/mldlproject/2020-cMIC-AntiKP)

## Webserver
Please access our webserver [here](http://cmic.studio)

## Contact 
[Go to contact information](https://homepages.ecs.vuw.ac.nz/~nguyenb5/contact.html)
