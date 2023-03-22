# 1. Statistic

1st review: August 10, 2022
2nd: 12 days
3rd: 12 days
4th: 18 days
Date Created: June 29, 2022 9:59 PM
Final Review: August 31, 2022
Next Review: September 24, 2022
Property: July 6, 2022
Status: Not started
Studies: Revised x 1
Topic: Basic Science

### TYPES OF DATA - NORMAL vs NON-PARAMETRIC (❗️ )

- What other kind of data are there?
    - Data can only be categorical or measurement type
    - **Categorical data can be:**
        - **Nominal** Data = categories without order e.g. smoking status
        - **Ordinal** data = categories with order e.g. pain score
        - Either of them can be binary (2 categories) or non binary
    - **Scale aka Measurement Data can be:**
        - **Discrete** = only certain values possible e.g. number of admissions
        - **Continuous** = any value is possible between intervals.
- What do you do with the data?
    - After we obtain data, we want to analyse the data but, in order to know what tests we can use, we need to decide if the data is PARAMETRIC/ NORMAL or NON-PARAMETRIC
    - Depending on if the data is normal or not, we use different tests
- How do you know the data is normal?
    - Only scale/ measurement data can be normal. CATEGORICAL data CANNOT be normal.
    - 2 methods  to check of the MEASUREMENT DATA is normal:
        - **Graphical** method - Plot all data and see if falls into a bell shaped curve
        - **Statistical** tests e.g. Shapiro-Wilk or Kolmogorov-smirnov test

### CATEGORICAL DATA

- How are categorical data summarized and analysed?
    - As percentages or proportions
    - TEsted using Chi-squared or Fisher exact tests

### NORMAL/ PARAMETRIC MEASUREMENT DATA

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled.png)

- What does this show?
    - These are all **bell-shaped** curves of a ‘Normal’ distribution. aka Gaussian curve
    - x-axis represents a **variable** (let it be weight, height, Hb level, Na level, hip score, knee score, etc.)
    - y-axis represents the **frequency** of that variable.
- Why do you say this this is a normal distribution?
    - SYMMETRICAL bell shaped curves - same median, mode mean.
    - A normal distribution of data is one in which the majority of data are relatively similar, occurring within a small range of values such as height, weight, Hb level, K, Na, etc.
    - Plotting normally distributed data results in a bell-shaped graph as shown here.
    - aka **Gaussian** curve
- What is the significance of a bell-shaped curve?
    - It means that the data is **Symmetric with a single peak, and the mean, mode and median is the same**
- What are the measures for **central tendancy? [Descriptive Stats]**
    - Mode, median, mean
- ‼️ What are the measures for **dispersion? [Descriptive Stats]**
    - "Dispersion is the variability of a data set. If all values same, then dispersion is 0"
    - **1. Range**
        - **Range** is highest and lowest numbers
        - Further breakdown into **Interquartile ranges** - 1st and 2rd quartiles are the 1st SD
    - **2. Variance** = "measure of spread" = Sum of the squares about the mean of the data.
    - **3. Standard deviation** = square root of the variance
- What are measures used in **inferential** statistics? [**Inferential Stats**]
    - **Standard Error of Mean** = Standard deviation divided by square root of sample size
    - **Confidence Interval**
        - Only applicable to normal distributions (parametric data)
        - Calculated from the standard errors of mean
        - If 95% confidence intervals do not overlap, there is a significant difference.
- What are the standard deviations?
    
    ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%201.png)
    
    - SD indicates the **spread** of the curve
    - 1/2/3 SD - **68/95/99.7 rule**
    - I.e. 95% of the data falls within 2SD
- What is a statistical test for?
    - To evaluate if the difference is **due to chance or is a real difference.**
- What kind of tests do you use for normal aka parametric data?
    - I will use parametric tests e.g.
    - T-test
    - Chi-squared test
    - Fisher's exact test
    - ANOVA (for 2 or more samples)
- How do you test Correlation for normal data?
    - To check for correlation, I can use **Pearson** Correlation test

### NON PARAMETRIC MEASUREMENT DATA

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%202.png)

