# openshift project backup
This shellscript can backup single projects or all projects a user has access to in an Openshift cluster with the "oc" cli-tool.

The backup-tool combines the backup steps provided here https://docs.openshift.com/container-platform/3.6/admin_guide/backup_restore.html#project-backup to an "all-in-one" backup tool.

# Usage
<code>ocpbackup -h</code>

# Tests
Tested with Minishift 3.7
