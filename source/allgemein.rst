Titel 1. Ordnung
================
Titel 2. Ordnung
----------------
Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. 

Lorem ipsum dolor sit amet, consetetur sadipscing elitr (siehe :ref:`Beispiel <Strasse_Strassenveraengung>`). sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

.. important:: 
   At vero eos et accusam et justo duo dolores et ea rebum (siehe :ref:`einzelnes_Bild`). Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. 

                                                  
                                                                 
Fubar                                                                                            
-----

Titel 3. Ordnung                                                                                    
^^^^^^^^^^^^^^^^
Aufzählungen:

* Stet clita kasd gubergren.
* At vero eos et accusam et justo duo dolores.
* Bundesgesetz über die Geoinformation `(Geoinformationsgesetz, GeoIG) <http://www.admin.ch/ch/d/sr/c510_62.html>`_

oder:

1. erstens
2. zweitens

Codeblock (Gesetzestext o.ä):

.. code-block:: none

   Art. 16: "Daten, die nicht laufend nachgeführt werden, sind in der Regel alle sechs bis zwölf Jahre periodisch nachzuführen."

*Kursiv* und **fett**.
                                         
Ich bin ein Titel
-----------------

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.

.. _einzelnes_Bild:

.. figure:: _static/Diagramm_Vorgehen.png               
   :width: 400px                                         
   :target: _static/Diagramm_Vorgehen.png               

   This is the image caption.

Lorem ipsum dolor sit amet, consetetur sadipscing elitr sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Siehe auch das da: Toleranz (siehe :ref:`ref_Tz`).

Homogenisierung
^^^^^^^^^^^^^^^

+--------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------+
|.. _Strasse_Strassenveraengung:                                                       | .. _Strasse_pave:                                                                     |
|                                                                                      |                                                                                       |
|.. figure:: _static/Strasse_Hofdurchfahrt.png                                         | .. figure:: _static/Strasse_ueber_mehrere_parz.png                                    |
|   :width: 550px                                                                      |    :width: 550px                                                                      |
|   :target: _static/Strasse_Hofdurchfahrt.png                                         |    :target: _static/Strasse_ueber_mehrere_parz.png                                    |                              
|                                                                                      |                                                                                       |
|   ``BB.Strasse_Weg`` darf bei Hofdurchfahrten nicht unterbrochen sein.               |    ``BB.Strasse_Weg`` bei Erschliessung mehrerer Liegenschaften wird nicht korrigiert.|                                                                               
+--------------------------------------------------------------------------------------+---------------------------------------------------------------------------------------+   



Gesetzliche Grundlagen
----------------------
* Bundesgesetz über die Geoinformation `(Geoinformationsgesetz, GeoIG) <http://www.admin.ch/ch/d/sr/c510_62.html>`_

* Verordnung über die amtliche Vermessung `(VAV) <http://www.admin.ch/ch/d/sr/c211_432_2.html>`_
 
.. code-block:: none

   Art. 22: "Sämtliche Bestandteile der amtlichen Vermessung unterliegen der Nachführungspflicht."
   Art. 24: "Alle Daten, die nicht der laufenden Nachführung unterliegen, sind periodisch nachzuführen. Jede periodische Nachführung hat sich jeweils über ein grösseres zusammenhängendes Gebiet zu erstrecken."
     
* Technische Verordnung des VBS über die amtlichen Vermessung `(TVAV) <http://www.admin.ch/ch/d/sr/c211_432_21.html>`_
* Verordnung über die amtliche Vermessung `(VaV-SO) <http://bgs.so.ch/frontend/versions/4168>`_

.. code-block:: none

   Art. 16: "Daten, die nicht laufend nachgeführt werden, sind in der Regel alle sechs bis zwölf Jahre periodisch nachzuführen."
   
