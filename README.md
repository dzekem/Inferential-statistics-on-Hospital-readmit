# Inferential statistics on Hospital readmit

Hospital readmit data contains hospital information about patient discharge and readmission rate.
Boostrap hypothesis test is used in this case where the null hypothesis is defined as mean of discharges equals 300 and the alternative hypothesis is defined as mean of discharges <> 300.

After computing the mean of boostrap replicates and the standard deviation, P value is calculated which ended up as p = 0.502. Since P is greater than 0.5, we therefore fail to reject the null hypothesis. Therefore the mean of discharges is 300 with a confidence interval of 357.80 : 370.82.

## Conclussion

- Also, the margin of error shows that from the 11494 samples of data taken, the approximations made are 93.5% accurate meaning there is a 6.5% possibility of errors
- Finally, the confidence interval gotten from the margin of error and z_score shows a range of possible discharge mean of [357.8 : 370.8] which is still close to the mean defined as the null hypothesis
- These analysis therefore shows that as the number of discharges from hospitals increases, rates of redmission reduces. Small hospitals are therefore ensured to use good quality drugs and services to ensure patients being discharged won't come back for admission.