- What kind of data is this? Skew is to which side? Which colour line is what?
    - Look at the tail. If tail is on the left, then it is left-skewed. If tail is on the right, then it is right-skewed!
    - **Mean is affected more by the skew**, thus the mean is more lateral to the median.
    
    ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%203.png)
    
- What tests for non-parametric data?
    - Ordinal AND Measurement data (has order)- Mann-Whitney U, Wilcoxon
    - Nominal (no order) - Chi Squared tests, Fisher's test
- How do you test correlation for non-parametric data?
    - **Spearman** Correlation test
- Can you transform non-parametric data to normal data?
    - Yes, You can do logarithmic transformation or bootstrap technique

### Box and Whiskers Graph/ Box plot (❌ )

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%204.png)

- What is this graph?
    - It is a box plot. It is a way to present **non-parametric data** in a visual manner.
    - It compares the Oxford hip score changes between distressed and non-distressed groups of patients from preoperative level to 5 years after surgery.
    - It presents the bell curve in a different format - box and whiskers
        
        ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%205.png)
        
- What do the lines represent?
    - Looking at the first line on the left, it shows the pre op Hip score
        
        ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%206.png)
        
        - The **ends of the line** (whiskers)can refer to the minimum and maximum of all the data OR the 2SD
        - The **ends of the box** represents the first and third quartile
            - first quartile is the median of the values before the Median
            - third quartile is the median of the values after the median
        - The **line in the box** represents the **median**
        - The **circles** are outliers
- What is an outlier?
    - A value that is much larger or smaller than the rest of the data
- ‼️ What does the size of the box mean?
    - The shorter the box, the higher the agreement of the values (**higher precision**)
- Why is the median not in the middle of the box?
    - It means the data is skewed!

### Sensitivity and Specificity, PPV, NPV/ Screening/ likelihood ratio (❗️ )

- ‼️ What is sensitivity/ Specificity, PPV, NPV?
    - **Reality is the ROOF; so on top**
    
    ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%207.png)
    
    - Draw 4x4 table (sensitivity makes you go down, specificity makes you go up).
    - [https://www.youtube.com/watch?app=desktop&v=VI-5vAFEK3A](https://www.youtube.com/watch?app=desktop&v=VI-5vAFEK3A)
    - Sensitvity = TP/ TP + FN
    - Specificity = TN/ TN + FP
    - Sensitivity is 1 if False negatives are 0 = All the negative tests are really negative. Good to rule out - SNOUT [**Screening** test]
    - Specificity is 1 if false positives are 0 = All positive tests are really positive. Good to rule in - SPIN [**Confirmatory** test]
    - PPV and NPV are affected by prevalance
    - Accuracy is (TP + TN )/ ALL 4
- ‼️Definitions of PPV/ NPV/ Sn/ Sp?
    - PPV = Probabilty of being truly positive when test is positive
    - NPV = Probability of being truly negative when test is negative
    - Sensitivity = Probability of identifying a disease when disease is present
    - Specificity = Probability of excluding a disease when disease is not there
    - Accuracy = probabilty of **correct idenfication** of a disease
- Which is more relavant to the patient? Sensitivity or PPV?
    - Predictive values are more relevant because it tells them what is the chances of them being truly positive (or negative) as it also takes into account the prevalance of the disease in the population
- How can you increase sensitivity or specificity?
    - Increases **number of tests** (panel of tests)
- What kind of test will you choose to "diagnose as many as possible"?
    - Such a test will need to be highly sensitive, so that the false negatives are low.
    - But this is usually at the expence of high false positives
- What kind of test will you choose to "confirm diagnosis"?
    - it must be very specific because it there is very low false positive. If the test is positive, it is really positive.
- What is likelihood ratio?
    - Likelihood ratio is when the test is positive, the ratio of chance of truly having the disease to not having it.
    - LR = Sensitivity/ (1-Specificity)
    - The larger the likelihood radio, the "better' the test
- What is accuracy?
    - The accuracy of a test is its ability to differentiate the True positives and True Negative cases correctly.
    - Accuracy can be described by the area under the ROC curve
    - It is also TN + TP / (TN+TP+FP+FN)
- What makes a successful screening test? - (DDH, Scoliosis)
    - There are **three groups of criteria**
    - Disease Criteria (4)
        - Disease must have significant **impact**
        - Natural **history** of disease is known
        - Detection can occur before a **critical point** before being too late
        - There must be accepted and **effective treatment** available
    - Screening test features (3)
        - Accepted and tolerated
        - **High sensitivity** - Low false negatives (can catch more - if there are low false negatives, then there has to be false positives)
        - **High specificity** reduces false positive
    - Population features
        - Disease must have high enough **prevalance** [Scoliosis 3%, DDH 1:1000]
        - Patients willing to undergo treatment
- E.g. - Is US **screening** for DDH a good screening test?
    - This kind of question go straight into What makes a successful screening test based on the WHO 1968 guidelines
    - **Disease (4)** DDH has significant consequence, natural history is known (becomes OA), pavlik harness is effective, if intervene early at birth can avoid complications.
    - **Screening test (3)** simple to do and no radiation thus accepted, Low costs, US has high sensitivity and specificity
    - **Population (2)** - prevalence is 1 in 1000 or as high as 34 in 1000, parents are willing to have children undergo treatmetn
- What are the bias are screening tests susceptible to?
    - **Selection bias** only those who are more at risk (e.g. Family hx of cancer) are more likely to want to be screened ➔ makes the test look better than it is
    - **Lead time bias** Affects interpretation of 5 year survival rates - making it appear that people survive longer with cancer even in cases where the course of cancer is the same as those who were diagnosed later. It also adds anxiety to patient
    
    ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%208.png)
    

