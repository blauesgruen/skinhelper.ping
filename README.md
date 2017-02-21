Skinhelper PING
===============

Informationen für Skinner / Informations for skinners
----------------------------------------------------

<b>Benutzung / Usage</b>

Startet das Addon und setzt den Status der Server in den Eigenschaften des Home-Windows / Runs the addon and store the state of the servers into the properties of the home window:

	<onclick>RunScript(script.skinhelper.ping)</onclick>
	
Öffnet ein Menü, in dem der Status der Server angezeigt wird. Server können aus diesem Menü heraus per WOL geweckt werden / Opens a menu with the state of all servers. Servers can woked up by sending a WOL-Packet.

	<onclick>RunScript(script.skinhelper.ping,menu)</onclick>
	
<b>Properties</b>

Online-Status Server 1 - 5 / Online state of servers 1 - 5:
 
    $INFO[Window(Home).Property(SkinHelperPING.server1)]
    $INFO[Window(Home).Property(SkinHelperPING.server2)]
    $INFO[Window(Home).Property(SkinHelperPING.server3)]
    $INFO[Window(Home).Property(SkinHelperPING.server4)]
    $INFO[Window(Home).Property(SkinHelperPING.server5)]
    
Name der Server 1 - 5. Der Name ist beliebig wählbar und muss nicht der Name des Servers im Netzwerk sein / Server names 1 - 5. The name can be chosen as desired and does not match the name of the server in the network:
	
    $INFO[Window(Home).Property(SkinHelperPING.servername1)]
    $INFO[Window(Home).Property(SkinHelperPING.servername2)]
    $INFO[Window(Home).Property(SkinHelperPING.servername3)]
    $INFO[Window(Home).Property(SkinHelperPING.servername4)]
    $INFO[Window(Home).Property(SkinHelperPING.servername5)]
    
IP-Adressen der Server 1 - 5 / IPs of the servers 1 - 5:
	
    $INFO[Window(Home).Property(SkinHelperPING.ip1)]
    $INFO[Window(Home).Property(SkinHelperPING.ip2)]
    $INFO[Window(Home).Property(SkinHelperPING.ip3)]
    $INFO[Window(Home).Property(SkinHelperPING.ip4)]
    $INFO[Window(Home).Property(SkinHelperPING.ip5)]
    
MAC-Adressen der Server 1 - 5 / MAC of servers 1 - 5:
	
    $INFO[Window(Home).Property(SkinHelperPING.mac1)]
    $INFO[Window(Home).Property(SkinHelperPING.mac2)]
    $INFO[Window(Home).Property(SkinHelperPING.mac3)]
    $INFO[Window(Home).Property(SkinHelperPING.mac4)]
    $INFO[Window(Home).Property(SkinHelperPING.mac5)]

<b>zusätzliche Infos / additional Informations</b>
 
Anzahl der Einträge in den Einstellungen / Count of servers in settings:

    $INFO[Window(Home).Property(SkinHelperPING.servercount)]
    
Anzahl der Server mit Online Status / Count of online servers:

    $INFO[Window(Home).Property(SkinHelperPING.serveron)]
    
Anzahl der Server mit Offline Status / Count of offline servers:

    $INFO[Window(Home).Property(SkinHelperPING.serveroff)]

