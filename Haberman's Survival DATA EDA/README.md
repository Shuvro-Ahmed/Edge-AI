Introduction
The Haberman's Survival Data Set is a dataset collected to study survival rates of patients who underwent surgery for breast cancer. This EDA provides insights into the dataset's variables and their relationships.

Key Observations:
Age Distribution:

The age distribution is right-skewed.
Most patients fall between the ages of 40 and 70.
Year of Operation:

The number of operations decreased over the years, with a notable drop after 1965.
Positive Axillary Nodes:

The distribution of positive axillary nodes is heavily skewed, with most patients having fewer than 10 nodes.
Survival Status:

There are more patients who survived for 5 years or longer than those who did not.
The dataset is somewhat imbalanced.
Age and Positive Axillary Nodes:

No strong linear relationship between age and positive nodes.
A higher number of positive nodes is associated with not surviving for 5 years.
Pairwise Correlation:

Variables don't show strong correlations, suggesting potential independent effects.
Survival Status and Age Distribution Comparison:

Age distributions for survival groups are somewhat similar.
Age distribution for non-survivors seems slightly wider.
Survival Probability by Positive Nodes:

Patients with fewer positive nodes have a higher probability of survival.
Mann-Whitney U Test:

No significant difference in age distributions between survival groups.
P-value of 0.329 suggests age might not be a strong predictor.

Conclusion:
The EDA of the Haberman's Survival Data Set reveals insights into factors potentially influencing survival after breast cancer surgery. While age and positive nodes show associations, the complex nature of survival requires more advanced techniques like machine learning models for accurate predictions. Interpretation should consider both statistical significance and domain knowledge.