### Receiver Operator Characteristics ROC Curve (❌ )

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%209.png)

- What is this curve?
    - Graphic representation to compare accuracy of a diagnostic test
    - Can be used to explore the trade off between sensitivity and specificity of the test as you vary the threshold value
- How is the ROC plotted?
    - Basically using different cut off values for the same test and plot the sensitivity and 1-specificity on a graph
- What is the X and Y axis?
    - Vertical axis = true positive rate = sensitivity
    - Horizontal axis = false positive rate = (1- specificity)
    - Essentially, it is plotting the Likelihood ratio
- What is the area under the curve?
    - Area under the ROC curve = **accuracy**
    - Range is 0.5 (no better than random test) to 1.0 (perfect accuracy)
- Based on this curve, which test is good for screening and which good for confirmation?
    
    ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2010.png)
    
    - Good screening test will not have false negatives as it catches all the positive. So it must be high in sensitivity
    - Good confirmation test must be high in specificity (so 1-specificity will be low)
    - Choosing a cut off value for a perfect test will have trade offs.
- How can you improve the test?
    - Add more variables and the accuracy will improve overall

### [MA] Forest plot (❌ )

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2011.png)

- What is this?
    - This is a forest plot. It numerically and graphically represents a meta-analysis, combining a number of studies
    - **Describe column by column:**
        - List of studies and year
        - Number of outcome events vs sample size of control and intervention
        - Weightage - determined by the **precision of study** (sample size and confidence interval)
        - Treatment effect estimate - can be risk ratio, odds ratio
    - **Describe chart:**
        - Area of square = weightage
        - Lines = 95th percentile CI; the narrower the more previse
        - Line of no effect
        - If its at 0, it is a risk difference, if it is 1, it is risk ratio
        - If the line touches the curve, it is not significant
        - Overall effect is represented by a diamond
- What is MH?
    - M-H - Mantel Haenszel Test - this is a test used by the review manager developed by cochrane library to combine studies
    - Here it is [**Fixed**] this means it is fixed-effect model
    - In **fixed** effect, it is assumed that the size of the effect is similar in the included studies.
    - In **random** effect, it is used when the effects are not similar. e.g. studies using 2 different outcome scores to **measure outcomes.**
- What is the weight influenced by?
    - Sample size
    - **Confidence interval**
- What is confidence interval?
    - The 95% confidence interval is **a range of values that you can be 95% confident contains the true mean of the population**
- ‼️ What is homogeneity/ heterogeneity? How to test for it?
    - Studies have VARIATIONS in **methodologies** (randomization, blinding), **patients** (inclusion and exclusion), **interventions** (different dose, duration), **outcome** measures,
    - Variations lead to heterogeneity
    - Can be tested with the Chi2, or Q statistic
    - Cochrane software (revman) produces a number I2 - < 50% is low, 50-75% is moderate, > 75% is high heterogeneity
