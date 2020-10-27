Update Management - Turn Off VMs
================================

            
This script is intended to be run as a part of Update Management Pre/Post scripts.

 

It requires a RunAs account, the module 'ThreadJobs' from the PowerShell Gallery, and the usage of the [Turn On VMs](https://gallery.technet.microsoft.com/Update-Management-Turn-On-ffadfc26) script
 as a pre-deployment script.

 

This script will ensure all Azure VMs in the Update Deployment are turned off after they recieve updates.

 

This script reads the name of machines that were started by Update Management via the
[Turn On VMs](https://gallery.technet.microsoft.com/Update-Management-Turn-On-ffadfc26) script


 



        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
