
## __Google Drive | Bash Curl Upload__ ##

### Overview ###

__Install__

- First Run: 
	- Configuration variables
	> Via terminal to connect with Google APIs.

### Upload ###

 - Default folder will be the root of Google drive.
 - To specify a directory pass the Google folder ID to the flag ``-r``

> Example: gdrive -r 9ts8gTlFzTV2clRSZlR0B0pgtUQ3

> > 28 long character Folder ID is: __9ts8gTlFzTV2clRSZlR0B0pgtUQ3__

> > drive.google.com/drive/folders/9ts8gTlFzTV2clRSZlR0B0pgtUQ3

 - Configurations file is stored at ``$HOME/.googledrive.conf``


### Dependencies ###

- Google APIs:
  > version: 2.0	
  - OAuth2.0 as a device
  - Generate access tokens to authorize application
  - Google Console
	- Client ID
	- Client Secret

- Curl
 	> Upload
	- files
	- directories

- Sed
	> Stream editor

- Find
	> Command

- Awk

- GetOpt
	> CLI Commands