- How to **deal with heterogeneity?**
    - **Subgroup analysis** of studies that are more familiar
    - **Do not do meta-analysis,** just present as table
    - Use a **random** effect model of the mantel-haenszel test
- What is the difference between systematic review and a meta-analysis
    - SR - structured review that is more **qualitative** than quantitative
    - MA - more **quantitative** with the aim to get a combined and more precise estimate of an itnervention's effectiveness

### [MA] Funnel plots [Meta-Analysis] (❌ )

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2012.png)

- What is this?
    - A simple **scatter plot** of the **treatment effects** on the horizontal axis (can be risk ratio or odds ratio) aginast the standard error on the vertical axis [The higher up the Y-axis, the lower the standard error]
    - It is expected that **larger** studies, with larger sample size are more precise with low standard error and will be nearer to the **pooled effect** at the top of the plot
    - Smaller studies are scattered widely at the bottom
    - This gives a classical inverted symmetrical funnel
- What is standard error?
    - **Standard Error of Mean** = Standard deviation divided by square root of sample size
- What does asymmetry show?
    - **2 possible explanations**
    - The smaller trials of lower quality are **overestimating the true effect, hence they are on the right side of the pooled effect**
    - It might also **reflect publication bias** - where small trials that did not show benefit were not published (publicaiton bias)
- What are funnel plots used for?
    - 2 “P”s
        - Vertical funnel = **Publication** Bias
        - Horizontal funnel = **Performance** Analysis

### Horizontal funnel plots (#❌ )

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2013.png)

- What is this? [mortality rate]
    - Funnel Plot.
    - **Y-axis** = Standardized mortality ratio which is proportion of deaths compared to average
    - **X-axis** = Expected mortality
    - Data is risk-adjusted (Case-mix adjustement) to take into account different hospitals may operate on higher or lower risk patients due to demographics (e.g age)
    - **Green central line** denotes **average national expected mortality**
    - **Redline** denotes 99.8% confidence limit
    - **Progression along X-axis** means hospital has done more cases or cases at higher mortality risk
    - **Progression along y-axis** means have more deaths
    - Hospitals on either side of the green line but below the upper red line have a level of mortality within the expected range
    - Hospitals above red line have mortality rate higher than expected.

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2014.png)

- What is this? [revision rate]
    - Funnel Plot.
    - **Y-axis** = *Standardized revision rate* which is *proportion of revisions* compared to average
    - **X-axis** = *expected revision*
    - Data is risk-adjusted (Case-mix adjustement) to take into account different hospitals may operate on higher or lower risk patients due to demographics (e.g age)
    - **Green central line** denotes **average national *expected revision***
    - **Redline** denotes 99.8% confidence limit
    - **Progression along X-axis** means hospital has done more cases or cases at higher *revision* risk
    - **Progression along y-axis** means have more *revision*
    - Hospitals on either side of the green line but below the upper red line have a level of *revision* **within the expected range**
    - Hospitals above red line have *revision* rate higher than expected.
- How is the curves risk-adjusted?
    - “Surgeons with more cases have smaller allowance”, “Surgeons with lesser cases have larger allowance”
- What is other name for the outlier and those in normal range?
    - “Special cause Variant” = outliers
    - “Common Cause Variants” = those within expected range
- What is the criticisms for such analysis?
    1. Does not account the type of patients being operated on. 
        - E.g. Surgeons who operate only on high ASA patients, may be falsely attributed as an outlier
    2. May lead to bias. So in order to be the “low complication rate” surgeon, may choose only to operate on low risk patients to appear to be in the graph. 

### Survival Curves (#❗️ )

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2015.png)

- What is this?
    - This is a Kaplan Meir survival curve, comparing 3 different types of cements
    - it looks at **survival probability** and every time an event takes place, survival is recalculated
    - The midline is the mean value and the upper and lower lines represent the 95% confidence interval. The lines diverge as the graph moves right because there are fewer patients remaining in the study. With lower number of patients, precision of study becomes lower, confidence becomes lower, thus CI becomes wider.
    - Each downward step is an event. i.e. **outcome of interest**
    - **Censored** data - often presented as a vertical ticks are not seen here, but occurs when a patient dies, loss to follow up leads to incomplete data.
