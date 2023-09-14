# PostgreSQL database design for marketing campaign data

## Contextual overview

<p align="justify">
A bank needs to store the data from its marketing campaigns into a database for later analysis.
</p>

## Project objectives

<p align="justify">
1. To clean the data and to design a schema, we will use a python script. <br>
2. To store the data, we can then use PostgreSQL as a high extensible open-source database. 
</p>

## Reproducibility guidelines

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
