**White Paper**

Cover Page Image

![](C:\Users\ADMIN\Desktop\Projects\8 Securities\technologies.jpg)

**Title: How to achieve and maintain Optimal Security for your Enterprise REST API's**

**Table of Contents**

1. Introduction 

2. What you learn from this Whitepaper

3. Existing Problems

4. Existing Solutions

5. Proposed Solutions

6. Conclusion

#### **Introduction** 

Regarding REST API

#### What you learn from this Whitepaper

This whitepaper outlines the existing problems the REST API community is facing, pitfalls in the existing solutions and proposes a solution to enhance the overall security of the REST API's from all the dimensions i.e from "the security best practices to follow while planning, designing, and developing the REST API's" to "maintaining the optimal security by periodically scanning the REST API's with latest attacks and patterns".

#### **Existing Problems**

In the past few years, the IT world has seen a rapid growth in the digital services and majority of the technology companies are moving towards developing, implementing, and integrating the REST API's into their infrastructure. Any technology which is gaining such high interest from the community also requires high security but, unfortunately there is no all-in-one solution for REST API which can provide the enterprise developers with an approach to achieve optimal security at multiple stages of development and maintenance. With our presence and experience in the IT Security from the past 8 years, since 2012 and best-in class security experts, we have identified multiple problems at different levels of the enterprise organizations which are addressed in detail in this document.

###### **A Huge gap the entire REST API community is facing**

- REST API Development lacks a standard development life cycle approach

In comparison with the development life cycle approach followed for developing an application(Web/Mobile/Thick client) which involves planning, analysis, design, develop, implementing, testing, and deployment, there is no standardized approach being followed by the organizations for developing an REST API. 

###### **Gaps developers are facing**

- Lack of proper documentation

When an organization identified the need for the REST API implementation for their services, relevant developers are assigned to develop the work. Sometimes the tasks are assigned for the developers who are preoccupied with other workloads, assignments and targets to reach. Based on the business needs and executive decisions the developers are forced to complete the tasks in limited timelines which obviously leads to improper documentation.

###### **Gaps Testers are facing**

- Lack of necessary information 

Due to the lack of necessary documented information, testers responsible for functional, QA, and security testing of the respective REST API cannot perform a wholistic and in-depth reviews. 



Keeping the above mentioned problems in mind, we have analysed and observed most of the existing scanners from reputed organizations fail to identify some of the known vulnerabilities. Also, in some instances, we have seen enterprises turning to multiple service providers for documentation, testing and for security of their REST API's because there is no single solution available which can aid the developers in all the above aspects. 



#### **Existing Solutions**

###### **Automated Scanners**

Leading security scanners from the reputed organizations are failing miserably in finding vulnerabilities in the REST API's automatically. All the existing automated scanners are providing limited coverage because they fail in collecting necessary information from the customer at the first glance. The majority of the issues reported by these scanners are seen to be false-positives because the scanner is not equipped with the patterns which actually differentiates the false positives from actual vulnerabilities. Also, these companies fail in feeding all the latest patterns into the scanners from time-to-time since it involves a lot of research and development activity.

###### **Bug Bounty Programs**

However, turning to a bug bounty platform with crowd sourced hackers is also a common practice, this too has some limitations. 

1. Once the program gets kicked off, a lot of researchers will target and initiate testing on the target assets and the respective enterprise's mailbox will be flooded with huge number of reports and it requires more number of reviewers to analyse the reports.
2. Enterprises will receive a large number of duplicate reports with different attack patterns exploiting the same vulnerability. If the reviewers lack in understanding these scenarios, they end up in spending more money. 
3. Most of the researchers don't follow the scope and will report issues which are outside the acceptable target scope and demands bounty for those reports.
4. Also, very limited number of researchers follow manual approach for identifying vulnerabilities and majority of the researchers initiate automated scanners, fuzzers on enterprise assets which will make the application to go down.

###### **Security Companies**

A lot of information security organizations provide REST API security assessments but, majority of them 

1. Depend on the scanners which are used to find vulnerabilities in web applications. 
2. Do not have dedicated teams for assessing the REST API's. 
3. Lack in research on the latest development patterns and respective attack patterns.



#### **Proposed Solution**s

The below discussed scenarios, procedures and proposed solutions were the outcome of the research conducted over the years by the teams at Entersoft security.

###### Advanced Automated Security Scanner

After thoroughly analysing the existing REST API scanners, we have collectively decided to design a scanner with the below features which addresses the existing gaps.

1. Customers usually prefer scanners which require less configuration efforts but these scanners fail miserably in detecting complex vulnerabilities which require additional configuration details. We believe in "With ideal configuration comes the ideal outcome". Hence, we prefer to collect all the necessary information regarding the REST API endpoints and respective constraints before proceeding to scanning. 

2. With the collected necessary information, our scanning engine will create payloads rather than fuzzing the REST API endpoint parameters with random values. The generated payloads are actually useful in identifying complex vulnerabilities including input validations, injections, IDOR, Authorization, Authentication, and other Business Logic vulnerabilities. 

3. With more than 10+ years of experience in REST API security, our team has developed a list of all the vulnerabilities along with latest patterns and all of these are being feed into our scanning engine. 

   

###### Automated Industry Standard Documentation Creator for Developers

To help the consumers/end-users to easily interpret and integrate the REST API into their existing solutions and infrastructure, a standardized formatted document is the finest solution the developers can offer. Unfortunately, majority of the developers were not able to maintain these documents for a variety of reasons whether it could be time constraints, lack of skill to include relevant information, etc. So we created  a solution in the form of a portal where we collect all the necessary information regrading the REST API including the use case, endpoints(name, use case, role-matrix, method, headers, parameters, constraints), role-matrices, etc, and we provide the developers with a highly descriptive and standardized document.



###### REST API Development Life Cycle approach with inherent secure implementations

To help or aid the developers in developing REST API's, we came up with a solution which can offer a customized approach for different use cases(financial, healthcare, e-commerce, education, etc). In this approach, all the necessary information pertaining to the use case and implementation of the respective REST API are collected and a list of best possible security practices will be provided for the development teams which clearly explains what security practices should they follow and possible ways to implement those security practices with real world examples and sample configurations. For example,

1. Fetching a health record
2. Authenticating a User via OTP

[Rony, Please add some content like precautions to be taken at multiple stages like planning, designing and developing an API endpoint]



#### **Conclusion**

Achieving optimal REST API security involves adapting and following several procedures, practices, and most importantly the 

#### **References**

Gartner Magic Quadrant - Hype Cycle - 2019