# SSBONDPredict
A machine learning method for disulfide bond engineering site prediction based on structures
## Introduction
SSBONDPredict is a project use a computational method based on neural network to predict residue pairs that can form disulfide bonds after cysteine mutations.The neural network was trained with atomic structures curated from the Protein Data Bank. The webserver are available at [PredDisufideBond](http://liulab.csrc.ac.cn/ssbondpre) and you can get the detail source code and usage in **PreDisulfideBond** folder.Beside predicting the residue pairs which can form disulfide bonds after mutations,it also can calculate the change of entropy and energy due to mutations. 
The predicted result will show you like this:  
```CYSA4-ARGA10 0.997 -24.4450 -1.8942```  
the order of result from left to right are followed by:
* Residue pairs that can form disulfide bonds after mutations.  
* The probability about this residue pairs can form disulfide bonds after mutations.  
* Change of entropy after mutations  
* Change of energy after mutations  

## Detailed Documentation 
see the Source code [README](https://github.com/LiuLab-CSRC/SSBONDPredict/tree/master/PreDisulfideBond)

## Copyright  
SSBONDPredict is created by liulab of Beijing Compulational Science Research Center.
