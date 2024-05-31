# linux-backup-script

**Scenario**

A top-tech company currently suffers from a huge bottleneck - each day, interns must painstakingly access encrypted password files on core servers, and backup those that were updated within the last 24-hours. This introduces human error, lowers security, and takes an unreasonable amount of work. As a linux developer, create a script backup.sh which automatically backs up any of these files that have been updated within the past 24 hours.

Template script is provided by IBM. As such, no code prior to [TASK 1] is edited.

crontab is used to schedule the script to run every 24 hours.
