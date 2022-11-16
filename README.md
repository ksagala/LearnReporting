# LearnReporting

This project is based on Learn Oranizational Reporting - https://learn.microsoft.com/en-us/training/support/org-reporting

To use Power BI template first you must configure receive datashare from Microsoft Learn to Azure SQL Database, as described in documentation.

Before importing this template, you must create additional table in database as described in https://github.com/ksagala/LearnReporting/blob/main/AADUserTable.sql

When you have additional table, you must import users from your Azure AD to this table, to see some additional information about users.

After you import pbit template, you must change tenant id in dataflows and npw it should works properly.
