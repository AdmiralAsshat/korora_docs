How To Backup Your System
=========================

## Why You Should Make a Backup

A backup protects your files from data loss, malware infections, and inadvertent deletions. Storing your important files in a backup location allows you to restore those files to your computer should they ever be removed, go missing, or otherwise become corrupted.

## What to Backup

Ideally, you should be backing up all personal files and directories that are important to you. Only you can know for sure what directories are important to you, but it goes without saying that files such as pictures downloaded from your camera may hold more sentimental value than, say, your internet browser's cache.

If you wish to try to preserve your application data, you may need to research where each individual app of interest tends to store its data. If your application follows standard conventions, it likely stores its settings somewhere in the user's home directory. So it may not be a bad idea to backup:
- ~/.config
- ~/.local
- /opt (If you wish to backup the application itself)
- /usr/local/share
- /etc

Be aware that within application directories there may also reside cache subdirectories that can probably be excluded in order to reduce the size of the backup.

**NOTE**: "~/" is an alias to the user's home directory. So if you are logged in as 'guest', ~/.config would evaluate to */home/guest/.config* by the system.

## System Backup versus Personal Backup

## Backup vs Sync

## Backup Best Practices
### Test Your Backup
### Local and Off-Site Backups
### 3-2-1 Rule

## Getting Started:  Included Programs
### Déjà Dup
### Back in Time
### Third-party or DIY Solution