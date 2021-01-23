Preinstallations-1)XAMPP software

Steps-1)Install XAMPP on your system(preferably UBUNTU)
      2)Copy the NIT-CSE Folder in htdocs folder in Xampp.
      
        To find htdocs folder, computer--->opt--->lampp--->htdocs
        
        (you have to paste NIT-CSE Folder inside htdocs folder)
      3)Open Terminal on ubuntu and give following series of command
      ->cd /opt/lampp
      ->sudo ./manager-linux-x64.run
      
      Then enter your password
      
      4)Xampp software will be launched.
      5)On the top, click Manage Server
      6)On below there is a tab "start all" , click that tab.(you will see all three--mysql, apache server,ProFTPD start running)
      7)Minimize the Xampp software.
      8)Open browser.
      9)Type the URL localhost/phpmyadmin/
        You will see phpMyAdmin page --->Showing that everything goes correct till now.
      10)On the Top there is a tab "Databases", Click on it.
      11)Again You can find a Tab "import", click on it.
      12)A new page open where you can find "Browse", click on it to browse and select "nandy.sql" file provided.
      13)Now after selection scroll down and click "go".
      14)Now you are ready to view the site---"NITK-CSE"
         To view,a)Open a new tab in the browser
                 b)Type url http://localhost/NITK-CSE/
                 c)Now you can navigate through the sites

Technology Used--a)PHP----------For basic code
                 b)Javascript---Some Interactive Features
                 c)CSS----------For styling the web page
                 d)sql----------For database query
                 e)HTML---------For Body elements on web page
                 
software used----XAMPP(Provides tools--Apache server and Mysql database)

Tools------------a)Apache Server
                 b)Mysql database


# For login---There are two type of login
                 a)admin login------can change and update entire site and datbase.
                 b)faculty login----can view and update their profile over the site.
                   
                 c)Login and password for admin in table--"Admin"
                   sample--username=Admin
                           password=12345
                           
                   login and password for faculty in table--"h_faculty"
                   sample---username=Annappa
                            password=1234
                    

