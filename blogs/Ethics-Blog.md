---
title: "Beyond the Login"
date: 2026-10-21T21:29:21
draft: false
github_link: "https://github.com/baggapoonam"
author: "Poonam Bagga"
tags:
  - Markdown syntax
  - Sample
  - example
image: /images/MyEthicsBlog.png
description: ""
toc:
---

## Can Anonymous Surveys Truly Be Anonymous?

Before studying Data Analytics at TRIOS College, I believed that successful analysis depended mainly on technical skills such as Excel, SQL, data visualization, and statistical methods. This week's study of data ethics changed my perspective. I learned that even the most sophisticated analysis can produce misleading results if ethical concerns affect the quality of the data being collected.

One case that stood out involved a course evaluation survey. Students are required to log in using their username and password to access the survey, yet they are told that their responses will remain anonymous. As the data analyst responsible for providing recommendations to executive management, I must determine whether the survey data can be trusted and whether ethical concerns could affect the results.


This scenario highlights several important ethical concepts, including Privacy, Confidentiality, Trust, Transparency, Informed Consent, Bias, Accountability, and Data Integrity. More importantly, it demonstrates how ethics directly influences data quality and decision-making.

> #### Ethical concerns can impact data quality long before an analyst begins working with the data.


### Understanding the Problem

At first glance, the process appears straightforward. However, an ethical concern immediately emerges.

```html
In this scenario:
•	Students complete a survey at the end of a course.
•	Students must log in using organizational credentials.
•	The survey asks for the course name but not the student's name.
•	The survey claims responses are anonymous.
•	Executive management uses the results to decide which courses require redesign or improvement.
•	The data analyst must provide actionable insights based on the survey results.
```

At first glance, the process appears straightforward. However, an ethical concern immediately emerges.

> If students must log in before completing the survey, can they truly believe that their responses are anonymous?

Even if the organization has systems in place to separate login credentials from survey responses, participants may not understand how that process works.

> #####  Perception can influence behaviour just as strongly as reality when collecting data.

This concern forms the foundation for the four ethical questions explored below.

```html
Course Survey Results
         ↓
Used by Executive Management
         ↓
Course Improvement Decisions

If survey responses are biased, the decisions based on those responses may also be flawed.
```

### Question 1: Is the Survey Truly Anonymous?

The first ethical concern is whether the survey is anonymous or simply perceived as anonymous by the organization.
From a technical perspective, it may be possible to separate authentication records from survey responses. However, data ethics requires us to consider the participant's perspective as well.

```html
Participants may ask: 
•	Can my responses be linked back to me?
•	Will negative feedback affect my standing?
•	Who can access my responses?
•	Is the anonymity claim accurate?

```


If students doubt anonymity, their behaviour may change.


```html
For example:
•	They may avoid criticizing a course.
•	They may soften their feedback.
•	They may choose neutral responses instead of honest ones.
•	They may avoid participating altogether.

```


> ##### A survey can be technically anonymous, but if participants do not believe it is anonymous, their behaviour may change.

This demonstrates the importance of Privacy, Confidentiality, and Trust in ethical data collection.

### Question 2: How Does Privacy and Trust Affect Data Quality?

Before this week's learning, I viewed privacy mainly as a policy or compliance requirement. I now understand that privacy directly affects data quality.


##### 1. Privacy

Privacy refers to an individual's right to control how their information is collected, used, stored, and shared.
In this scenario, students may be hesitant to provide honest responses because they are required to authenticate before accessing the survey.

##### 2. Confidentiality

Confidentiality means ensuring that responses cannot be accessed, shared, or disclosed without authorization.

##### 3. Trust

When participants believe their information is protected, they are more likely to provide genuine feedback.

```html
Benefits include:
•	Increased participation
•	More honest responses
•	More representative data
•	Better decision-making
```

```html
Privacy Protection
        ↓
Participant Trust
        ↓
Honest Responses
        ↓
Reliable Data

```
> When trust increases, participants provide better data. When trust decreases, even a perfectly designed survey can produce unreliable results.

```html
Trust
   ↓
Honest Responses
   ↓
Reliable Data
   ↓
Better Decisions
```
> Trust is not a soft skill in analytics; it is a measurable factor that directly influences data quality.

```html
Reduced Trust
        ↓
Response Bias
        ↓
Reduced Data Quality
```
> Protecting privacy is not just about following policies; it is about creating an environment where people feel comfortable sharing honest feedback.

This was one of the most important lessons I learned from analyzing this scenario.


### Question 3: What Ethical Risks Exist in This Scenario?

Several ethical concepts introduced this week apply directly to this case.

##### 1. Lack of Transparency

Transparency requires organizations to clearly explain how participant information is collected, stored, and used. In this scenario, students may not understand:

```html
•	Why login credentials are required
•	How anonymity is maintained
•	Whether identities can be linked to responses

```
A lack of transparency can reduce confidence in the survey process.

##### 2.	Weak Informed Consent

Informed Consent requires participants to understand what information is being collected and how it will be used. Participants should know:

```html
•	Why the survey exists
•	Who will review the results
•	How anonymity is protected
•	How responses contribute to decision-making

```
##### 3.	Response Bias

