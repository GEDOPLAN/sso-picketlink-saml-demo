# SSO Beispiel mit PicketLink, SAML und JSF

###Dieses Projekt zeigt wie man Single Sign-On mit einem Identity Provider (IDP) und mehreren Service 
###Providern (SP) realisieren kann. Um dies zu realisieren besteht das Projekt aus drei Webanwendungen.
###Einmal dem IDP, welcher die Authentifizierung kontrolliert und zwei SPs auf die dann mit
###SAML Assertions zugegriffen werden kann ohne, dass ein erneuter Login durchgeführt werden muss.

###Zum Betreiben der Webanwendungen wird ein WildFly 9 Application-Server benötigt. Dieser muss zuerst installiert werden.
###Dieser benötigt zu Beginn ein PicketLink Update auf die Version 2.7.1. Dieses kann unter 
###[Absolute README link]http://downloads.jboss.org/picketlink/2/latest/picketlink-installer-2.7.1.Final.zip)
###heruntergeladen werden. Danach muss in dem entpackten, heruntergeladenen Ordner die Kommandozeile geöffnet werden und der Befehl
###"ant" ausgeführt werden. Der Installationsprozess beginnt. (Hierzu muss das Build-Tool Ant auf dem System vorhanden sein.)
###Zuletzt wird mit Hilfe des in dem Git-Repository befindlichen CLI-Skript der WildFly 9 konfiguriert.

##Weitere Informationen finden Sie unter xxxxx und in den READMEs der einzelnen Projekte.
