---
layout: default
title: Activities
nav_order: 4
---

# Activities

---

## Activity Summary

During the grant period (September 1, 2021 - August 31, 2022), the CHCD team's activities could be largely split into three areas: data preparation, technical development, and public outreach. Project team members were responsible for various areas of the project's development. In addition, Alex Mayfield was hired as the Project Director to provide both technical development support and to ensure that all project activities were completed in a timely manner.

In addition to the generous support of the National Endowment of the Humanities, the project team also received $100,000 in private donations during the grant period. This additional funding enhanced the stated goals of the project, namely by enabling more data collection during the project period.

---

## Data Preparation

As the core of the project, the process of data collection, cleaning, and integration made up a sizeable portion of all project activities during the grant period.

### Data Collection
A large portion of the data for the project was collected prior to the grant period. However, the additional funding from private donors allowed for an additional round of data collection to be included. Thus, from September to April, the project team oversaw dozens of students, volunteers, and partners as they collected additional data from French, Chinese, Spanish, Russian, and English sources. Notable contributions from this round of data collection include data on Russian Orthodoxy in China, early Protestant missions in China, and New Society Jesuits in China.

### Data Cleaning
The data cleaning process occurred in stages and at key junctures of the data collection process. From September to October, the data collected prior to the grant period was cleaned and prepared for the database. During this period, pertinent data from the defunct Ricci Institute's Roundtable Database was also incorporated into the dataset. Another round of cleaning took place from January to February to incorporate data collected during the fall semester. The final round of cleaning took place from April to May. This phase focused on removing duplicates, assigning unique ids, and incorporating data collected in the early part of the spring semester.

### Data Integration
In early June, the initial data was converted into CSVs and uploaded into a Neo4j graph database. After this initial upload, the project team oversaw a brief period of cleaning to correct any additional errors and to ensure that the data was in conformity with the database schema.

---

## Technological Development

Technical development activities can be largely broken into two categories: database development and online platform development.

### Database Development

Initially, the project team intended to create a data-input system that would enable partners to enter data directly into the database. In September, the project team was advised by members of other large database projects that such an approach would be cost- and time-prohibitive and prove less useful than desired. Thus, the project team was forced to rely upon pre-existing solutions. Thankfully, Neo4j, the graph platform used by this project includes a intuitive backend interface that enabled the project team to input and manipulate project data.

From November to December, the team implemented a draft Neo4j Community Edition database on a free Elastic Cloud Computing (EC2) instance on Amazon Web Services (AWS). Hosted using free tiers within AWS pricing schemes, this draft database hosted previously gathered data and allowed for application development. From May to June, the full-scale database was implemented using Neo4j Community Edition hosted on an EC2 reserved instance with AWS. During this time, a CSV version of the dataset was also stored on Boston University Library’s OpenBU platform and GitHub.

The choice to deploy the database with open-source and commercial solutions was a purposeful one by the project team. Widely supported by large technology companies, the technologies should be readily updateable and resistant to technological obsolescence. The CSV files stored with OpenBU provide a permanent repository for the database.

### Application Development

From September to April, the team oversaw the development of the online platform. The platform is a React JavaScript application that depends on several libraries for the design and data visualization, most notably Bootstrap.js, Leaflet.js, and D3.js. This platform was a major expansion and revisioning of the beta version which was created prior to the grant period. During this period, the project also entered into a partnership with students at Anderson University who were responsible for creating additional customizable graphs and charts using the data. Unfortunately, their work was not completed by the time of the project launch and will have to be incorporated at a later date.

From May to June, the online platform underwent a period of prolonged adjustments, bug fixing, and query tuning to ensure that the application was fully functional and user experiences were intuitive. The final product was uploaded to a GitHub repository so it can be easily utilized by other projects. In addition, the projects source code was stored in Boston University Library’s OpenBU platform.

---

## Public Outreach

As a project oriented towards data literacy and public engagement, outreach and publicity is as integral to the CHCD as data collection and technological development. One of the main ways this was achieved was through partnerships. During the course of the grant period, the project team worked with partners at over nine institutions to collect data and develop the project. These institutions include Boston College, Renmin University, the University of Naples, the University of Perugia, and Whitworth University. A second avenue of outreach was through scholarly meetings. Throughout the grant period, project team members presented on the progress and scope of the project via regional, national, and international scholarly meetings. As a third avenue of dissemination, the project team also published a technical essay about the project in _Digital Humanities 數字人文_. Finally, the project team produced a quarterly newsletter, _the Gazetteer_, that directly updated over 200 donors and interested parties about the progress of the project.

These various avenues ensured that our relevant audiences in the general public and scholarly community were informed of the status of project.