- What are the some assumptions in this curve? (3)
    - Patients who are censored have the same **survival prospects** as those who continue to be followed (they dont have other medical conditions that may skew the results when they drop out)
    - Survival probabilities are the same for patients recruited early or late in the study (all start with 100%)
    - Assume that the event happens at the time specified (the events/ dropouts are not happening at real time on the chart, they actually happen some time before the timing of audit but assumed it happened where it is marked)
- How do you tell if there is significant difference between the groups?
    - No overlaps in confidence intervals and p < 0.05
- What is the downside of this analysis?
    - Because the end point is revision, it does not capture data of patients who failed but did not go through revision
- What statistical test do you use to compared this 2 curves?
    - Log rank test aka Mantel haenszel test

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2016.png)

- Are you able to derive mean revision time/ rate from this curve?
    - No

![Screenshot 2022-09-09 at 3.48.52 PM.png](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Screenshot_2022-09-09_at_3.48.52_PM.png)

![Screenshot 2022-09-09 at 3.47.12 PM.png](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Screenshot_2022-09-09_at_3.47.12_PM.png)

![Screenshot 2022-09-09 at 3.49.06 PM.png](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Screenshot_2022-09-09_at_3.49.06_PM.png)

### Reading RCTs/ Error (#❗️ )

- What is confidence interval?
    - Confidence interval **shows the range the treatment effect** is likely to lie if the study was treated again
    - In other words, it the trial is repeated 100 times, 95 out of 100 times, it will be in that range
    - The narrower the CI the better. A wide CI means we are not confident of the range
- How is CI different to P values? What is P-value
    - P-value has **no correlation to treatment effect**
    - It merely calculates whether a treatment effect observed in a study is likley to have occured due to change
    - By convention, we use p< 0.05. This means there is a **5% risk that the result is due to chance**
    - if P value is 0.001, then there is 0.1% chance that the result is due to chance.
- Do you prefer to know the CI or the P value?
    - CI is preferable because they tell us the range of possible effect size
- What is the null hypothesis?
    - By default it is NO DIFFERENCE between control and intervention
    - If you reject null hypothesis means there is difference
- What is type 1 (alpha) error? How to reduce?
    - “no problem but think you have a problem”
    - Type 1 or alpha error is **False positive** i.e. wrongly rejecting null hypothesis
    - Reduce by reducing the P-value. But the drawback is that we will be less likely to detect a true difference if one truly exists
- What is type 2 (beta) error How to reduce?
    - “has problem but you do not detect the problem”
    - Type 2 or beta error is **False negative.** i.e. wrongly accepting null hyopthesis
    - Reduce by increasing sample size or ensuring the test has enough power to detect true change
- What is type 3 (gamma) error?
    - It is when we correctly determine a true positive (rejects null hypothesis). BUT for the **wrong reason**
    - I.e. **Misinterpretation** of cause and effect.
- What is risk ratio or relative risk and absolute risk reduction?
    - Is it used in **PROSPECTIVE** studies
    - Risk = probabilty that an event will occur
    - Risk is calculated by number of events/ all people exposed
    - **Relative Risk** = risk of exposed/ risk of non exposed
        - RR value 1 means no difference.
    - **Absolute Risk reduction (ARR) = Risk Difference (RD)** = exposed - non exposed
- What is the NNT?
    - NNT = number needed to treat to prevent one event
    - AAR = Absolute Risk Reduction
    - NNT = 1/ AAR
    - If AAR is 10%, then NNT is 1/0.1 = 10
- What is Odds Ratio?
    - Used in **retrospective** studies
    - Odds ratios are less logical and always overstate associations

![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2017.png)

- What can you interprete from the **PROSPECTIVE** study result?
    - Risk Ratio for prophlyactic Abx = 10/100 = 10%
    - Risk ratio for No Abx = 20/100 = 20%
    - Relative RIsk = 20%/10% = 2
    - What is the Absolute risk reduction or RD? = 10% (0.1)
    - What is the NNT? = 1/0.1 = 10. For one patient to benefit, need to treat 10.