Students who question anonymity may adjust their answers.
Potential outcomes include:

```html
•	Less criticism of course content
•	Underreporting concerns
•	Overuse of neutral responses
•	Incomplete feedback

```

##### 4. Reduced Data Integrity

Data Integrity refers to the accuracy, consistency, and reliability of information.
Biased responses may lead to inaccurate conclusions regarding course quality.

```html
Unclear Anonymity
      ↓
Reduced Trust
      ↓
Altered Responses
      ↓
Response Bias
      ↓
Reduced Data Integrity

```
> Not all data quality problems are technical; some begin with ethical concerns during data collection.

```html
Reduced Data Integrity
            ↓
Misleading Conclusions
            ↓
Poor Business Decisions

```

The biggest risk is that management may believe the results accurately represent student opinions whereas, in reality, the ethical concerns may have influenced responses.


### Question 4: What Should the Data Analyst Do?

#### •	Accountability

One concept that resonated strongly with me this week was Accountability.
As data analysts, our responsibilities extend beyond calculations, charts, and reports. We are also responsible for evaluating the ethical quality of the data we use.
If I were assigned this project, I would take the following steps:

##### 1.	Verify Anonymity Procedures

```html
•	Confirm how login credentials are separated from survey responses.
•	Validate that anonymity claims are accurate.

```
##### 2.	Improve Transparency

Recommend that participants receive clear explanations regarding:

```html
•	Authentication requirements
•	Data storage practices
•	Access controls
•	Privacy protections

```
##### 3.	Identify Potential Bias

Evaluate whether anonymity concerns may affect participant behaviour.

##### 4.	Protect Confidential Information

Ensure survey data is only accessible to authorized individuals.

##### 5.	Report Findings Honestly

Present results objectively while acknowledging limitations.

##### 6.	Communicate Limitations

Explain factors that may affect reliability and interpretation.


> ##### Responsible Analytics = Transparency + Privacy Protection + Accountability + Data Integrity

As data analysts, our responsibility extends beyond analyzing numbers; we must also evaluate the ethical quality of the data behind those numbers.

> Good analytics explains what the data says, while ethical analytics asks why the data may look that way.


#### •	Limitations 

If I were presenting findings to executive management, I would include an important limitation.
Because participants must authenticate before accessing the survey, some students may question whether their responses are truly anonymous.
This may result in:

```html
•	Less critical feedback
•	Reduced participation
•	Underreporting of problems
•	Response bias

```
Therefore, survey findings should be interpreted carefully when making decisions about course redesign.

```html
Perceived Lack of Anonymity
            ↓
Reduced Participation
            ↓
Incomplete Feedback
            ↓
Less Reliable Conclusions

```

Recognizing limitations does not weaken an analysis; it strengthens the credibility of the conclusions.

> Every ethical decision made during data collection has the potential to improve or weaken the quality of the final analysis.

Including such limitations demonstrates both Transparency and Accountability.


#### •	Personal Reflection

This assignment challenged my assumptions about data analysis.
Prior to studying data ethics, I believed that accurate results depended primarily on technical expertise. I now realize that Privacy, Trust, Transparency, Confidentiality, Informed Consent, Bias, Data Integrity, and Accountability influence the quality of data long before analysis begins.


```html
Ethical Decisions
        ↓
Better Data
        ↓
Better Insights
        ↓
Better Decisions

```

The most significant insight I gained was understanding the difference between actual anonymity and perceived anonymity. 

> ###### As discussed in Martens (2022), Data Science Ethics: Concepts, Techniques, and Cautionary Tales, data professionals must consider not only what can be done with data, but also what should be done. This idea helped me understand that ethics is not separate from analytics; it is an essential part of responsible analytics and decision-making.

Even when a system is designed to protect participant identities, people may still modify their behaviour if they do not trust the process.

> ###### The most important insight I gained was understanding the difference between actual anonymity (objective approach where true identity is completely unknown) and perceived anonymity (subjective approach as it is a personal feeling or belief that the identity cannot be identified, even if it can be).

This case reminded me that every dataset represents real people, not just rows and columns in a spreadsheet.

Every dataset represents real people, and maintaining their trust is one of the most important responsibilities of a data analyst.

> Every ethical decision made during data collection has the potential to improve or weaken the quality of the final analysis.


### Conclusion

This scenario demonstrates how ethical considerations can influence participant behaviour, data quality, and organizational decision-making. Although the survey states that responses are anonymous, the requirement to log in may create uncertainty that affects trust and introduces response bias.

Through this week's learning, I gained a deeper appreciation for the importance of Privacy, Confidentiality, Trust, Transparency, Informed Consent, Bias, Data Integrity, and Accountability in data analytics. These concepts are not separate from the analytical process; they are essential to producing reliable and meaningful insights.

As I continue my studies at TRIOS College, I aim to combine strong technical skills with strong ethical judgment. Data may drive decisions, but trust determines whether that data deserves to be trusted.

> #### Data Quality = Accuracy + Completeness + Honesty



> ##### Strong analytical skills help us understand data, but strong ethical principles help us determine whether that data deserves to be trusted.


> Skills Strengthened: 
Critical Thinking, Data Analysis, Ethics in Data Science, Reporting




