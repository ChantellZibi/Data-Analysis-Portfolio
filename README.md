# Chantell Zibi - Data Analyst Portfolio

## About
HI, I am Chantell Zibi! I am a Civil Engineering graduate who is transitioning into a Data Analysis. I have studied with ALX to attain a Data Analysis certification and I am looking to start a role as a Junior Data Analyst in the next month. When I am not in-front of a computer studying, I like to read self-help books and listen to podcasts. In the near future I look forward to being one of the most influential women in the Big Data industry, empowering young women to lead.

While I was in school, I worked hard to hone in my analytical and communication skills. I am focused and attentive to detail when addressing high-volume task loads to meet deadlines. I am inspired by making a positive impact by applying my interpersonal skills and my problem solving abilities allow me to address challenges to achieve results.

My academic experiences have served me well in developing my communication, decision making and problem-solving skills. I work well to use clear and concise communication to interact professionally with colleagues, supervisors and customers.

This is a repository to showcase my skills, share projects and track my progress in Data Analysis/Science related topics.

## Table of contents
- [About](#about)
- [Portfolio Projects](#portfolio-projects)
    - Presentation
        - [EHR Presentation](https://github.com/ChantellZibi/Data-Analysis-Portfolio/#ehr-presentation)
    - SQL
        - [Maji Ndogo Data Cleaning](https://github.com/ChantellZibi/Data-Analysis-Portfolio/#maji-ndogo-data-cleaning)
        - [Maji Ndogo Data Exploration](https://github.com/ChantellZibi/Data-Analysis-Portfolio/#maji-ndogo-data-exploration)
        - [Maji Ndojo Action Plan](https://github.com/ChantellZibi/Data-Analysis-Portfolio/#maji-ndogo-action-plan)
    - Power BI
        - [Data Visualization of Maji Ndogo](https://github.com/ChantellZibi/Data-Analysis-Portfolio/#data-visualization-of-Maji-Ndogo)
 - [Education](#education)
 - [Contacts](#contacts)

## Portfolio Projects
  In this section I will list data analytics projects, briefly describing the technology stack used to solve cases.

### EHR Presentation
 **Presentation:** [EHR System Presentation](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/EHR%20presentation.pdf)

 **Goal:** The goal of this project is to mitigating problems that people face in rural hospitals in regards to patient management, patient health records and resource allocation due to the lack of a digital patient management system which will help to  improve care coordination, providing doctors and patients with better access to test results, identifying missing patient information and may allow better care in emergency situations.

 **Description:** The project focuses on proposing an EHR system that will help to maintain accurate and accessible patient records.

 **Skills:** Presentation,data analysis, data visualization.

 **Technology used:** Microsoft Excel, Powerpoint Presentation

 **Results:** The implementation of an Electronic Health Record (EHR) system would automate processes, reducing waiting times, enabling efficient check-ins and providing real-time updates . Digital patient records would improve accessibility, accuracy and continuity of care. Additionally, the system would assist in resource management, optimizing bed allocation, equipment utilization and staff allocation. By embracing the EHR system, the hospital aims to enhance healthcare delivery, improve operational efficiency and increase patient satisfaction, ultimately benefits the local community.


### Maji Ndogo Data Cleaning
**Project Overview:** The aim of this project is to cluster our data, stepping back from the individual figures to gain a panoramic understanding. This bird's eye view will allow us to unearth broader narratives and hidden correlations concealed within the dataset.

**Code:** [Data Cleaning Project Queries: Maji Ndogo](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/Data%20Cleaning.sql)

**Description:** The database contains a water source table, a 'visits' table to record all the trips made to different water sources, the water quality table to find records   where the subjective quality score is within a certain range and the visit count is above a certain threshold and an employee table which has info on all of our workers, but then the email addresses have not been added.

**Skills:** Joins,CTE's, Windows Functions, Aggregate Functions, Creating Views

**Technology used:** SQL Server

**Results:** 
- Most water sources are rural.
- 43% of our people are using shared taps. 2000 people often share one tap.
- 31% of our population has water infrastructure in their homes, but within that group, 45% face non-functional systems due to issues with pipes, pumps, and reservoirs.
- 18% of our people are using wells of which, but within that, only 28% are clean..

### Maji Ndogo Data Exploration
**Project Overview:** This data analysis project aims to provide insights into water sources in Maji Ndogo that affect most people so that they can be improved to benefit the residents.

**Code:** [Data Exploration Project Queries: Maji Ndogo](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/Maji%20Ndogo%20Data%20Exploration.sql)

**Description:** The database contains a water source table, a 'visits' table to record all the trips made to different water sources and the water quality table to find records   where the subjective quality score is within a certain range and the visit count is above a certain threshold.

**Skills:** Joins,CTE's, Windows Functions, Aggregate Functions, Creating Views

**Technology used:** SQL Server

**Results:** Looking at the river column, Sokoto has the largest population of people drinking river water so drilling equipment should be send out to Sokoto first, so people can drink safe filtered water from a well. The majority of water from Amanzi comes from taps, but half of these home taps don't work because the infrastructure is broken so engineering teams should be send out to look at the infrastructure in Amanzi first. Fixing a large pump, treatment plant or reservoir means that thousands of people will have running water. This means they will also not have to queue for water, so this would improve two things at once.

**Recommendations:** 
- If communities are using rivers, trucks should be dispatched to those regions to provide water temporarily in the short term, while crews are send out to drill for wells, providing a more permanent solution. Sokoto is the first province that should be targeted.
- If communities are using wells, then filters should be installed to purify the water. For chemically polluted wells, we can install reverse osmosis (RO) filters, and for wells with biological contamination, we can install UV filters that kill microorganisms, but we should install RO filters too. In the long term, we must figure out why these sources are polluted.
- For shared taps, in the short term, we can send additional water tankers to the busiest taps, on the busiest days. We can use the queue time pivot table we made to send tankers at the busiest times. Meanwhile, we can start the work on installing extra taps where they are needed. According to UN standards, the maximum acceptable wait time for water is 30 minutes. With this in mind, our aim is to install taps to get queue times below 30 min. Towns like Bello, Abidjan and Zuri have a lot of people using shared taps, so we will send out teams to those towns first.
- Shared taps with short queue times (< 30 min) represent a logistical challenge to further reduce waiting times. The most effective solution, installing taps in homes, is resource intensive and better suited as a long-term goal.

### Maji Ndogo Action Plan
**Project Overview:** The goal of this project is to implement a plan in the database to improve water sources in Maji Ndogo by creating a table where our teams have the information they need to fix, upgrade and repair water sources.

**Code:** [Action Plan Project Queries: Maji Ndogo](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/Maji%20Ndogo%20Action%20Plan.sql)

**Description:** The database contains the addresses of the places the repair team should visit (street address, town, province), the type of water source they should improve, and what should be done to improve it.

**Skills:** Joins,CTE's, Windows Functions, Aggregate Functions, CASE function.

**Technology used:** SQL Server

**Results:** Addressing broken infrastructure offers a significant impact even with just a single intervention. It is expensive to fix, but so many people can benefit from repairing one facility. For example, fixing a reservoir or pipe that multiple taps are connected to. We identified towns like Amina,Lusaka, Zuri, Djenne and rural parts of Amanzi seem to be good places to start.

**Recommendations:** 
- Install UV filter or Install RO filter for improvement where the results of the pollution tests are Contaminated: Biological and Contaminated: Chemical respectively.
- Add Drilled wells to the improve all river sources
- Install one tap near each shared tap for every 30 minutes of queue time.

### Data Visualization of Maji Ndogo
**Project Overview:** These reports will aim to present the data in a manner that is not only accessible but also compelling, ensuring that the key messages resonate with stakeholders.  Focus will be on clarity and impact, ensuring that the information provided drives informed decision-making and strategy formulation. The goal is to make complex data comprehensible, engaging, and actionable.

**Description:** I utilized clean and intuitive designs with a colour scheme that subtly underscores the water crisis theme.I imported a table of Maji Ndogo's national water crisis with the following columns, hour of day (The hour of day at the time of record which will help aggregate the data by the hour of the day), day of week (The day of the week from the time of record which will help aggregate the data by the day of the week), percent male (The percentage of men in the queue at the time of record), percent female (The percentage of men in the queue at the time of record), percent child (The percentage of men in the queue at the time of record). I also imported the visits, water source, well pollution, project progress and infrastructure cost tables, ensuring a 1-to-1 or 1-to-many relationship, where appropriate,  between the tables. 

**Technology used:** Power BI

**Findngs 1:** With nothing selected, all of the metrics shown below are at the National level. The treemap shows how many people use the water sources per type of source, but its function is actually to select each source type. Filtering on sources can help engineers who are responsible for shared taps, for example, to see what they need to do Nationally, Provincially, rurally, and in each town.

**Findings 2:** We can see that in Amanzi, the average queue is mostly made up of men, while on a national level, it is mostly women. On Saturdays, queues across Maji Ndogo are 40% men, and on Mondays, 71% women. And when zooming in on 15:00 on a Saturday and see that the queue has only 3% children, while an hour later, the queue has 29% children.

**Findings 3:** 
- As water collectors, women are twice as likely to be a victim of crime than men.
- Women are most likely to be victims of harassment, followed by sexual assault.
- Crime spikes over weekends, and almost twice as many crimes are committed early in the mornings or at night with women again facing the greatest threat.
- In Amanzi, women face significantly less risk of being crime victims.
[Crime rate in Maji Ndogo based on gender](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/Crime%20rate.png)


## Education
ALX, Certification: Data Analytics, May 2023 - Dec 2023

The Vaal University of Technology, NDip: Civil Engineering, 2015 - 2019

### Certificates
The best way to showcase your skills is by sharing the work you have done but sometimes certificates appear to be as an indirect result. Here is a list of the certificates I have (in reverse chronological order, with completion dates in brackets):
- [Data Analytics Certificate](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/DAcertificate.pdf) (Dec 2023)
- [NDip: Civil Engineering](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/DAcertificate.pdf) (Sept 2019)

## Contacts
- LinkedIn: [@chantellzibi](https://www.linkedin.com/in/chantell-zibi/)
- Email: senate.bahlekazi@gmail.com
