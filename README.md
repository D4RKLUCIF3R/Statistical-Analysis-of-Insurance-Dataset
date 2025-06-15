# Statistical-Analysis-of-Insurance-Dataset
Statistical Analysis of Insurance Dataset

\
The insurance dataset used by our team contains 1,338 policyholder records with seven core 
variables per row: age, sex, body mass index (BMI), number of children, smoker status, 
geographic region, and individual insurance charges. The data had no missing entries or 
duplicate rows originally.  
The age range for policyholders is 18 to 64 years, with a mean of 39.2 and a standard 
deviation of 14.1. The distribution was slightly right-skewed, meaning there was a heavier 
concentration of younger adults and a tapering tail toward the upper bound of 64. This skew 
suggested older policyholders were relatively less common in this dataset which could 
influence risk modeling if age interacted nonlinearly with other factors.  
The gender column is nearly balanced with a 51% male and 49% female ratio. Such parity 
ensured that modeling efforts could fairly assess sex-based risk differences without major 
imbalances. It also increased the generalizability of findings across male and female 
segments since both groups are nearly equal. 
BMI values ranged from 15.9 to 53.1, with an average of 30.7 and a standard deviation of 
6.1. This range of values captured both underweight individuals and reasonably overweight 
individuals. The distribution was right skewed because of a subset of high-BMI policyholders 
which highlighted a potential nonlinear relationship between BMI and healthcare costs. This 
seemed reasonable given the researched association between obesity and higher medical risk.  
Household composition, as measured by the number of children covered, had a range from 0 
to 5 with a mode of 0 as 36% of data subjects had no dependents. Since approximately one
third of the dataset consisted of single-adult policies, family structure could cause an increase 
of risk and cost patterns, especially when combined with other demographic factors. 
Smoker status showed that 20% of policyholders were smokers. Since smoking is a known 
major health risk, this subgroup was expected to drive medical costs higher. In fact, the 
inclusion of smoking status was critical for any predictive model of costs, as smokers often 
incurred frequent and expensive medical claims. 
The dataset was split evenly across four regions, namely northeast, northwest, southeast, and 
southwest, which minimized regional bias. This uniformity allowed for more reliable 
comparisons of regional cost differentials and ensured that no single area had 
disproportionately influenced our testing. 
Finally, insurance charges themselves ranged from $1,121.87 to $63,770.43, with a mean of 
$13,270.42 and a standard deviation of $12,105.49. The charge distribution was markedly 
right-skewed meaning a small subset of high-cost claims had increased the upper tail. This 
fact underscored the importance of considering robust modeling techniques or 
transformations when predicting or analyzing claim amounts.
