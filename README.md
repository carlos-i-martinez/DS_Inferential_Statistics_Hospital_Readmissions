# DS_Inferential_Statistics_Hospital_Readmissions

<B>Hospital Readmissions Data Analysis and Recommendations for Reduction</B>


<B>Background</B>

In October 2012, the US government's Center for Medicare and Medicaid Services (CMS) began reducing Medicare payments for Inpatient Prospective Payment System hospitals with excess readmissions. Excess readmissions are measured by a ratio, by dividing a hospital’s number of “predicted” 30-day readmissions for heart attack, heart failure, and pneumonia by the number that would be “expected,” based on an average hospital with similar patients. A ratio greater than 1 indicates excess readmissions.


<B>Exercise Directions</B>

In this exercise, you will:
1) Critique a preliminary analysis of readmissions data and recommendations (provided below) for reducing the readmissions rate.

<B>Preliminary Report</B>

Read the following results/report. While you are reading it, think about if the conclusions are correct, incorrect, misleading or unfounded. Think about what you would change or what additional analyses you would perform.

A. Initial observations based on the plot above
1) Overall, rate of readmissions is trending down with increasing number of discharges
2) With lower number of discharges, there is a greater incidence of excess rate of readmissions (area shaded red)
3) With higher number of discharges, there is a greater incidence of lower rates of readmissions (area shaded green)

B. Statistics
1) In hospitals/facilities with number of discharges < 100, mean excess readmission rate is 1.023 and 63% have excess readmission rate greater than 1
2) In hospitals/facilities with number of discharges > 1000, mean excess readmission rate is 0.978 and 44% have excess readmission rate greater than 1

C. Conclusions
1) There is a significant correlation between hospital capacity (number of discharges) and readmission rates.
2) Smaller hospitals/facilities may be lacking necessary resources to ensure quality care and prevent complications that lead to readmissions.

D. Regulatory policy recommendations
1) Hospitals/facilties with small capacity (< 300) should be required to demonstrate upgraded resource allocation for quality care to continue operation.
2) Directives and incentives should be provided for consolidation of hospitals and facilities to have a smaller number of them with higher capacity and number of discharges.


<b>Exercise</b>

Include your work on the following in this notebook and submit to your Github account.
A. Do you agree with the above analysis and recommendations? Why or why not?
B. Provide support for your arguments and your own recommendations with a statistically sound analysis:
1) Setup an appropriate hypothesis test.
2) Compute and report the observed significance value (or p-value).
3) Report statistical significance for  αα  = .01.
4) Discuss statistical significance and practical significance. Do they differ here? How does this change your recommendation to the client?
5) Look at the scatterplot above.

      a) What are the advantages and disadvantages of using this plot to convey information?
      
      b) Construct another plot that conveys the same information in a more direct manner.




Construct a statistically sound analysis and make recommendations of your own.

All exercise work and answers will be in the python jupyter notebook file named Inferential_Statistics_Hosp_Read_Final.ipynb


<B>Resources</B>

Data source: https://data.medicare.gov/Hospital-Compare/Hospital-Readmission-Reduction/9n3s-kdb3

More information: http://www.cms.gov/Medicare/medicare-fee-for-service-payment/acuteinpatientPPS/readmissions-reduction-program.html

