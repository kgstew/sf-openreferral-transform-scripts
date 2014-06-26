sf-openreferral-transform-scripts
=================================

Testing forks...

A collection of transform scripts for taking raw San Francisco service provider data from different City Departments, and transforming it into the Open Referral specification.

This project is part of a movement to take data about social services including where they are and what they offer to whom, and transform it into a standard that can be shared broadly through the Ohana API and any other tool that supports the emerging Open Referral spec.

#Contribution guidelines
The first thing to do is to bring yourself up to speed on the emerging Open Referral spec and the implementation examples of Ohana API, Ohana API admin and SMC-Connect. Ohana API and related tools came out of a 2013 Code for America fellowship project in San Mateo County.

#High Level Timeline
March - May 2014: Prepare two to three social service datasets in the required JSON format.

Nat'l Day of Civic Hacking (end of May): Deploy Ohana API with 2-3 datasets. Work on admin console.

June - July 2014: Develop admin platform and simple frontend for database.

July - September 2014: Pilot program with Department of Children, Youth and Their Families in SF to update and maintain data in database.

October - ongoing: Work with other social services to provide admin interface for updating and maintaining data

#Quick and dirty tasks 4/9/2014

1. Look at the existing list of [datasets here](https://docs.google.com/spreadsheet/ccc?key=0ArHmv-6U1drqdGxmNTFwdjl5ckZUZmhGNFNzVWp4c3c&usp=sharing)
2. Copy over the promising ones to a [wiki page here](https://github.com/sfbrigade/sf-openreferral-transform-scripts/wiki/Data-Sources) under *Need to be worked on:*
3. Look them over and pick one to start working on, edit the [wiki page](https://github.com/sfbrigade/sf-openreferral-transform-scripts/wiki/Data-Sources) and move to *working on:*
4. Create a folder for your script named something sensible related to the data you're working on, the repo will have one folder for each dataset
5. Write an extraction script, if necessary, to get the data from the original source (website, PDF, or even printed document) to a basic spreadsheet
6. Write a transform script to transform into the format [documented here](https://github.com/codeforamerica/ohana-api/wiki/Populating-the-Postgres-database-from-a-JSON-file)

---------------------------------------


![The plan](https://raw.githubusercontent.com/sfbrigade/sf-openreferral-transform-scripts/master/plan.png)

