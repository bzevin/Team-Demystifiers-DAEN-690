# Team-Demystifiers-DAEN-690
George Mason DAEN 690 Capstone Project Repository

## GMU Faculty and Researcher Experts List

**Product Owner:** Zevin, Benjamin  
**Scrum Master:** Margulies, Derek  
**Developers:** Ghyabi, Mehrdad | Munnangi, Karthik | Vangoor, Harshith  

**Client:** GMU C4I & Cyber Center  
**Project POC:** Dr. Linton Wells, ll  
**Knowledge Domains:** Systems Engineering, Data Engineering, Data Mining, Natural Language Processing(NLP)  
**Skill Sets:** Screen scraping, Natural Language Processing, Python  
**New/Follow-on Project:** New Project  

**Problem Description:**  
One of the frustrations here at the GMU C4I & Cyber Center has been not being able to find people rapidly who are working on related topics, be they AI, cybersecurity, European politics, community resilience, etc.  Mason tried to assemble an “experts” list a few years ago based on keywords, but it has been hard to keep current.
The project consists of four elements, data collection, natural language processing, database implementation, and database visualization and reporting.  The data collection is completed using self-built web scrapers for specific sources.  Natural language processing is completed using python to remove stop words and conduct cosine similarity to create scores between faculty members and research that represent how much research they are conducting in that area.  Next, the database is implemented in a graph database format due to its unique ability to visualize data.  The graph database will be implemented using Neo4j because it is one of the world’s largest graph database management systems.  It provides a “community edition” free and grants large enough storage to store all the data required for this project.  The final element of this project is to visualize the database in a simple and informative way to the user.  This process is completed using NeoDash, a reporting tool very similar to Tableau or Power BI.  However, it is unique because it is an open-source project designed specifically for Neo4j and graph databases.  This tool allows our team to create dashboards like Tableau but maintains a graph database visualization style.


**Project Goals:**  
A good data analytics problem for students might be to write a bot that would check out (a) bios for Mason faculty and researchers, (c) Google Scholar, ResearchGate, etc., to assemble lists of people working in particular areas. Some kind of Institutional Review Board (IRB) approval might be needed, but all the material would be public domain so it should not be a problem.
The optimal outcome of this project was to create a working prototype that could be re-run periodically to keep the roster of faculty and their research interests updated without burdening the scholars; due to unanticipated setbacks and problems with the standardization of the data collected. The project's goal shifted to making a working database that could accurately label the relationships between researchers and their interests that would have to be updated manually and would need to be maintained by an individual or team.


**Project Deliverables:**  
Showcase Presentation & PowerPoint Slides  
Final Project Report  
GitHub Repository for data and code artifiacts  
Working Prototype  

**Repository Contents:**  
The GitHub repository contains all the files not restricted by the university or LinkedIn.  The original taxonomy received from the university is not included, and the collected About sections and publications found on faculty members' LinkedIn profiles are not included.  The repository is split into five folders:
•	Data Cleaning: This folder contains all the files used for data cleaning or created from the data cleaning process.
•	Data Collection: This folder contains all the data collection files. This folder is where the self-built web scrapers are located.
•	Data: The folder contains all the data collected from the web scrapers or the final data generated through the data cleaning process and natural language processing.  
•	Database Files: This folder contains all of the files that are used to transform data to be passed into the database, the transformed files, and the database itself.
•	Natural Language Processing: This folder contains all the files used to complete the Natural Language Processing, such as the stop word removal and the cosine similarity.

