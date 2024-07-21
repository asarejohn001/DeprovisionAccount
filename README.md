# Note
This is a subcode from my [MicrosoftEntra_AzureAD](MicrosoftEntra_AzureAD) respiratory.

## Deprovision
The [Deprovision User Account script](DeprovisionUserAccount.ps1) will delete the user's account from Microsoft Entra. The script will:
1. Repeat steps 1 to 8 from the [User Account Provision script](UserAccountProvision.ps1).
2. Loop through the [CSV file](offboard.csv)containing the UPN.
3. Delete each user account.
4. Log into the [log file](Log.txt).
