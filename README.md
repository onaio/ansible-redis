# Redis

This role installs Redis and sets up backup

## Depends on
- [DavidWittman.redis](https://github.com/DavidWittman/ansible-redis)
- [onaio.backup](https://github.com/onaio/ansible-backup)
## Backup

The default configuration is to enable Redis backup. To disable it, set `redis_backup_enabled: "no"`

