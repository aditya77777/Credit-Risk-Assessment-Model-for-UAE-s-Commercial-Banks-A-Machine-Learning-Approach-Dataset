# Credit-Risk-Model-Dataset
Credit Risk Model on Machine learning and prediction

Dataset

Dataset used is the pooled collection of both accepted and rejected applications from different commercial banks of UAE having a debt ratio between 0 – 1. The data content is composed of 7778 cases. In the provided sample, 292 (59.3%) applications were creditworthy while 200 (40.3%) applications were not. The data collection resulted in a total of 12 variables: with 11 being input variables and being the output variable. The definition, coding, type, and descriptive of each of these variables are shown in Table 1.

Variable	Key	Type	Variable Definition
Resolving the utilization of unsecured lines	P1	Scale	This attribute indicates the credit card limits of the borrower after excluding any current loan debt and real estate.

Age	P2	Scale	Applicant’s age
Number of Time30-59 Days Past Due Not Worse	P3	Scale	The number of this attribute indicates the number of times borrowers have paid their EMIs late but have paid them 30 days after the due date or 59 days before the due date.

Debt ratio	P4	Scale (0 – 1)	If my monthly debt is \$200 and my other expenditure is \$500, then I spend \$700 monthly. If my monthly income is \$1,000, then the value of the debt ratio is \$700/\$1,000 = 0.7000

Monthly income	P5	Scale	Total monthly income, and used log for transforming it.

Number of Open Credit Lines and Loans	P6	Scale	This attribute indicates the number of open loans and/or the number of credit cards the borrower holds.

Number of Times 90 Days Late	P7	Scale	This attribute indicates how many times a borrower has paid their dues 90 days after the due date of their EMIs.

Number Real Estate Loans or Lines	P8	Scale	This attribute indicates the number of loans the borrower holds for their real estate or the number of home loans a borrower has.

Number of Time 60-89 Days Past Due Not Worse	P9	Scale	This attribute indicates how many times borrowers have paid their EMIs late but paid them 60 days after their due date or 89 days before their due date.

Number of Dependents	P10	Scale	This attribute is self-explanatory as well. It indicates the number of dependent family members the borrowers have. The dependent count is excluding the borrower.

Outcome	Output	Binary	Good Creditor or Bad Creditor
