# Zabbix Windows Server Backup
Monitor Windows Server Backup Status from Windows Event Log. 

Requirements: 
- Windows Server 2008 or newer
- Zabbix 3.0 or newer
- Zabbix Agent Active Checks Enabled

# resources/items/triggers

- {$EVENTLOGFILTER} (macro) - This is a Filter for getting any Event ID except 14 (Backup task was finished) and 213 (The backup volume has been loaded)
- Backup Status (item)
- Backup Failed/Warning (trigger)
- No Backup Reported in the last 2 days (trigger)

# roadmap

- Install script

# installation

- import template

# contributors

Bruno Guilherme Souza (me)

