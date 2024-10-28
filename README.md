java c
CS-GY 6083B, FALL 2024
Principles of Database Systems
Assignment: 2 [100 points - 5% weight towards final grades]
Problem 1: 50 points
LinkedIn innovation team has proposed a new tool iREAD (Innovative REsume
ADministration) with an idea that the team will create a repository of resumes in a
normalized database. This will facilitate recruiters to search candidates efficiently with flexible search criteria.
The following figure depict a sample resume.  You have been assigned a task to create a
normalized data model to ensure data consistency and integrity.  The innovation team has described following business rules.
a)  A candidate can have multiple skills.  In addition to skills, iREAD desires to store
proficiency (High, Moderate, Basic) of each skill possessed by the candidate. Please note that sample resume has not depicted such proficiency level.
b)  A candidate can have multiple education, experience, and certification entries.
c)  The database will have date formats for education, experience and certification as depicted in the sample resume.
d)  Each experience entry can have multiple entries for activities performed.
e)  Each candidate must have their LinkedIn page.

Normalized  resume data and create a database model with appropriate entities and relationships.
SUBMIT: a) Logical Model b) Relational Model c) Assumptions made about the business rules (other than stated in business case) d) DDL code.
Problem 2: 50 points
PAGE (Project Administration Global Excellence) is the project management consulting
company.  It provides its client project administration services. PAGE maintains their
business data into excel worksheet. However, with growth in company’s business, data
management has become tedious and erroneous. Also, data is stored in inconsistent format. PAGE代 写CS-GY 6083B, FALL 2024 Principles of Database Systems Assignment: 2
代做程序编程语言 has decided conversion of its dataset to relational data model. Your team has been  assigned the task to develop a well-defined relational database.  PAGE has identified
following requirements and rules.
A client can have multiple projects and project can be of multiple types (Radical project or Incremental project).
Client details should include Company Name, Company Address, name of project owner, and type of the company (Private or Public or Non-profit organization).If the client is public, PAGE wants to store public type (central, state, local government bodies), with name. Name will be null if it is central government, state name if it is state  government, and city name if it is local government).
If the client is private, PAGE wants to store name of the department and name of the department head.
For each project undertaken, PAGE wants to store project name, project description, project start and end date, project budget and name of the project manager.
For Radical projects, PAGE wants to store risk level (high, moderate, low), source of the fund (self/venture capital/bank loan/partnership).
For Incremental project, PAGE wants to store name of the existing product and reason for the change such as Opportunity/Enhancement/Defect resolution etc.
Using Oracle Data Modeler, develop an EER model with appropriate super-types and sub-types.Resolve any composite/multivalued/derived attributes, if any. For each attribute choose appropriate data type, their size and whether or not mandatory. Please  clearly state any assumptions that you have made, if any, in support to your ERD models.
In a single PDF document submit  a) Logical Model b) Relational  Model c) Assumptions made about the business rules (other than stated in business case) d) DDL code







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
