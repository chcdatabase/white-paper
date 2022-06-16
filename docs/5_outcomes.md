---
layout: default
title: Outcomes
nav_order: 5
---

# Project Outcomes

---

## Overview of Initial Goals

The initial grant proposed to meet the following goals:
1. Create an initial database with over 400,000 data points
2. Produce an online data entry system that allows for streamlined data entry, and
3. Produce a fully functioning web application which will allow the public to interact with the data from the database.

As will be seen, Goals 1 and 3 were not only met but surpassed in every measure. The overarching intention of Goal 2 was met, however, the form needed to be adjusted for the sake of cost-effectiveness and efficiency.

---

## Goal 1: Database

By combining the data produced prior to the grant period with the data collected during the grant period, the CHCD surpassed its initial goal of having a database with over 400,000 data points. In its initial release, the database is comprised of:
1.  44,979 Nodes
   - 33,900 People
   - 6,488 Institutions
   - 1,155 Corporate Entities
   - 130 Events
   - 1,306 Geographic Locations
2. 208,237 Relationships
3. 1,916,717 Properties

This large number of nodes, relationships, and properties allows users of the database to create queries to study a diverse number of religious groups in China, and can be combined with other datasets to understand how Christianity affected historical happenings in China. The sources utilized to create this dataset are documented in the image below.

![CHCD Release Chart](https://raw.githubusercontent.com/chcdatabase/white-paper/gh-pages/assets/images/release_table_v1.png)

---

## Goal 2: Data Input System

Initially conceptualized as a way for partners to enter data, our experiences with bulk data-collection demonstrated that developing any backend-interface may be cumbersome and potentially slow the rate of data entry. In addition, such an interface would require a large amount of development time and an ongoing suite of trainings for partners. Upon advisement from experienced members of the digital humanities community and members of the project's board, the goal was adjusted for the sake of efficiency and cost-effectiveness.

Rather than develop a new system for data entry, the team focused on developing data collection processes and spreadsheet templates that would ensure accurate and cross-referenced data which could be cleaned and easily integrated into the database using customized queries. This approach leveraged pre-existing technologies and lowered the technical threshold needed for project participation.

Our [Bulk Data Collection Documentation](https://chcdatabase.github.io/data-collection/) is the core of our training materials for data collection. Likewise, our [Data Documentation](https://chcdatabase.github.io/data-documentation/) contains sample queries for data integration.

---

## Goal 3: Web Application

Building on the beta version produced through a prior grant, the funding from the National Endowment for the Humanities enabled a full-scale redesign and feature addition to the database. The [Beta Version](https://beta.chcdatabase.com/) was a basic, browser-based application that depended on JSON files to populate the various views. The beta version did not work well on mobile devices and it was not scalable.

In the [Release Version](https://data.chcdatabase.com/), the web application is a fully responsive React.js application that is directly linked to the database over an HTTPS connection. This responsive design allows for students, educators, and researchers to use the application on whatever device they use, and the direct linkage to the database ensures the application will automatically incorporate any additional data added to the database.

The final application has three "views" which allow users to interact with CHCD data in multiple ways. In the "search" view, users can search for specific entities in the database. In the "map" view, users can utilize filters to create customized maps of people, events, and institutions. On the "network" view, users can create customizable ego network visualizations. Importantly, each view is interactive and allows a user to click on database entities and pull up lists with all of their relationships and information. An additional "fourth" view was planned in coordination with students from Anderson University. However, this view remains in development and will be completed through future collaboration.

Like the rest of this project, the source code for this web application is freely accessible. The release version is available via GitHub and a archived version has been placed on Boston University's OpenBU platform.
