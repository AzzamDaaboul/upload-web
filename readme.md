##### I have start developing this website before two years and then I lost the domain upload-website.com :D 
##### I decide to make this project public 
##### this project has two sections 
#### first section 

I have developed the same idea as Codepen  with real time result with all the functionality 

#### second part 
(Upload your project part)

you have to zip your folder then upload the zip to main page  
now your files will go to public folder as new website and if you are working on Ubuntu, we have developed a way to create demo website 
or you can use it like yourdomain.com/yourproject/.... 

#### I will return back to fix everything I made before because my Laravel level was 0 :D (I will come back when i have time) 



# Installation on ubuntu 

### 1- sites-available and sites-enable  
give full permission to those two files 


### 2 - composit install 

 
  
### 3- inside Ubuntu etc there is sudoers.d folder 

inside this file we have 90-cloud-init-users file 

inside this folder just add

##  www-data ALL=(ALL:ALL) NOPASSWD: /etc/init.d/apache2 reload

to give permission for the normal user 



# Ubuntu Laravel installation 

sudo apt-get install php-mbstring

https://askubuntu.com/questions/764782/install-laravel-5-on-ubuntu-16-04


php artisan cache:clear 



inside the main conf we have to add 


 <Directory /var/www/html/public>
       AllowOverride All
     </Directory>
     
     
     
    ###### when i have time, I will rewrite the documentation again 
     
     
