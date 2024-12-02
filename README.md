
About zipdevils

zipdevils is a Php-based security tool designed to crack zip files using bruit force attack. It helps recover a forgoten password.
Key Features

    it crack password using dictionary attack.
    if the password found in the list it extract the files to (files/) and tell you the exact password if found

Documentation
Prerequisites

To run the script, you need:

    xammp apache php server for windows or linux or KSWEB in android
    Required libraries: enable zip extesion in xammp or KSWEB in android,

Usage

put the extracted script in htdocs and open xammp or KSWEB in android control panel and click on admin


        

Example input: you can download rocyou.txt or create your own password file

   

passwords.txt

       12345
       ehjdjd
       shalom
       jjjdjjs
       321eie
     

      
        

    

 for cracking large file you must increase memory limit and uploads max size in php.in increase the limit as per your needs

     
 memory_limit=5000M 

     
upload_max_filesize=5000M 


     

