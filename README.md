#IRCapp (code by MrJ, design by Schickele)

##IRCapp is a small highly user friendly, cross-platform (Linux, Windows, Mac) download application for those who don't have the time to bother.

#Installation
Download at : <https://sourceforge.net/projects/ircapp/files/>

##Windows
Simply download and execute the setup.exe file

##Unix
There are currently two .deb files available.

*   FULL Version :  
    Use this version if you do not program python and didn't install any of the following packages (this is the dependency list):      
    
    *   irc
    *   requests
    *   cherrypy
    *   django
    *   pytz
    
    If you have these packages, there might be an error during the installation (file overwrite).
    Install with:          
    
        sudo dpkg -i IRCapp_1.1.1_full.deb

*   MIN Version :  
    Use this version in any other case. To install, run:         
     
        sudo apt-get install python3-pip
        sudo pip3 install django==1.8.5 irc requests cherrypy pytz
        sudo dpkg -i IRCapp_1.1.1_min.deb
*   In case you choose to clone the source code, for instance if you implement a server, you should run :
       
        sudo pip3 install django==1.8.5 irc requests cherrypy pytz rarfile
##OSX
I'm currently trying to get a Mac and will create a Mac distribution ASAP !

##Contact
ircappwebmaster@gmail.com

###To do's
This is an open-beta version (1.1.1).  
As such, a few major things still need to be done:  

*   Add OSX distribution
*   Clean up the code and add documentation (didn't really have the time...)
*   Add SSL support

###Added in 1.1.1 (since 1.1) :
*   Fixed an issue with item queue replacing
*   Completion time is now displayed properly
*   Version in the "about" box matches the current version



