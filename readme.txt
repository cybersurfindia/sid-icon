These 3 files will be changed for new icons :
sd.css
sd.min.css
sd.svg


:: STEPS TO ADD NEW ICONS ::

Step - 1 -> rename all the files , from iconly to sd

Step - 2 -> open new "sd.css" file , replace "iconly" to "sd" 

Step - 3 -> open new "sd.css" file , remove !important from css

Step - 4 -> open new "sd.min.css" file , replace "iconly" to "sd" 

Step - 5 -> open new "sd.min.css" file , replace comments with this below:
                /*!
                *  sd-icon  v0.0.9
                *  sd-icon icon font.
                */

Step - 6 -> open new "sd.min.css" file , add this comment at the last line of file
                /*# sourceMappingURL=sd.min.css */

Step - 7 -> open new "sd.svg" file , replace "iconly" to "sd" 

Step - 8 -> Replace all the files old files to new files

Now The changes will be reflacted after 24 hours