Date :2022/06/19- 2022/06/20

<h1>PHP</h1>
PHP : Hypertext Preprocessor

Is a widely-used, open source scripting language PHP scripts are executed on the server PHP files can contain text, HTML, CSS, JavaScript, and PHP code PHP files have extension ".php"

To setup php u can simply download the XAAMP given in the link below:
        https://www.apachefriends.org/download.html

What Can PHP Do?

PHP can generate dynamic page content.
PHP can create, open, read, write, delete, and close files on the server.
PHP can collect form data.
PHP can send and receive cookies.
PHP can add, delete, modify data in your database.
PHP can be used to control user-access.
PHP can encrypt data.
SYNTAX :
   <?php 
    PHP code goes here 
   ?>

ECHO:
It is used to output data to the screen.
The echo statement can be used with or without parentheses: echo or echo().
Example :
<?php                                                 
 echo "MY NAME IS SHIRISH";                                       
 echo ("SHIRISH");                                    
 ?>
 
 Output : 
    MAY NAME IS SHIRISH
    SHIRISH
Here, regardless of the parantheses both output results are displayed.

Virtual Host
A virtual host is used for hosting multiple domain names on a single server.

Create a folder in htdocs of xammp then write php code syntax: <?php> echo "Echo is use to print in php" ?>

Open apachi > conf >extra >httpd-vhosts.conf in notepad (run as administrator) Then add:

 DocumentRoot "C:\xampp\htdocs\folder location"
 ServerName name.local
</VirtualHost>
then save

Then open C:\Windows\System32\drivers\etc\hosts in notepad add 127.0.01 name.local then you are ready to go:search localhost/location of your directory