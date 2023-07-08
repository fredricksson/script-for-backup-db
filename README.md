# Backup PostgreSQL db using sh file

## 1. fill some variable with your database data
#### go to pg_backup.config and fill the follow fiels
```bash
HOSTNAME=ip_of_your_db
PORT=5432
BACKUP_DIR=/home/username/backups/
PASSWORD=db_password
```

## 1. run script
#### run de pg_backup.sh script to make back up
```bash
bash pg_backup.sh
```