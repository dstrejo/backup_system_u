## Automated Backup Script

This project contains a Bash script to automate the backup of important files or directories using `rsync` and `tar`. The script synchronizes the source directory with the destination directory and then creates a compressed archive of the synchronized files. It also logs the backup process and sends an email notification upon completion.

### Features

- **Synchronization**: Uses `rsync` to synchronize files between source and destination directories.
- **Compression**: Creates a compressed `.tar.gz` archive of the synchronized files.
- **Logging**: Logs the backup process to a specified log file.
- **Notification**: Sends an email notification upon successful backup completion.

### Requirements

- Bash shell
- `rsync` utility
- `tar` utility
- `sendmail` or `mailutils` for email notifications

### Optional
- Schedule a task to execute the script automatically. To do so, run crontab -e and modify it accordingly. 
