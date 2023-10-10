# data_eng_practice

- find a REST API you like as a data source. Maybe stocks, sports games, Pokémon, etc.

 https://github.com/kyleconroy/deckbrew for Magic the Gathering cards. 
https://api.chucknorris.io/


 
 data quality, or write-audit-publish, or idempotency consideration

 
- learn Python to build a short script that reads that REST API and initially dumps to a CSV file

- get a Snowflake or BigQuery free trial account. Update the Python script to dump the data there

- build aggregations on top of the data in SQL using things like GROUP BY keyword

- set up an Astronomer account to build an Airflow pipeline to automate this data ingestion

- connect something like Tableau to your data warehouse and build a fancy chart that updates to show off your hard work!



More advanced topics:

1. start building that Python script in more detail, 
2. optimize it, use multiprocessing
3. write unit tests and implement CICD. 
4. Model the data and load using SQL aggregations


And then that's a more robust project to start as a DE. 
Add airflow, and dashboard as the next layer of complexity. 

https://medium.com/data-engineer-things/create-first-data-engineering-project-incremental-roadmap-6f0e66e7a5bf
