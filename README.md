
	<onclick>RunScript(script.skinhelper.PING)</onclick>		# startet das Script und löst damit einen Ping aus, danach werden die Propertys gesetzt
	<onclick>RunScript(script.skinhelper.ping,menu)</onclick>	# öffnet ein WOL-Menü in dem der Onlinestatus zu sehen ist und die einzelnen Server geweckt werden können

    $INFO[Window(Home).Property(SkinHelperPING.server1)]      	# Onlinestatus Server 1
    $INFO[Window(Home).Property(SkinHelperPING.server2)]      	# Onlinestatus Server 2
    $INFO[Window(Home).Property(SkinHelperPING.server3)]      	# Onlinestatus Server 3
    $INFO[Window(Home).Property(SkinHelperPING.server4)]      	# Onlinestatus Server 4
    $INFO[Window(Home).Property(SkinHelperPING.server5)]      	# Onlinestatus Server 5
	
    $INFO[Window(Home).Property(SkinHelperPING.servername1)]    # Name von Server 1
    $INFO[Window(Home).Property(SkinHelperPING.servername2)]    # Name von Server 2
    $INFO[Window(Home).Property(SkinHelperPING.servername3)]    # Name von Server 3
    $INFO[Window(Home).Property(SkinHelperPING.servername4)]    # Name von Server 4
    $INFO[Window(Home).Property(SkinHelperPING.servername5)]    # Name von Server 5
	
    $INFO[Window(Home).Property(SkinHelperPING.ip1)]      		# IP von Server 1
    $INFO[Window(Home).Property(SkinHelperPING.ip2)]      		# IP von Server 2
    $INFO[Window(Home).Property(SkinHelperPING.ip3)]      		# IP von Server 3
    $INFO[Window(Home).Property(SkinHelperPING.ip4)]     	 	# IP von Server 4
    $INFO[Window(Home).Property(SkinHelperPING.ip5)]     		# IP von Server 5
	
    $INFO[Window(Home).Property(SkinHelperPING.mac1)]      		# MAC Adresse von Server 1
    $INFO[Window(Home).Property(SkinHelperPING.mac2)]      		# MAC Adresse von Server 2
    $INFO[Window(Home).Property(SkinHelperPING.mac3)]      		# MAC Adresse von Server 3
    $INFO[Window(Home).Property(SkinHelperPING.mac4)]     	 	# MAC Adresse von Server 4
    $INFO[Window(Home).Property(SkinHelperPING.mac5)]     		# MAC Adresse von Server 5

    $INFO[Window(Home).Property(SkinHelperPING.servercount)]  	# Anzahl der Einträge in den Einstellungen
    $INFO[Window(Home).Property(SkinHelperPING.serveron)]     	# Gesamtzahl der Geräte die online sind
    $INFO[Window(Home).Property(SkinHelperPING.serveroff)]    	# Gesamtzahl der Geräte die offline sind
