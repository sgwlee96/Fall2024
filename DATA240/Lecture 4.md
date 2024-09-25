09/12 Thu

# Group Project 
- Due Sep 19th
- 3~4 slides and present
	- Group project title
	- Group members
	- Data collection plan
	- Motivation
	- Community contribution

# Previous Lecture
## Central Limit Theorem
- If we take random samples from the population that are individually and identically distributed, the sample mean follows normal distribution
- Sample size should be more than 30 
## Feature Scaling
- Min-Max Scaling 
	- (x-min(x))/(max(x)-min(x))
	- Sensitive to outliers
	- range: 0~1
- Z-score
	- range: -3 ~ +3
	- It is more robust to outliers because it uses standard deviation
## Converting Categorical Data to Numerical Data
- Integer Encoding
- One-hot Encoding
	- More unique values in rows, More memory size required
- Embedding

## Correlation
- Strong correlation => 0.7 ~ 1.0 (generally)
- Pearson Coefficient Correlation
		![[Pasted image 20240912185651.png]]
------------

# Today's Lecture
## Confidence Interval
- CI = population mean +- Z * population std
	 = mean +- Z * sample std / root(n)
### Law of Large numbers
### Level of Significance
### Z-value
- z-value: 2.58 = 99%
- z-value: 1.96 = 95%
- z-value: 1.645 = 90%
Two side / One side
## Hypothesis testing
- Z-test
	- Z-score
- T-test
	- T-score
- P-value
#### Probability Distribution curve
- p - value < a : reject null hypothesis
- p-value > a : accept null hypothesis
- z-score < Z-value : accept null
- z-score > Z-value : reject null