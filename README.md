# cronjob

* * * * * /usr/local/Cellar/flock/0.2.3/bin/flock -n /Users/adiallo/Desktop/cron/my.lock sh /Users/adiallo/Desktop/cron/compte_phones_number_aggr/compte_phones_number_aggr_run.sh

@reboot sh /Users/adiallo/Desktop/cron/compte_phones_number_aggr/compte_phones_number_aggr_run.sh

#* * * * * sleep 15; /Users/adiallo/Desktop/cron/compte_phones_number_aggr/compte_phones_number_aggr_run.sh
#* * * * * sleep 30; /Users/adiallo/Desktop/cron/compte_phones_number_aggr/compte_phones_number_aggr_run.sh
#* * * * * sleep 45; /Users/adiallo/Desktop/cron/compte_phones_number_aggr/compte_phones_number_aggr_run.sh

#crontab cron.txt 
#crontab -l
#crontab -e
