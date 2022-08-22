# OpenStack PowerShell rc
PowerShell Module to facilitate a user sourcing an OpenStack rc file. This allows a user to set and clear the variables from there WIndows system.

## Powershell Module to Source an RC file 
* **[Source Code](set-source.psm1)**  
_Allows for simple sourcing and removal of environmental variables utilizing WIndows Powershell_  

    **Usage:**
    
        Set-Source -Path project-openrc.sh
        Set-Source project-openrc.sh

        Remove-Source
