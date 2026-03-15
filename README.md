# Glossar-VLAN


Trunk

Die Eigenschaft, dass am Switch über denselben Port mehrere Vlan's übertragen werden können. 


VLT

(= Trunk-Port) Vlan-Trunk, Daten von mehreren Vlans über das selbe Kabel übertragen. 


VTP

Cisco Vlan-Protokoll, um Vlans in Cisco-Netzen zu konfigurieren. 


Tagging

Zum Datenpaket wird die Vlan-ID hinzugefügt, damit der Trunk-Port weiss, welches Datenpaket zu welchem Vlan gehört. 


Trunk-Port

Der eine Port am Switch, an welchen alle Vlan's die Verbindung zum Router oder zu den nächsten Switches herstellen. 


Access-Ports

Ports, an denen die Endgeräte angeschlossen werden (Für die Endgeräte wird der Vlan-Tag vorab entfernt). 

Untagged Port
(= Access-Port) Gewöhnlicher Port am Switch für Endgeräte, welches nur einem Vlan zugeordnet ist. 

Tagged Port
(= Trunk-Port) Der Port am Switch, der für alle Vlan's die Verbindung zu den anderen Switches od. zum Router herstellt. 

VID
Vlan-ID, Nummer der Vlans. 

PVID
Port Vlan ID, die Vlan-Nummer des Ports. 

Vlan-Routing
Layer 3-Switches, die verschiedene Vlan's verbinden können. 

Inter-Vlan : 		?

Native-Vlan
(= Vlan 1) Den Paketen, die keinem Vlan zugeordnet werden können, zu ermöglichen, in nicht-getagtem Zustand trotzdem 
über den Trunk transportiert werden zu können. Ausserdem können dadurch auch nicht-Vlan-fähige Switches diese Pakete 	empfangen.

802.1Q
Die Funktion, dass im Vlan mittels tagging ein Trunk erstellt werden kann.

802.1p
Bestandteil von 802.1Q, die Funktion "QoS" einzurichten. Priorisierung der Vlan's. 

802.3
Ethernet. Frame, Vlan-Tag ist grob auf zwei Arten realisierbar: Portbasiert und Tag-basiert 

Portbasiert = alt: jedes Vlan hat separates physisches Kabel. Es gibt kein Trunkport. 
Tag-basiert = neu: Datenpakete sind tagged / markiert, so dass über den Trunkport mehrere Vlans betrieben werden können. 
(MAC-basiert = Ausserdem kann auch auf Basis der MAC-Adressen der Endgeräte ein Vlan realisiert werden.)

- Heute ist meistens nur noch tagged-Vlan im Einsatz, da Tag-basiert flexibel ist.
 
- Beim portbasierten Vlan mussten die Ports statisch konfiguriert werden und zum nächsten Punkt musste für jedes Vlan ein separates Kabel benutzt werden, da tagging nicht möglich war.
