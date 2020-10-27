Change-InsightsAlertsState
==========================

            

This Azure Automation runbook enables or disables all Application Insights alerts from resource group.



You can use this runbook to enable or disable alerts in 'microsoft.insights/alertrules' namespace. Script has been tested in two scenarios:


* Enable / Disable Application Insights web tests 
* Enable / Disable SQL Database alert rules


This runbooks needs AzureRunAsConnection.


You can find your alert names using Find-AzureRmResource cmdlet.




 




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
