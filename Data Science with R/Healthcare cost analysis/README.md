<h1>Data Scientist Assignments</h1>

<h3>Data Science with R Assignments - Healthcare cost analysis</b></h3> 

<b>DESCRIPTION</b>

Background and Objective:<br>

A nationwide survey of hospital costs conducted by the US Agency for Healthcare consists of hospital records of inpatient samples. The given data is restricted to the city of Wisconsin and relates to patients in the age group 0-17 years. The agency wants to analyze the data to research on healthcare costs and their utilization.

Domain: Healthcare<br>

Dataset Description:<br>

Here is a detailed description of the given dataset:<br>

Attribute	Description
Age 	Age of the patient discharged
Female 	A binary variable that indicates if the patient is female
Los	Length of stay in days
Race 	
Race of the patient (specified numerically)

Totchg	Hospital discharge costs<br>
Aprdrg	All Patient Refined Diagnosis Related Groups<br>
Analysis to be done: <br>

1. To record the patient statistics, the agency wants to find the age category of people who frequent the hospital and has the maximum expenditure.

2. In order of severity of the diagnosis and treatments and to find out the expensive treatments, the agency wants to find the diagnosis-related group that has maximum hospitalization and expenditure.

3. To make sure that there is no malpractice, the agency needs to analyze if the race of the patient is related to the hospitalization costs.

4. To properly utilize the costs, the agency has to analyze the severity of the hospital costs by age and gender for the proper allocation of resources.

5. Since the length of stay is the crucial factor for inpatients, the agency wants to find if the length of stay can be predicted from age, gender, and race.

6. To perform a complete analysis, the agency wants to find the variable that mainly affects hospital costs.

Download the dataset from here  

Disclaimer: In Business Analytics, there are different ways of solving the same set of problems. Feel free to explore other ways of answering these questions.

Good Luck!

</li>

<li>
Insurance factors identification<br>
<p>The data gives the details of third party motor insurance claims in Sweden for the year 1977. In Sweden, all motor insurance companies apply identical risk arguments to classify customers, and thus their portfolios and their claims statistics can be combined. The data were compiled by a Swedish Committee on the Analysis of Risk Premium in Motor Insurance. The Committee was asked to look into the problem of analyzing the real influence on the claims of the risk arguments and to compare this structure with the actual tariff.</p>

<p><strong>Domain:</strong> Insurance</p>

<p><strong>Dataset Description:</strong>&nbsp;<br>
The insurance dataset holds 7 variables and the description of these variables are given below:&nbsp;</p>

<div class="table-responsive">
<table class="table" style="width: 100%;">
<tbody>
<tr>
    <td><strong>Attribute</strong></td>
    <td><strong>Description</strong></td>
</tr>
<tr>
    <td>Kilometers</td>
    <td>Kilometers travelled per year&nbsp;<br>
    1: &lt; 1000&nbsp;<br>
    2: 1000-15000&nbsp;<br>
    3: 15000-20000&nbsp;<br>
    4: 20000-25000&nbsp;<br>
    5: &gt; 25000</td>
</tr>
<tr>
    <td>Zone</td>
    <td>Geographical zone&nbsp;<br>
    1: Stockholm, Göteborg, and Malmö with surroundings<br>
    2: Other large cities with surroundings&nbsp;<br>
    3: Smaller cities with surroundings in southern Sweden&nbsp;<br>
    4: Rural areas in southern Sweden&nbsp;<br>
    5: Smaller cities with surroundings in northern Sweden&nbsp;<br>
    6: Rural areas in northern Sweden<br>
    7: Gotland</td>
</tr>
<tr>
    <td>Bonus</td>
    <td>No claims bonus; equal to the number of years, plus one, since the last claim.</td>
</tr>
<tr>
    <td>Make</td>
    <td>1-8 represents eight different common car models. All other models are combined in class 9.</td>
</tr>
<tr>
    <td>Insured&nbsp;</td>
    <td>The number of insured in policy-years.</td>
</tr>
<tr>
    <td>Claims&nbsp;</td>
    <td>Number of claims</td>
</tr>
<tr>
    <td>Payment&nbsp;</td>
    <td>The total value of payments in Skr (Swedish Krona)</td>
</tr>
</tbody>
</table>
<strong>Analysis Tasks: </strong>After understanding the data, you need to help the committee with the following by the use of the R tool:</div>

<p>&nbsp;</p>

<ul>
<li>The committee is interested to know each field of the data collected through descriptive analysis to gain basic insights into the data set and to prepare for further analysis. &nbsp;</li>
<li>The total value of payment by an insurance company is an important factor to be monitored. So the committee has decided to find whether this payment is related to the number of claims and the number of insured policy years. They also want to visualize the results for better understanding.&nbsp;</li>
<li>The committee wants to figure out the reasons for insurance payment increase and decrease. So they have decided to find whether distance, location, bonus, make, and insured amount or claims are affecting the payment or all or some of these are affecting it.&nbsp;</li>
<li>The insurance company is planning to establish a new branch office, so they are interested to find at what location, kilometre, and bonus level their insured amount, claims, and payment gets increased. (Hint: Aggregate Dataset)&nbsp;</li>
<li>The committee wants to understand what affects their claim rates so as to decide the right premiums for a certain set of situations. Hence, they need to find whether the insured amount, zone, kilometre, bonus, or make affects the claim rates and to what extent.&nbsp;</li>
<li>Dataset attached in the Folder</li>
</ul>