- If it is **RETROSPECTIVE**, what can you interprete from here?
    - Odds of infection w antibiotics = 10/90
    - Odds of infection without abx = 20/80
    - Odds ratio = (10/90)/ (20/80)
    - Note that if the incidence of outcome is v v v v low then OR is about same as RR

### Designing RCT/ Power/ Randomization/ Bias/ Blinding (#❗️ )

- ‼️ How do you design a Randomized Control Trial
    - 4 **steps** - Lit Review, Ethical approval, Power analysis, Study Design. “aiming to reduce systematic Bias”
    - 1. Lit Review - PICO method
    - 2. Approval by ethical boards
    - 3. Power Analysis
    - 4. Study Design - **7 things that aims to reduce bias**
        - Selection from adequate patient groups - (**selection** bas)
        - Block randomization to achieve Equipoise (**allocation** bias)
        - Blinding - to reduce **performance** and **reporting** bias
        - Validated outcome measures - to prevent **measurement** bias
        - Appropriate analysis based on parametric vs non parametric data - to prevent **analysis** bias
        - Appropriate follow up - to prevent **follow up** bias
- How do you do a literature review before designing a RCT?
    - Before I begin, I will conduct a literature search with the PICO principle
    - P - patients, I - intervention, C - comparison, O- outcome
    - I would first search the highest level of evidence which are SR and MA. If none, I will search for primary trials.
    - If my search reveals there is lack of evidence to my question, I will then design a trial.
- What is the level of evidence?
    - Level 1 = RCT or Meta-analysis of RCT
    - 2 = Prospective cohort or MA of Cohort studies
    - 3 = Case control study or retrospective cohort
    - 4 = Case series
    - 5 = Expert opinion
- What is a good Randomized Control trial?
    - Patient selection - inclusion and exclusion criteria that allows generalizibiliy
    - **Randomization - Why? How?**
    - Blinding - Why?
    - Good Sample size - how?
    - Analysis - ideally by ITT - why?
    - Address bias - stratified analysis, mutlivariate analysis
- Advantages of randomization?
    - Purpose - to create **equioise** between control and trial group by equally distributing known **and unknown** patient variables that may potentially afffect outcomes
- How do you randomize?
    - **Simple** randomization. (head vs tails) But issue is due to chance, may not be same number in he group
    - **Block** Randomization
        - E.g. 5 groups of 20, then computer randomize
        - Advantage on top of simple randomization is that can start analysis even when you haven’t finish the number or when unable to recruit number of patients.
- Types of blinding?
    - Single vs double vs triple (assessor). But in orthopaedics, hard to blind the surgeon. You can blind the assessor and the patient.
- How to calculate sample size and power?
    - Done using power calculators - need 3 values
        - Decide **significance** level usually 5% (alpha)
        - Decide **study** **power** - usually 80%
        - Loss to follow up rate - approximate percentage
    - Choose primary outcome and from previous studies, decide **clincally important difference**
    - Calculator will tell us the number of patients needed per group.

---

- What is **bias**?
    - Flaw in **impartiality** that introduces **systematic error** into study
- Types of Bias? and How to address?
    - 7 main biases: SAFRA-MP
    - **Sampling** bias - *non- representative* selection of study sample
    - **Allocation** bias -  “allocation of subjects with *failure of randomization*”
    - **Performance** bias - “is *performance of the interventionist*, may be due to vested interest” ➔ need blinding
    - **Follow up bias -** unequal losses to follow up
    - **Measurement** bias - “Can be contributed by assessor who is doing measurement or patient who is biased for the treatment (maybe push for better ROM) → so need blinding
    - **Reporting** bias - “Due to inter-observer variability and reporting of results”, selective reporting
        - Need ICC (intraclass correlation coefficient) analysis
    - **Analysis** bias - wrong test used, failure to adjust for confounding
    
    ![Screenshot 2022-08-08 at 8.42.13 PM.png](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Screenshot_2022-08-08_at_8.42.13_PM.png)
    
