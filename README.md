List all VM's in all subscriptions in Azure and display running state and size
==============================================================================

            

This script display a list of all VM's created in all your Azure subscriptions and also displays if they are running or stopped and displays their size. The script not only shows VM's in the V1 portal (Service Manager) but also the V2 portal (Resource Manager).


For each subscription the scripts stores all VM's in two arrays (Service Mode and Resource Manager):




Collection of info about the V1 mode VM's is done as follows:






 
Collection of V2 mode VM's is a bit different because of the JSON output:







The output of the script is stored in an array and can easily be used to create reports or set up monitoring events.




        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
