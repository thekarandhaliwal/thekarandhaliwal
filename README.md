sudo apt install httrack webhttrack  (For installing Httrack in ubantu)

pip freeze > requirements.txt (for creating requirement.txt file)
#cronjob
crontab -e (For apply a cron job to python file)
crontab -l (for verify a cron job is applied or not)

0 6 * * * /usr/bin/python3 /home/shrey/shrey/daily/single.py >> /home/shrey/shrey/daily/cronjob.log 2>&1 (for apply a cron job in which folder file have and log created location)
tail /home/shrey/shrey/karan/cron.log (for checking log of cronjob run or not and find run when file run using cron job)

vim file.py (for edit a file in server or in terminal)

rm (For removing file in ubantu)
rm -rf (For removing Folder in Ubantu)
