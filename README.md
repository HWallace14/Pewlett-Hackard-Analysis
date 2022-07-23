# Pewlett-Hackard-Analysis

## Overview

### Purpose

The purpose of this analysis was to help the company Pewlett-Hackard prepare for a large number of retirements that they know would be coming up soon. A lot of the employees are in higher-up positions and to not be prepared for such an event would court disaster, so they brought us in to help them get a list of each person, their title and the department they worked in. This was to be done using a collection of csv files that we were to upload to a database that we created and then we were to query the database in order to receive our answers. 

## Results

### Process

To be begin we outlined our schema to identify which bits of data each csv had in common. See below:

![EmployeeDB](https://user-images.githubusercontent.com/105998378/180622688-b66afdb3-06e7-4650-8ec7-a8c3ec3d2bd1.png)

Then we created our database and created the tables in order to upload our data to them:

<img width="355" alt="PHschema" src="https://user-images.githubusercontent.com/105998378/180622765-917e3e31-5d2e-4f90-9b87-525b462c9ec6.png">

After importing our data we began querying the different tables and creating new ones, tailoring our requests to whatever information the Pewlett-Hackard team needed.

### Querying

We began by searching for employees in the age range desired, querying for anyone born from 1952-1955. From there we filtered for employees still employed by the company and brought in the which department each person worked for. Finally, we brought in their title as of the latest date available. As we progressed we created new tables full of only the data that we needed and even exported those results into new csv files. We ended up with a total of 16 tables (shown below):

<img width="150" alt="Table_View" src="https://user-images.githubusercontent.com/105998378/180623054-93aa622f-a6f6-4bb5-86a6-76d45ebc8176.png">

### Summary

## Final Results

We found a total of 33,118 employees that would be retiring across 6 different jub functions from Staff members to Senior Engineer to Managers. In light of these findings the Pewlett-Hackard company asked us to look at potential recruits for a mentorship program that would be picked from a younger batch of employees. These employees would be used to mentor even younger associates and, should the program be a success and continue, should keep the "silver tsunami" of retirement from becoming as big of an inconvenience as it wound up being for the company.

We re-used our previous queries and tweaked them to find employees born in the mid-1960s, where we found roughly 1,549 potential candidates for the mentorship program. This information was given to Pewlett-Hackard's board right so that they could get started with their program immediately. I believe there are too few employees to completely stave off the ill effects of such a large portion of the workforce retiring, but they should be able to keep the company afloat until the mentorship program can do its job. 
