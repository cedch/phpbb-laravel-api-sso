# phpbb-laravel-api-sso
PHPBB Extension to authenticate with Laravel API (JWT)

#Installation
- Download phpBB
- Uncompress it
- go to localhost/{pathtphpbb}
- Go to the tab install
- Make sure that the files are writable (Check permission)
- Click on install
- Enter the administrator information and click on submit
- Enter the database info and submit
- Enter the email config
- Enter forum info and submit
- Rename the install directory
- Copy the laravel folder in the /ext directory
- Copy the parameters.yml in the /config/default directory

#Set User as admin through database
-To set a user as an admin from the database: set user_permission as _a

#Notes
-If you change the config, remove the cache