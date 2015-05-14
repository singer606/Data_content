# Data_content


How to run this application

1.)Ensure that you have the latest version of xampp installed( for php and mysql)

2.) create a directory called "harlem" and point it to http://localhost hence you will have

http://localhost/harlem/

3.) Very important: Configure the apache server to allow URL rewrite rules by copying and pasting of
.htaccess files into "harlem" directory you created

4.) Download the application from my account submission form in challengepost.com and paste all the script 
in the folder "harlem" that you created.


5.) To be able to manage Email Messaging System and to be able to send email notifications to all silicon harlem members when post/news hacthons were posted on the site

a.) Edit files "update.php" as per this line of code ($from = "email@yoursite.com";) to your working site email

b.) Edit files "company/ajax.php" as per this line of code ($from = "email@yoursite.com";) to your working site email

c.) Edit files "users_email.php" as per this line of code ($from = "email@yoursite.com";) to your working site email

d.) Edit files "school_email.php" as per this line of code ($from = "email@yoursite.com";) to your working site email



Special Warning: Posting of Silicon Harlem News, Hackthons,Events on etc. on the apps will not work fully unless all this Email files has been edited
as per requirements above. Again the files has to be hosted on a live server with internet connections..






6.) To be able to manage and Send SMS messages to Silicon Harlem members. the 2 files below takes care of it.

a.) school_sms.php

b.) users_sms.php

The coding has been implemented but you have to get/Buy your own SMS API Gateways. For instance from https://www.clickatell.com
Since this an open source, my sms paid sms API gateways has been removed from the above 2 mentioned files to avoid
exposing my account credentials and running down of my sms credit.


Consequently, if there is still need for the SMS workability, 2 the full sms code files above 
will be provided for testing purposes.
 


7.) download database file here and create database name: fb_wall1

8.) copy all the database table to create table

9.) call up the browser and run http://localhost/harlem/index.php

10.) you are done.





