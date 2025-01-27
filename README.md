# CODETECH-Task-2-4
# Name: Prajapati Udit Mukesh
# Company: CODTECH IT SOLUTIONS
# Id: CT12EHC
# Domain: SQL
# Duration: December 17th, 2024 - February 17th, 2025
# Mentor: Muzammil Ahmed

# Backup Process
Open SQL Server Management Studio (SSMS):

Connect to the SQL Server instance where your database resides.
# Run the Backup Script:

Execute the provided backup script to create a .bak file.
Make sure the folder path (C:\Backup\) exists and has appropriate write permissions.
Verify the Backup:

Navigate to the backup directory (C:\Backup\) to confirm the .bak file has been created successfully.
Restore Process
Prepare the Environment:

Ensure the backup file is accessible from the SQL Server instance.
If restoring to the same server, terminate active connections to the database.
Run the Restore Script:

Execute the restore script in SSMS.
Modify file paths for MOVE commands if the data and log files need to be restored to a different location.
Verify the Restoration:

Check the database in SSMS under the Databases folder.
Run queries to ensure the data has been restored correctly.
Handle Errors (If Any):

Review the error message in SSMS.
Ensure the .bak file path and permissions are correct.
# Key Notes
Schedule Backups: Use SQL Server Agent jobs to automate backups at regular intervals.
Test Restores: Periodically test the restoration process to validate backup integrity.
Secure Backup Files: Store backups in a secure location to prevent unauthorized access or data loss.

