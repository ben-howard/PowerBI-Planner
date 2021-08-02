# PowerBI-Planner
A Power BI template file that imports plans exported from Microsoft Planner

The exported files can either be stored in a Windows folder ( eg c:\mydocs\plannerfiles) or a SharePoint folder (eg in the root URL of https://mvpapplepark.sharepoint.com/sites/PowerBIFolderRefresh and then within the folder /Shared Documents/General/Planner Files/ )

A .pbit is availalbe for both storage options.

Supported languages are English, French, Dutch, German, Spanish, Portugues (Brazilian) and Russian

https://www.youtube.com/watch?v=Ng8D5czMCuY
https://applepark.co.uk/planner-task-template-on-github/

Please note - the exported Planner Excel files need to be in a folder with no other files.  Power BI imports all the files in that folder, and if other files exist in there this will break the import.

Known issues - if you are not using a date format of DD-MM-YYYY you will need to change the regional settings to match your format once you have imported the template into PowerBI.  The setting is within the file | options dialogue box of Power BI.  
