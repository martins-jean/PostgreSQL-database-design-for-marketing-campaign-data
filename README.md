# Marketing Database Design for a Bank

Authored a Python script that also uses SQL syntax to create the tables needed for a marketing database in PostgreSQL.

## Project Overview

In this notebook, I applied data engineering skills to clean data and design a PostgreSQL database. <br>
The objective is to store information about marketing campaigns run by a bank. <br>
I modified values, added new features, and considered how data should be stored within a PostgreSQL database efficiently and clearly. <br>

## Reproducibility Guidelines

<details>
  <summary>Data preparation</summary>
  1. Read the source data "bank_marketing.csv" as a Pandas DataFrame. <br>
  2. Split the data into three DataFrames: one related to client data, another to campaign data, and the third referring to macroeconomics. <br>
  3. Rename the columns to more descriptive names. <br>
  4. Replacing the values in many columns and creating new columns in the campaign DataFrame. <br>
  5. Save each DataFrame into its separate csv file. <br>
</details>

<details>
  <summary>Creation of the necessary tables using PostgreSQL</summary>
  1. Create the clients table. <br>
  2. Create the campaign table. <br>
  3. Create the economics table. <br>
</details>