- How to eliminate bias?
    - By looking at each domain and addressing them
    - Sampling - choose representative selection
    - Allocation - block randomization
    - Follow up - close follow up, patient contact
    - Reporting - reduce with peer review
    - Analysis - choose the appropriate test
    - Measurement - Use a validated test.
    - Performance - blinding

---

- What is confounder?
    - Variable that influences both the dependant and independant variable, causing a spurious association
    - For example, study on lung cancer and you want to investigate vegetarian vs non vegetarin impact. When actually, smokers who are less health conscious may be less inclined to be vegetarians.
- How to address condounders?
    - By study **design** - randomisation, blinding, stratify at collection
    - In **analysis stage** - Stratified (aka subgroup) analysis Multivariate analysis

---

- Considerations in Inclusion and exclusion criterias?
    - Participants should be representative of the population of interest
- Types of analysis approach?
    - **Intention to treat** - participants are analyzed according to the group allocated regardless of whether they continued with that treatment. **(gold standard)**
    - **Per Protocol -** Per-protocol only analyzes data from participants who follow the protocol, excluding their data after they become nonadherent.
    - **As-treated analysis** - AT analyses consider the treatment actually received by the participant, without regard to adherence to their randomization assignment
    
    [ITT, PT, AT.pdf](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/ITT_PT_AT.pdf)
    
- Which type of analysis is gold standard? Why?
    - AT and PP analysis loses the important effect of randomization of eliminating systematic bias in treatment assignment

### Outcome measures/ Grades of evidence

- What are the types of outcome measures?
    - **Clinician-based** outcome measure - E.g. Stulberg score
    - **Pateint-based** outcome measure (PBOM) - DASH score
    - **Hybrid** - e.g. Constant Murley Score
- What is a validated outcome measure?
    - It means it has been tested and succeeded to show that it measures what is suppose to measure
- How do you evaluate outcome measures?
    - 1. **Validity** - when comparted to gold standard, does this outcome measure predict the state of health?
    - 2. **Reproducibility** - intra and interobserver variation
        - Intra-observer - same observer retest
        - Inter-observer - agreement between 2 or more observers
    - 3. **Responsiveness** - ability to measure change as the status of pateint changes
    - 4. **Clinical Utility** - patient and clinician friendliness and comfort
- Examples of Outcome Scores
    - [http://www.orthopaedicscore.com/](http://www.orthopaedicscore.com/) - has all the scores and if PROM or CBOM
    - [Hip] Oxford Hip Score (PROM)
        - 12 question patient questionaire
        - total 48 points
        
        ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2018.png)
        
    - [Hip] WOMAC Hip Score (PROM)
        - Western Ontario McMaster University Osteoarthritis index
        - Patient questionaire on symptoms, stiffness, pain, daily living
    - [Shoulder] Rowe Score (Clinician + PROM)
        
        ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2019.png)
        
    - [Shoulder] ASES Score (PROM)
        - Americal Shoulder and Elbow Surgeons score
        - Unlike Constant Miurley score, physician assessment not included in final sport
        - Max score 100, weighted 50% for pain, 50% for function
            
            ![Untitled](1%20Statistic%20c775a8b0f9e741ab8288cf4ba9b76a42/Untitled%2020.png)
            
    - [Shoulder] Constant Murley Score (CMS) - **Physician assessment + questionaire**
        - The scale combines two fundamentally different metrics: **physical examination** findings of motion and strength (65 points), and **patient-reported** subjective evaluation of shoulder function (35 points)
        - 
    - [Shoulder] UCLA shoulder Score
        - University of Califormina Los Angeles Shoulder Score
    - [Upper Limb] DASH Scores (PROM)
        - Disabilities of the arm, shoulder and hand
        - 0 no disability ➔ 100 most severe disability
        - **30 question questionaire** on various activities, pain, weakness and stiffness
        - DASH score.pdf
        - QuickDASH score - 11 questions, 100 points also
        - QuickDASH.pdf
- What is grades A,B, C reccomendations?
    - A = means good evidence
    - B = means fair evidence
    - C = poor evidence
    - D = insufficient evidence or conflicting evidence

- How to measure interobserver consistency/ variability? What test?
    - Cohen’s kappa for 2 people
    - Fleiss Kappa for 3 people