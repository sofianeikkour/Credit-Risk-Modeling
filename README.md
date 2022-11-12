# Credit-Risk-Modeling

### **Context and Objective:**  
In this project we'll be building various models to measure credit risk for a bank in the United States. Credit risk is a very sensitive topic and it is important for the financial health of creditors. Therefore, I spent a considerable amount of time looking for the best practices there is to predict the probability of default. Here, I followed the rules established by the Basel II and Basel III Accords which means that everything is done exactly as it is performed in banks. I took advantage of techniques like fine classing, coarse classing, weight of evidence, and information value which I believe their use is one of the most important determinants of the success of the model. 

Three different models are built:   
- PD (Probabililty of Default) showing the probability of a customer not repaying their debt.  
- LGD (Loss Given Default) showing the proportion of an exposure a company loses when a customer defaults.
- EAD (Exposure at Default) showing the total loss in terms of amount of money the bank is exposed to if a customer defaults.  

With this information, a scorecard identical to the ones bank officers use on a daily basis to accept or reject loan applications is created.

Finally, the three models are combined to calculate the total expected loss for the whole portfolio of loans that the bank holds. 

Credit risk models need adjustments from time to time. So a particular focus was given to maintaining credit risk models and deploying them for direct use. 

### **Dataset:**  
The dataset used contains all available data for more than 800,000 consumer loans issued from 2007 and 2015 by a large U.S. peer to peer lending company named LendingClub. There are several versions of this dataset. I have used a dataset available on www.kaggle.com. 

**Note:** This code was written on Jupyter Notebook.  
**Programming language:** Python.  
**Packages:** numpy, pandas, sklearn, scipy, matplotlib, seaborn.
