---
title: 'Mautic 3 upgrade errors'
twitterenable: true
twittercardoptions: summary
articleenabled: false
orgaenabled: false
orga:
    ratingValue: 2.5
orgaratingenabled: false
personenabled: false
facebookenable: true
---

Did you get an error while running the Mautic 3 upgrade? We're here to help. Please look for the error code you got on this page for further instructions.

If you need any further help, please post into our MAUTIC 3 FORUM CATEGORY (TODO).

## Error codes

### ERR_DATABASE_BACKUP_FAILED
During the upgrade process, the script makes an attempt to back up your database. We make use of the command `mysqldump` in order to execute the backup process. 

If your migration fails in this stage, it is likely that an error was experienced when running the command. The error code displayed should give you some more information.  Your Mautic 2.x instance is intact.

To move forward from this stage, you will need to fix the problem that has been reported and restart the upgrade script. 

### ERR_MAUTIC_2_MIGRATIONS_FAILED
When Mautic 2 migrations fail

### ERR_DOWNLOAD_UPGRADE_PACKAGE_FAILED
When downloading M3 upgrade package fails

### ERR_EXTRACT_UPGRADE_PACKAGE_FAILED
When extracting M3 upgrade package fails

### ERR_MOVE_MAUTIC_2_AND_3_FILES
When moving M2 or M3 files fails

### ERR_UPDATE_LOCAL_CONFIG
When updating config/local.php with new M3 values fails

### ERR_MAUTIC_3_MIGRATIONS_FAILED
When running M3 database migrations fails

### ERR_RESTORE_USER_DATA_FAILED
When restoring user data (themes/plugins/media) from M2 fails

### ERR_BUILD_M3_CACHE
When building M3 cache fails

### ERR_CLEANUP_FILES
When cleaning up upgrade files fails
