Multivariate Adaptive Regression Splines (Friedman, 1991) is a nonparametric technique that combines regression splines and model selection methods. It is a powerful predictive modeling tool because 1) it extends linear models to analyze nonlinear dependencies 2) it produces parsimonious models that do not overfit the data and thus have good predictive power. Multivariate adaptive regression splines construct spline basis functions in an adaptive way by automatically selecting appropriate knot values for different variables. This can help E-miners to identify linear and nonlinear variables, and the interactions of them as well. When excluding higher order terms, multivariate adaptive regression splines are really good at identifying the effects of single variables in a multivariate setting. This makes it highly usable in process control and for identifying experimental designs. Multivariate adaptive regression splines also has its application in forecasting as a variable screening tool.
 
It has always been a desirable tool for our E-miners and now you have multivariate adaptive regression splines as an extension node in Enterprise Miner by just following a few simple steps.

1.	Download all the files from this Github repository, including a XML file (MARS.xml) defining the node properties, a SAS catalog (emextn.sas7bcat), and two GIF files (MARS_16.gif and MARS_32.gif) for the node icon.
 
2.	To deploy the extension node, you need to follow the steps as instructed in Chapter 5 “Deploying an Extension Node” in [“SAS® Enterprise Miner™ 14.1 Extension Nodes: Developer’s Guide”](http://support.sas.com/documentation/cdl/en/emxndg/67980/PDF/default/emxndg.pdf).  

3.	After storing the files in the proper directories, restart the Enterprise Miner server if necessary.

4.	The MARS extension node runs with SAS Enterprise Miner 13.1 or any later version.

Please see this [SAS Data Mining and Machine Learning Community tip](https://communities.sas.com/t5/SAS-Communities-Library/Tip-Fit-Multivariate-Adaptive-Regression-Splines-in-SAS/ta-p/328133) for more details. 

