# Macchanger-For-Kali-

step 1
copy the file.txt script in the kali bash file
eg nano yourfilename.sh
past the script in the bash 

step 2
make that file executable
by 
cmd chmod +x yourfilename.sh

step 3
type the cmd 
crontab -e
press enter

it will tell you to enter the file type to edit 
so select the nano file 

step 4
type this cmd
@reboot filepath/yourfilename.sh
press ctrl+x
press enter

and all done

but is your cron.service is not running
then do 
systemctl start cron.service

and all set
