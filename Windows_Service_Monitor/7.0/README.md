<h1>Windows Service Monitor</h1>

This is a Zabbix template which performs a low-level discovery of Windows services that are running on a server, and then creates a trigger for each discovered service to go off when the service is in any state other than Started.

The services which are allowed to be discovered are obtained via the {$WINDOWS.SERVICES.MONITORED} macro, which is a list of the relevant Display Names (note: not the actual service names), of the services you wish to monitor. This is case sensative, and should be entered to exactly match the service display name.
