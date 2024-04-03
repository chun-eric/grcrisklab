
# Cybersecurity Risk Assessment Documentation/Walkthrough for Falcone Systems

### To see the full Final Report click on the attached ```Risk Assessment Lab Final Report v2.pdf``` located in this repository.

## Background
The Falcone Systems risk assessment is focused on assessing the risk from the Media Protection controls that were either partially in place or not in place at Falcone Systems. 
The risk assessment could be undertaken from the findings of the Falcone Systems Audit Lab. 

The goal of this risk assessment is found out the 

We structured the audit into six detailed steps, using NIST SP 800-30 Guide for Conducting Risk Assessments 2, which covers the protection of Controlled Unclassified Information in non-federal systems and organizations, 
as our primary reference. 

We then compared and aligned the security measures at Falcone IT Systems with the Media Protection controls from NIST SP 800-53 Revision 5, 
ensuring that they meet the requirements for safeguarding Controlled Unclassified Information.


Below are the steps we took to undertake this risk assessment.

<br/>

## Step 1 - Risk Assessment Preparation

In order to prepare for the risk assessment, we needed to identify the threats present first.

A modified threat list was compiled based of NIST SP 800-30 Appendix D and E.
Below is a snapshot example.


| Threat Source |	Threat	| Description	| Consequence |
| :---: |  :---: |  :---: |  :---: |
| Human intentional/Human Unintentional | Data modification/destruction/corruption | An improperly protected system |  Operational failure of Falcone Systems |
| Environmental/Natural |	Power Failure |	Inadequate power will adversely affect the availability of a system |	Without adequate power and backup power, the systems supporting Falcone Systems will not be available.  |
| Legal |	Policy Breach |	Inadequate power will adversely affect the availability of a system |	Without adequate power and backup power, the systems supporting Falcone Systems will not be available.  | The lack of policy or a violation of existing policy may open the up to litigation or result in serious damage to the 's reputation |
| Managerial |	Lack of Resources |	Resources, including personnel and life cycle replacement of IT components, if not adequately put in place, can cause system failures or inability to provide adequate support to the  mission  |	Without adequate resources, Falcone Systems has suffered single points of failure which caused repeated repair or reinvention of processes  |

We would then add the ```Threat``` column and add to our Audit excel spreadsheet.

A further two columns called ```Vulnerability Description``` and ```Mitigating Factors or Compensatory Controls in Place``` would be addeded. 
So the risk assessment file would have the following columns.  The column headings were taken and modified from Appendix I of NIST SP 800-30.

| Threat(s) |	Vulnerability Description	| Mitigating Factors or Compensatory Controls in Place	| 
| :---: |  :---: |  :---: |  

The ```Vulnerability Description``` means

The ```Mitigating Factors or Compensatory Controls in Place``` means 

<br/>

 
## Step 2 - Conduct the Risk Assessment

Now that we have entered our data for the above columns in Step 1 (the Threat, the Vulnerability and Mitigating Factors), 
we need to as objectively as possible quantify the likelihood and impact of each threat.

Using NIST SP 800-30 Appendix G and H tables, we can begin to accurately quantify the Likelihood and Impact of each Vulnerability to Falcone Systems.

Values can either be 
qualitative: 
| Very Low | Low |	Moderate| High	| Very High	| 
| :---: |  :---: |  :---: |   :---: |   :---: |  

or semi quantitative:
| 0 | 2 |	5| 8	| 10	| 
| :---: |  :---: |  :---: |   :---: |   :---: |  

After inputting all the data, we can move onto the next step.

<br/>


## Step 3 - Calcuating the Risk
 
Since all the data was inputted from step 2, this step is
now easy. 

Risk is calculated as:
```Likelihood```  X  ```Impact```

If a semi-quantitative approach was used then a final score out of 100 will be calculated.
For example: 
```Likelihood```  = 2
```Impact``` = 8
<br/>

``Risk``` = 2 x 8 = 16

A ```Risk``` of 16 out of 100 is considered low.
The image below shows an example using this approach.

![image](1)


If using a qualitative approach your results will be mapped to a risk assessment table
that will combine both likelihood and impact similar to the below table.

![image](2)

In our risk assessment report, we have gone the semi-quantitative approach.


<br/>


## Step 4 - Explaning the Risk

We would add an extra column to the risk assessment spreadsheet and call it ```Risk Explanation```.

```Risk Explanation``` can:
*	be concise.
*	explain the consequence for Falcone Systems if exploited.


Our goal here is simply to explain the risk of each vulnerability/control sorted by most severe to least severe. 
A good way to explain the risk is what would happen to Falcone System if this vulnerability was to be exploited?
What would be the consequences would this cause to Falcone Systems?

If a control is already in place and working as intendend, we would just skip it.

<br/>
<br/>



## Step 5 - Reporting our Findings (Final Risk Assessment Report)

The Final Risk Assessment Report is compiled and presented to board members and senior executives.
The final report is also attched in this git repo as a pdf file ```Risk Assessment Lab Final Report v2``` 

Included in the final Risk Assessment report are the following sections:

### Executive Summary 
  *	Overview: A concise overview of the audit’s objectives, scope, and main findings. Designed for high-level stakeholders.
  *	Key Findings: Highlights critical vulnerabilities or compliance issues.
  *	Recommendations Summary: Summarizes recommended actions.

### Objective & Scope
  *	Purpose of the Audit: Describes objectives and triggers of the audit.
  * Scope: Details examined systems, networks, and data.


### Audit Methodology and Standards
  * Audit Procedures: Specific procedures followed, including automated and manual checks. Listing the people the auditors interviewed.
  * What was Audited?
  * Methodology: Explains audit methods and tools.
  * Standards and Frameworks: Cybersecurity standards and frameworks used as benchmarks. This is the specific set of controls based off a framework such SP 800-171 or NIST CSF.

### Detailed Findings and Analysis
  * Security Controls Assessment: Effectiveness of existing security controls.
  * Compliance Assessment: Compliance with laws, regulations, and standards.
  *	Linking the spreadsheet so anyone can verifiably fact check.
  *	Vulnerabilities Identified: Detailed list of discovered vulnerabilities, categorized by severity.
  *	Optionally can add a High Level compliance status (e.g. Listing the top 25 controls and implementation status next to it)

### Risk Assessment (wait)
  * Risk Analysis: Identified risks based on likelihood and impact.
  * Risk Prioritization: Prioritizing risks to guide mitigation efforts.

### Recommendations and Action Plan (optional)
  *	Mitigation Strategies: Recommendations for mitigating identified vulnerabilities.
  *	Implementation Timeline: Timeline for implementing recommendations.
  *	As the auditor you could provide a fix in order to help ensure the org get compliant

### Conclusion
  * Overall Security Posture: Closing assessment of the organization's cybersecurity posture.
  *	Provide key takeaways from the audit such as critical issues and implementation recommendations. 
  *	Future Recommendations: Next steps for continuous improvement.

### Appendices
*	Glossary
*	Detailed Logs and Evidence – supporting documents and evidence collected
*	Audit Team Members

<br/>
<br/>

The full report is in ```Risk Assessment Final Report v2.pdf``` in this git repo.

Sample screenshots. 
<br/>
<a href="https://ibb.co/PttdXY7"><img src="https://i.ibb.co/Bww9WPX/1.png" alt="1" border="0"></a>

