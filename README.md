# SnowTel
SnowTel Snowflake Query Telemetry in a Tableau Workbook

# Setup to Account Usage with SnowTel Workbook
Snowflake documentation on Account Usage and Query History would be a place to start if you are new to Query History in Snowflake. By default only the ACCOUNTADMIN Role has access to query these views. I have created the workbook for ACCOUNTADMIN and using DEMO_WH. If you do not have a DEMO_WH I suggest you set one up or alter the TWB as I describe here.
I have Tableau Desktop installed and licensed on my computer. Tableau offers a 14 day trial if you want to see what this workbook looks like on your Snowflake account and you unfortunately do not have a Tableau license. Get your Tableau trial here. Snowflake ODBC drivers for Tableau are required too, see here.
https://docs.snowflake.com/en/user-guide/odbc-download.html

# How to Use the SnowTel Workbook
You can grab a copy of the workbook (TWBX) from this GitHub (or if you need the TWB because a browser will think a TWBX is a zip archive also from this GitHub). The workbook is version 0.3 of what I plan to make many improvements on an almost monthly basis. I have it divided into 4 dashboards for now. Warehouse Health (WH - Query Time), Warehouse Query History (WH - Queries over Time) , Queries Dashboard and Users Dashboard respectively. Two informational sheets looking at the query hierarchy and a landing page are also included.

# Blog Article Explaining How to Read This
https://bigdatadave.com/2020/03/15/tableau-snowflake-snowtel-snowflake-query-telemetry-in-a-tableau-workbook/
