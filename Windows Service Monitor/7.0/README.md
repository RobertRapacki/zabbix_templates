<h3>Windows Service Monitor by SNMP</h3>

This Zabbbix template performs a discovery of all Windows services on a client.<br>
It then allows only the service names lisded in the {$WINDOWS.SERVICES.MONITORED} macro to be monitored.<br><br>
The format of the macro value is as follows:<br>
<i>^(Full Service Name|Second Full Service Name|Etc)$</i><br>
***Note that there are no spaces between the pipes/braces and the service names.<br>        
The default trigger execution time has been set to 1 minute.<br>
Be advised that some Windows services bounce up and down constantly.<br>
Changing this to a shorter length of time may lead to excessive triggers being set off.<br><br>
This template has been tested on Zabbix 7.0 to monitor Windows Server 2012R2-2022.

Copyright (C) 2024  Robert Stanley Rapacki

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
