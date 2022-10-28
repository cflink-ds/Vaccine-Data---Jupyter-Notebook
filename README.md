# Vaccine-Data---Jupyter-Notebook

This is project that I worked on to help find answers to questions that were being asked by my work place. The data has been completely scrubbed of all PHI to stay HIPAA compliant. 

I started this project due to a report that had been run for years having the number of vaccines given not corelating with data presented by the individuals giving the vaccines and conducting their own tracking processes.

The data was housed on a SQL server and was being accessed through Microsoft Access through some queries and macros that were out of date and broken due to many factors, some known and some unknown. After working for weeks on troubleshooting and debugging the code and macros in Access, I then took another route. I used SQL queries that I wrote from scratch through SSMS to query the data correctly and pulled it all for data exploration as well as data cleansing.

I then followed the steps in the Jupyter Notebook to import the data and explore the data, deleting duplicates, dropping unwanted data points, and imputing missing values so the data could be used to answer the questions being asked.

I simultaneously created the same work flow in Microsoft Access so that others I work with that know next to nothing about SSMS, SQL, or Python could then run a macro that is not broken and attains the same data pull, cleanse, and imputation.

This data is now being used to audit the companies vaccine tracking/giving processes as well as answer any questions from Grant givers of how our vaccine program is benefiting our community.
