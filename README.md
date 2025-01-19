# Scheduled Backup Script

## Project Overview
This project automates the backup process for encrypted password files that have been updated in the last 24 hours. The script creates timestamped backups and schedules them to run daily.

## Features
 - Automated Backup:The script identifies encrypted password files updated within the last 24 hours and creates a timestamped archive.
 - Daily Scheduling: The script is scheduled to run daily using crontab to ensure regular backups.
 - Backup Integrity: The script performs extensive testing and validation to ensure it functions as expected.

## Accomplishments
 - Developed backup.sh to automate the process of identifying and backing up encrypted password files.
 - The script generates a timestamped backup archive (e.g., backup-[TIMESTAMP].tar.gz).
 - Configured the backup script to execute daily using crontab.
 - Ensured proper executable permissions for the script.
 - Verified the functionality by running extensive tests and capturing screenshots and logs of successful execution.

## Tools and Technologies
 - Shell Scripting: Used to write the backup logic.
 - Linux Command-Line Utilities: Tools like tar, find, chmod used to manage the backup process.
 - Crontab: Used for daily task scheduling.
