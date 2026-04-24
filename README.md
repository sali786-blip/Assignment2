# Assignment #2 Repository

This repository includes the simulated data for Assignment #2. Fork this repository and add your analysis as described in the canvas assignment.

The csv file for `cohort` in the `raw-data` folder includes 5,000 observations with variables `smoke`, `female`, `age`, `cardiac`, and `cost`.

Summary:

The raw data `cohort` did not have an associated data dictionary, so I was not sure what the 1s and 0s were coding. I assumed an entry of "1" meant true. So, if `female` had a 1, the participant was female. If `smoke` had a 1, then the participant was a smoker, etc. Also, I was not sure what `cost` referred to either. If I had to guess, it's the cost of some medical procedure?

There were 2866 females and 2134 males in the sample. Males had a slightly higher median `age` of 46 years compared to 44 years. Both males and females had similar rates of smoking at ~13%. The median `cost` for men was slightly higher than that for females. Interestingly, men had a higher percentage of cardiac events (~11%) compared to females (1.2%).  

My logistic prediction model tested the association between having a cardiac event and multiple demographic variables. My primary exposure of interest was smoking, and I controlled for age and sex. Not surprisingly, smoking status was very strongly associated with having a cardiac event (p < .001).

For my figure, I plotted `cost` between males and females. The distribution of cost was shifted slightly to the right compared to females.

I did not use generative AI (e.g. ChatGPT, Gemini, etc.) for this assignment.
