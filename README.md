# NTC-BUS-TICKET-BOOKING-SYSTEM

# Frameworks used

Platform	Framework
PHP Framework	CodeIgniter 3.1.5.
Admin UI Framework	matrix-admin Bootstrap.

# Library used

Name	Repository
Login Authentication	CodeIgniter-Ion-Auth.
Migration Authentication	codeigniter-ion-auth-migration.
Error Log	CodeIgniter-Log-Library.
Excel Export	Codeigniter-Excel-Export.
Core My_Model	CodeIgniter-MY_Model.
Translator	codeigniter3-translations.
Installation
Create first a databse named NTC_DB .

then just run/execute the website, tables in database will automatically migrate.

OR you can just import in databse a sample data from sample_data/ci_capstone.sql.

then if you just/want to rename the folder name, you will be required to set/modify the base url as the same of name of your new folder name.

# Note:

production ENVIRONMENT
compress html, for fast renderring page in live server
csrf_protection is enabled (set to TRUE), for prevent malicious/unnecessary behavior in submitting forms
errors log save to database,then not directly seen in browsers,
developing ENVIRONMENT
compress html disabled, for easy monitoring html output (easy debugging)
csrf_protection is disabled (set to FALSE), for easy submitting forms, for testing in big forms
errors log disabled, directly promt in browser,
database set to localhost
..
all is this set up in application/config/{ENVIRONMENT_FOLDER_NAMES}/config.php

# Thanks to our team.

Prageeth Thilina
Sakun Pushpitha
Menushi Lakshika

Any suggest/issue/problem dont hesitate to open an issue, even pull request. :)
