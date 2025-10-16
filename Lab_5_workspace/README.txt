VM Name: dev-onboarding-jbc5
Developer Username: dev-jether
Developer Password: [your password]

Instructions to run scripts:

1. monitor.sh
   - Navigate to workspace scripts: cd /home/developers/IT-340-Lab-4-Repo/Lab_5_workspace/_scripts
   - Run: ./monitor.sh
   - This will log system info (uptime, memory, disk) to logs/system.log automatically every minute via cron.

2. timesheet.sh
   - Navigate to scripts folder: cd /home/developers/IT-340-Lab-4-Repo/Lab_5_workspace/_scripts
   - Run: ./timesheet.sh
   - Follow prompts for first name, last name, hours, and work description.
   - Logs will be saved in logs/timesheet.log and copied to data/timesheet.log
