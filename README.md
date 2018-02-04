# SSRS-WIXInstaller
Repo for creating WIX installer for SSRS deployment 

## WIX install command

msiexec /i MyReportsInstaller.msi REPORTSERVERURL=https://<SERVER_URL> ROOTFOLDER=<ROOT_FOLDER_PATH> DATABASESERVER=<DB_SERVER_INSTANCE> /l*v C:\MyReportsInstall.log
