# Note
This is a subcode from my [MicrosoftEntra_AzureAD](https://github.com/asarejohn001/MicrosoftEntra_AzureAD) respiratory.

## Deprovision
The [Deprovision User Account script](DeprovisionUserAccount.ps1) will delete the user's account from Microsoft Entra. The script will:
1. Repeat steps 1 to 8 from the [User Account Provision script](https://github.com/asarejohn001/ProvisionAccount/blob/main/README.md).
2. Loop through the [CSV file](offboard.csv)containing the UPN.
3. Delete each user account.
4. Log into the [log file](Log.txt).
