# To use this file, am assuming you have roots permissions

1. Clone this repo $bash: `git clone https://github.com/emekaorjiani/bashscripts` and `cd bashscripts`
2. Make executable $bash: `chmod u+x v-restore-user-cpanel`
3. Move to /usr/local/hestia/bin/ $bash:`mv v-restore-user-cpanel /usr/local/hestia/bin/`
4. Restore the backup by running $bash: `v-restore-user-cpanel username <backupfilename>`


This also worked better


wget https://raw.githubusercontent.com/hestiacp/hestiacp/feature/v-restore-user-cpanel/bin/v-restore-user-cpanel -O /usr/local/hestia/bin/v-restore-user-cpanel
chmod u+x /usr/local/hestia/bin/v-restore-user-cpanel