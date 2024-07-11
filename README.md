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
        - [EHR Presentation](#ehr-presentation)
    - SQL
        - [Maji Ndogo Data Exploration](#maji-ndogo-data-exploration)
        - [Maji Ndojo Action Plan](#maji-ndogo-action-plan)
 
## Portfolio Projects
  In this section I will list data analytics projects, briefly describing the technology stack used to solve cases.

 ### EHR Presentation

 **Presentation:** [EHR System Presentation](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/EHR%20presentation.pdf)

 **Goal:** The goal of this project is to mitigating problems that people face in rural hospitals in regards to patient management, patient health records and resource allocation due to the lack of a digital patient management system which will help to  improve care coordination, providing doctors and patients with better access to test results, identifying missing patient information and may allow better care in emergency situations.

 **Description:** The project focuses on proposing an EHR system that will help to maintain accurate and accessible patient records.

 **Skills:** Presentation,data analysis, data visualization.

 **Technology used:** Microsoft Excel, Powerpoint Presentation

 **Results:** The implementation of an Electronic Health Record (EHR) system would automate processes, reducing waiting times, enabling efficient check-ins and providing real-time updates . Digital patient records would improve accessibility, accuracy and continuity of care. Additionally, the system would assist in resource management, optimizing bed allocation, equipment utilization and staff allocation. By embracing the EHR system, the hospital aims to enhance healthcare delivery, improve operational efficiency and increase patient satisfaction, ultimately benefits the local community.



 ### Maji Ndogo Data Exploration

**Project Overview:** This data analysis project aims to provide insights into water sources in Maji Ndogo that affect most people so that they can be improved to benefit the residents.

**Code:** [Data Exploration Project Queries: Maji Ndogo](https://github.com/ChantellZibi/Portfolio-Projects/blob/main/Maji%20Ndogo%20Data%20Exploration.sql)

**Description:** The database contains a water source table, a 'visits' table to record all the trips made to different water sources and the water quality table to find records   where the subjective quality score is within a certain range and the visit count is above a certain threshold.

**Skills:** Joins,CTE's, Windows Functions, Aggregate Functions, Creating Views

**Technology used:** SQL Server

**Results:** Looking at the river column, Sokoto has the largest population of people drinking river water so drilling equipment should be send out to Sokoto first, so people can drink safe filtered water from a well. The majority of water from Amanzi comes from taps, but half of these home taps don't work because the infrastructure is broken so engineering teams should be send out to look at the infrastructure in Amanzi first. Fixing a large pump, treatment plant or reservoir means that
thousands of people will have running water. This means they will also not have to queue for water, so this would improve two things at once.

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

