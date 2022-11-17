# LearnReporting

This project is based on Learn Organizational Reporting - https://learn.microsoft.com/en-us/training/support/org-reporting

Original pbit template was published by Microsoft on https://github.com/MicrosoftDocs/mslearn-organizational-reporting (UPDATE - recently updated two months ago after a year of inactivity). Here is my own version with certification part prepared by myself. Of course everyone can modify it accourding to specific company requirements.

To use Power BI template first you must configure Azure Data Share service (only receive datashare) to synchronize data from Microsoft Learn to internal Azure SQL Database, as described in documentation mentioned above.

Before importing this template, you must create in this Azure SQL database additional table with script published here https://github.com/ksagala/LearnReporting/blob/main/AADUserTable.sql, because data synchronized from Microsoft Learn doesn't include any personal data - only user id.

So user names must be imported from Azure Active Directory (manual import also mentioned in documentation) to have any information about learn and certification progress.

There are only first names published in dashboard to make it more user friendly.

When you have additional table, you must import users from your Azure AD to this table, to see some additional information about users.

After you import pbit template, you must change tenant id in dataflows and npw it should works properly.