* Handbuch der amtlichen Vermessung des Kantons Solothurn 
* Richtlinie der Arbeitsgruppe KKVA „Periodische Nachführung der amtlichen Vermessung“ `(PNF_KKVA) <http://www.kkva.ch/de/downloads/richtlinien/pnf_av/KKVA_PNF-AV_081127.pdf>`_
* AV-Express Nr. 2010 / 08: Grundlagen für die Pauschalierung der bundesbeitragsberechtigten Kosten bei der «ersten» periodischen Nachführung (PNF) der amtlichen Vermessung (AV) 


.. _ref_RefDaten:

Vergleichsdaten
---------------

Als Referenz dient hauptsächlich das aktuelle Orthofoto. Um die Vollständigkeit der Daten der amtlichen Vermessung zu überprüfen oder bei Interpretationsschwierigkeiten können weitere Vergleichsdaten helfen. Solche Vergleichsdaten sind meist unabhängig der amtlichen Vermessung erfasst und können deshalb für einen Vollständigkeitsvergleich sinnvoll sein. Folgende Vergleichsdaten sind in der QGIS-Fachschale integriert:

.. important::    
   Bitte die Herkunft dieser Daten beachten. Die Richtigkeit und Vollständigkeit dieser Daten kann nicht garantiert werden.

=========================  ===========================================================  ======================================================  ===================================                  
Layername (QGIS)           Beschreibung                                                 Herkunft                                                Erhebungszeitpunkt 
=========================  ===========================================================  ======================================================  =================================== 
DTM                        Digitales Höhenmodell (Gradientenbild)                       Abgeleitetes LiDAR-Produkt                              2014 
DOM                        Digitales Oberflächenmodell (Relief)                         Abgeleitetes LiDAR-Produkt                              2014 
GEWISSO	                   Gewässerinformationssystem                                   Digitalisiert ab Übersichtsplan 1:10'000                2012
Wanderwege                 kantonal flächendeckende Grundlage der Fuss- und Wanderwege  Digitalisiert ab LK25                                   2012
Freileitungen (ARP)        Freileitung                                                  Digitalisiert ab LK25,  SIKOSO-Daten                    2007  
Abbaustellen (AFU)         Richtplan - Abbaustellen                                                                                             2012
Flachmoore (AFU)           Flachmoore                                                   Feldbegehung durch ANL AG, digitalisiert                2006
Flachmoore (BAFU)          Bundesinventar der Flachmoore von nationaler Bedeutung       Digitalisiert ab Kartierung 1987-1990                   1987-1990, 2001, 2004, 2007
Hochmoore (BAFU)           Bundesinventar der Hochmoore von nationaler Bedeutung        Digitalisiert ab Kartierung 1988-1990                   1988-1990, 2003, 2007
Reservoir                  Gewässeranalyse Datenbank Solothurn GASO                     Digitale Eingabe der Koordinaten                        2006-2008
Waldplan                   Forstliche Plangrundlagen                                    AV als Grundlage, Feldkontrolle durch Förster           alle 10 Jahre neu erstellt 
Radio- und Fernsehsender   Daten von geo.admin.ch                                         
Mobilfunkantennen UMTS     Daten von geo.admin.ch                                                                                           
Mobilfunkantennen GSM      Daten von geo.admin.ch 
SBB                        Daten vom Bahnunternehmen                                    Messung (Anforderung Qualität AV93 erfüllt VAV Ar. 46)  laufende Nachführung
=========================  ===========================================================  ======================================================  ===================================
                                                                                                                                 

Vorgehen beim Projekt *Periodische Nachführung und Homogenisierung* 
-------------------------------------------------------------------
.. _Diagramm_Vorgehen:                                   
                                                         
.. figure:: _static/Diagramm_Vorgehen.png               
   :width: 400px                                         
   :target: _static/Diagramm_Vorgehen.png               

