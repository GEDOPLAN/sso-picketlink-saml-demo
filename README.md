## SSO Beispiel mit PicketLink, SAML und JSF

#####Dieses Projekt zeigt wie man, mit Hilfe von PicketLink, Single Sign-On mit einem Identity Provider (IDP) und mehreren Service Providern (SP) realisieren kann. Um dies zu realisieren, besteht das Projekt aus drei Webanwendungen. Dem IDP, welcher die Authentifizierung kontrolliert und zwei SPs auf die nach einmaligem Login zugegriffen werden kann.

###Usage

* Git Repository clonen
* [WildFly 9](http://wildfly.org/downloads/) installieren
* [PicketLink 2.7.1](http://downloads.jboss.org/picketlink/2/latest/picketlink-installer-2.7.1.Final.zip) installieren
  * zum Installieren wird [Apache Ant](http://ant.apache.org/bindownload.cgi) benötigt
  * Befehl **ant** im PicketLink 2.7.1 Ordner ausführen
* standalone-full.xml des WildFly AS konfigurieren
  * configure-wildfly-ipd-sp.cli verwenden (jboss-cli.bat oder jboss-cli.sh)
* READMEs der beinhalteten Projekte (IDP, SP1, SP2) zum Deployen dieser lesen 

####Weitere Informationen finden Sie unter xxxxx und in den READMEs der einzelnen Projekte.
