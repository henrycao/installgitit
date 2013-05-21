installgitit
============

this is a gitit memorandum  
gitit can easily to setup a wiki website


#####installation guide  
    
    http://gitit.net/Installing
    
#####usage guide

    https://github.com/jgm/gitit

####notice

The origin version of gitit only allow 100K to upload.  
In order to change it, by using:

    gitit --print-default-config > mygitit.conf
    
change the parameter `max-upload-size`  
Then run  

    nohup gitit -f mygitit.conf &