In einem ersten Schritt werden die Objekte, die nachzuführen resp. die zu homogenisieren sind, detektiert. Eine QGIS-Fachschale unterstützt die Detektierung. Dazu ist das AV-Operat im Interlis-Format in die QGIS-Fachschale zu importieren (siehe https://docs.google.com/document/d/17wjFH5ijcSMELjZeC_23ZwY4X9RuDFk7_Rudk6peHGI/edit?usp=sharing).

.. important:: 
   Als Referenz für die Detektierung wird hauptsächlich ein aktuelles Orthofoto verwendet. Dabei ist zu berücksichtigen, dass Mutationen in der AV, die jünger als das Orthofoto sind, nicht an die Situation des Orthofotos angepasst werden. Zum Beispiel kann ein Strassenobjekt (Ausbau einer Strasse) in der AV aktueller sein als auf dem Orthofoto.       


Detektierung nach Gruppen
^^^^^^^^^^^^^^^^^^^^^^^^^
Um den Überblick bei der Detektion zu erhalten, werden die Objekte gruppenweise untersucht. Der Vorteil beim gruppenweisen Vorgehen ist, dass man sich auf ein Thema konzentrieren kann. 
Folgenden Gruppen wurden gebildet:

==================  ======================================================================================================
Gruppe              Bemerkung  
==================  ======================================================================================================
Strasse             Alle Objekte im Strassenbereich werden kontrolliert.
Bahn                Alle Objekte im Bahnareal werden kontrolliert.
Gewässer            Alle Objekte entlang dem fliessenden Gewässer und stehenden Gewässer werden kontrolliert.
Bebautes Gebiet     Alle Objekte in bebauten Gebieten werden kontrolliert. Dazu zählen auch Höfe und Reservoire im TS3/4.
Bestockte Fläche    Alle bestockten Objekte werden kontrolliert.
Landwirtschaft      Alle Objekte, die für die Landwirtschaft als Nutzfläche dienen, werden kontrolliert.
Seltene Objekte     Alle Objekte die nicht häufig vorkommen.
Perimeterrand       Kontrolle der Objekt am Perimeterrand mit der Nachbargemeinde.
==================  ======================================================================================================
   
Mängelpunkte/-linien erfassen
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^     
Werden Objekte gefunden, bei denen die AV angepasst werden muss, sind diese mit einem Mängelpunkt oder -linie zu kennzeichnen. Mängellinien werden nur bei Linien- und Flächenobjekten, welche eine Lagedifferenz aufweisen oder fehlen, erfasst.    
                             

| Zu den Mängelpunkt/-linien werden folgende Attribute erfasst:

+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+                      
| **Attributname**             |  **Beschreibung**                                                                                                                                             |
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+  
| Gruppe                       | Zuweisung der Gruppe (Strasse, Bahn, Gewässer, Bebautes Gebiet, Bestockte Fläche, Landwirtschaft, Seltene Objekte, Perimeterrand)                             |      
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+           
| Art                          | Auswahl der BB.Art oder EO.Art die momentan in der AV vorhanden ist.                                                                                          |
|                              | Ausnahme bei Objekten die fehlen. Da soll die BB.Art oder EO.Art abgefüllt werden, die eben neu zu erheben ist.                                               |   
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+                                                                                                               
| Fehler                       | =====================================  =======================================================================================================================|                             
|                              | ``Lagedifferenz``                      Feststellung einer Lagedifferenz grösser als die Toleranz (siehe :ref:`ref_Tz`) zwischen der AV und dem Orthofoto .    |                             
|                              | ``Löschen``                            Objekt ist aus der AV zu löschen. Dies ist auch der Fall, wenn das Objekt den Aufnahmekriterien nicht genügt.          |                             
|                              | ``fehlt``                              Objekt fehlt in der AV                                                                                                 |                            
|                              | ``umattribuieren``                     Objekt ist falsch attribuiert und eventuell in der falschen Topic (EO <-> BB). Geometrie wird nicht verändert.         |                     
|                              | ``Darstellung nicht nach Richtlinie``  Objekt ist nicht nach aktuellen Richtlinie dargestellt                                                                 |                        
|                              | ``weitere``                            Falls ein Fehler in keine Fehlerart passt, kann dieser unter "weitere" erfasst werden                                  |                             
|                              | =====================================  =======================================================================================================================|                            
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+
| Feldkontrolle                | Falls eine Interpretation auf dem Orthofoto nicht möglich ist (z.B. durch Schatten oder Sichthindernisse wie Bäume), können die betroffenen Objekte auf dem   |
|                              | Feld kontrolliert werden. Dazu ist ein Häklein zu setzen. So können die Objekte auf dem Feld gezielt begangen werden.                                         |
|                              | Falls die Feldkontrolle ergibt, dass keine Bereingung in der AV vorgenommen werden muss, kann der Mängelpunkt resp. die Mängellinien gelöscht werden.         |                                          
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+                        
| Laufende Nachführung         | Für die Kostenverteilung der Bereinigungsarbeiten muss zwingend zwischen laufender und periodischer Nachführung resp. Homogenisierung unterschieden werden.   | 
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+  
| Terrestrische Aufnahme       | Für die Berechnung der Kosten ist die Information, ob eine Terrestrische Aufnahme nötig ist, relevant.  (siehe :ref:`ref_Metherei`)                           |
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+ 
| Bemerkung                    | Beliebige Bemerkungen können hier angebracht werden. Falls ein Objekt umattribuiert wird, ist hier die neu BB.Art oder EO.Art aufzuführen.                    |
+------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------------+

.. note::
   Falls mehrere der vordefinierten Attributwerte unter dem Attribut *Fehler* zum Mängelpunkt resp. Mängellinie passt, wird pro Fehler ein Mängelpunkt resp. eine Mängellinie erfasst.

   
.. _ref_Metherei:

Bereinigung der Mängel
^^^^^^^^^^^^^^^^^^^^^^

Die Mängel sind zu bereinigen. Dazu können die Objekte falls möglich ab dem aktuellen Orthofoto (Auflösung 12.5 cm) digitalisiert werden.
                                                                                                                                                   
Kosten
------
                                                                                                 
Die Kosten für die laufende Nachführung werden dem Verursacher in Rechnung gestellt. Als Beilage zu der Rechnung ist das Schreiben `Warum diese Rechnung <_static/Warum_diese_Rechnung.pdf>`_ beizulegen. Die laufende Nachführung kann zeitlich mit der PNF/Homogenisierung oder nachträglich erfolgen. 
Für die Kostenverteilung der Bereinigungsarbeiten muss zwingend zwischen laufender und periodischer Nachführung resp. Homogenisierung unterschieden werden.         
 
========================      =============================================================================
Kostenverteilung              Beschreibung
========================      =============================================================================                           
 Laufende Nachführung         | ``BB.Gebäude`` fehlt/löschen (< 10 Jahre)
                              | ``EO.Unterstand`` fehlt/ löschen (< 10 Jahre)
                              | ``EO.unterirdisches_Gebaeude`` fehlt/löschen (< 10 Jahre)
                              | ``BB.Wasserbecken`` fehlt/löschen (< 10 Jahre)                      
                              | ``EO.Reservoir`` fehlt/löschen  (< 10 Jahre)
                              | ``EO.Lärmschutzwand`` fehlt/löschen (< 10 Jahre)  
                              | ``BB.Strasse_Weg`` fehlt (< 10 Jahre)
                              | ``BB.Parkplatz`` fehlt/löschen (< 10 Jahre)
                              | ``BB.Steinbruch`` fehlt/Lagedifferenz auf Grund von Abbauarbeiten 
                              | ``BB.Kiesgrube`` fehlt/Lagedifferenz auf Grund von Abbauarbeiten 
                              | ``BB.Deponie`` fehlt/Lagedifferenz auf Grund von Abbauarbeiten 
                              | ``BB.uebriger_Abbau`` fehlt/Lagedifferenz auf Grund von Abbauarbeiten 

                                            
 PNF/Homogenisierung          | alle Lagedifferenzen (ausgenommen Abbau oder Deponien)
                              | alle Objekte die älter als 10 Jahre sind, die fehlen resp. zu löschen sind
                              | alle Objekte, die umzuattribuieren sind     
                              | alle Objekte, die nicht nach Richtlinien dargestellt sind  
========================      =============================================================================                                            


Die Kosten der periodischen Nachführung und Homogenisierung werden vom zuständigen Nachführungsgeometer resp. der zuständigen Nachführungsgeometerin in zwei Etappen (Detektierung, Bereinigung) offeriert.
Der Anteil der Feldarbeiten in Prozent am Gesamtaufwand bei der PNF und Harmonisierung ist tief zu halten. Als Richtwert gilt ein Anteil von jeweils maximal 15%.                

                                                                                                                                                                                          
Dokumentation
--------------

Plan für Feldkontrolle
^^^^^^^^^^^^^^^^^^^^^^
Die Objekte, die auf dem Orthofoto schwierig zu interpretieren sind, werden auf dem Feld kontrolliert. Dazu sind alle Mängel mit dem Häklein Feldkontrolle zu selektieren und auf einem Plan darzustellen. Auf dem Feld werden die Bemerkungen der Kontrollergebnisse direkt in den Plan notiert.  

Bereinigung
^^^^^^^^^^^
Können Objekte nur durch Aufnahmen (GNSS oder Tachymeter) im Feld erfasst werden, sind diese Aufnahmen gemäss Anhang B der TVAV zu protokollieren. Objekte, die digitalisiert werden, können direkt angepasst werden. Ein ITF (an AGI abzugeben) vor der Bereinigung sichert den alten Zustand. Durch das Attribut *Terrestrische Aufnahme* in der Mängelliste ist genau nachzuvollziehen, wo digitalisiert wurde. 
 
.. important:: 
   Auf korrekte Erfassung in Tabelle BBNachführung und EONachführung ist zu achten. D.h. die Objekte der Tabelle Bodenbedeckung und Einzelobjekt müssen einem Objekt in Tabelle BBNachführung resp. EONachführung mit ``Beschreibung`` *PNF* zugeordnet werden.

                                                                                                                                                         
Unternehmerbericht
^^^^^^^^^^^^^^^^^^                          
Nach Abschluss der Arbeiten ist ein technischer Bericht gemäss der `Vorlage <_static/Vorlage_Technischer_Bericht.pdf>`_ zu verfassen.

Verifikation
------------
Die Verifikation wird in zwei Schritten durchgeführt. 

1. Wird nach der Mängeldetektion durchgeführt. Dazu ist die Mängelliste (als Excelliste und als Shape-File) und ein ITF SO  pro Gemeinde auf einer DVD abzugeben. Der Feldplan mit den Kommentaren der Feldbegehung und ein technischer Bericht ist ebenfalls mit abzugeben. 
2. Wird nach der Bereinigung der Mängel durchgeführt. An das AGI ist pro Gemeinde ein ITF SO vor der Bereinigung und ein ITF SO nach der Bereinigung (kontrolliert mit MOCHECKSO) auf einer DVD abzugeben. Die abgearbeitete Mängelliste und der ergänzte technische Bericht ist ebenfalls mit abzuliefern. 
                                                                                       

QGIS Fachschale PNF/Homogenisierung
-----------------------------------
Anleitungen zu QGIS Fachschale PNF/Homogenisierung unter: https://docs.google.com/document/d/17wjFH5ijcSMELjZeC_23ZwY4X9RuDFk7_Rudk6peHGI/edit?usp=sharing

|



                                                                                                                                                                                                      
