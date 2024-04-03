
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
So the risk assessment file would have the following columns. 

| Threat(s) |	Vulnerability Description	| Mitigating Factors or Compensatory Controls in Place	| 
| :---: |  :---: |  :---: |  

The ```Vulnerability Description``` means

The ```Mitigating Factors or Compensatory Controls in Place``` means 

<br/>

 
## Step 2 - Conduct the Risk Assessment

Now that we have entered our data for the above columns in Step 1 (the Threat, the Vulnerability and Mitigating Factors), 
we need to as objectively as possible quantify the likelihood and impact of each threat.

Using NIST SP 800-30 Appendix G and H tables, we can begin to accurately quantify the Likelihood and Impact of the Vulnerability to Falcone Systems.

Values can either be 
qualitative: 
| Very Low | Low |	Moderate| High	| Very High	| 
| :---: |  :---: |  :---: |   :---: |   :---: |  

or semi quantitative:
| 0 | 2 |	5| 8	| 10	| 
| :---: |  :---: |  :---: |   :---: |   :---: |  

<br/>


## Step 3 - Calcuating the Risk
 
From the 

- [x] Ensure comprehensive data collection during the interview.
- [x] Determine the implementation status of Media Protection controls.
- [x] Document evidence, noting both the provider and the nature of the evidence.
  
With the interviewees’ consent, the session was both recorded and documented through notes.

Data collection encompassed interviews, document reviews, and testing to verify active implementation of processes.

For any additional information or to address pending action items, quick follow-up communications were promptly executed via email and phone after the audit interview.

<br/>


## Step 4 - Post Audit Reconciliation (Data cleaning)

Our goal here is to ensure that we have collected all the necessary data. Any missing data must be gathered as soon as possible.
We are now starting to organize this data into the excel spreadsheet and inputting it under the following column headings.

Below is a sample.

| Data Collection |	Evidence Detail	| Findings	| 
| :---: |  :---: |  :---: |
| Interview |	Director of IT	| No controls in place	| 
| Tested |	Network Engineer	| Reviewed Documentation of Media Markings	| 

<br/>

Data Collection can be:
*	Interview form – can be via recorded Zoom or in-person.
*	Documentation – these are documentation provided by the interviewee.
*	Tested – a process that the organization currently uses.

Evidence Detail can be:
*	The person who provided the evidence.
*	A documented record or process.

Findings:
*	This is the information that was given by the Evidence detail. 
*	The findings here must be factually verifiable.


<br/>


## Step 5 - Analysis 

In this step, our objective is to assess the effectiveness of the security controls under audit. 

We've introduced a ```Disposition``` column with four predefined values to describe the status of each control:

- [x] Not in Place: Indicates that the security control is absent.
- [x] Not Applicable: Indicates that the security control is unnecessary or currently not relevant.
- [x] Partially Implemented: Indicates that the security control is only partially put into effect.
- [x] Fully Implemented: Indicates that the security control is fully in place and effective.
 
The Disposition value is determined objectively by evaluating the gathered data for each control. 
This assessment is conducted individually for every control included in the audit.

<br/>


## Step 6 - Reporting our Findings (Final Audit Report)

The Final Audit Report is compiled and presented. This an audit report and not a risk report. 
You can add the risk findings in the final report after a risk assessment if needed.
The final report is attched in this git repo as a pdf file ```Audit Lab Final Report v2``` 

Included in the final audit report are the following sections:

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

## Step 7 - Final Audit Report 
The full report is in ```Audit Lab Final Report v2.pdf``` in this git repo.

Sample screenshots. 
<br/>
<a href="https://ibb.co/PttdXY7"><img src="https://i.ibb.co/Bww9WPX/1.png" alt="1" border="0"></a>
<a href="https://ibb.co/MsfHgr2"><img src="https://i.ibb.co/s2C4gnm/2.png" alt="2" border="0"></a>
<a href="https://ibb.co/MVW4d1W"><img src="https://i.ibb.co/d21qZp1/3.png" alt="3" border="0"></a>
<a href="https://ibb.co/cNz2FsX"><img src="https://i.ibb.co/P5B1hVz/4.png" alt="4" border="0"></a>
<a href="https://ibb.co/S7gP9hw"><img src="https://i.ibb.co/dJvrzd4/5.png" alt="5" border="0"></a>
<a href="https://ibb.co/qsYryf3"><img src="https://i.ibb.co/Z8zMLPp/6.png" alt="6" border="0"></a>
