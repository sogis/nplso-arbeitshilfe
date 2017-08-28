.. _ref_Erschliessung:

Topic Erschliessung
===================
Übersicht über das Topic Erschliessung:

	BILD
	
Attribute der Erschliessung
^^^^^^^^^^^^^^^^^^^^^^^^^^
Hinweis: Orange markierte Attribute sind Pflicht. D.h. diese Werte müssen immer erfasst werden.

	Klasse Typ_Erschliessung_Flaecheobjekt / Typ_Erschliessung_Linienobjekt / Typ_Erschliessung_Punktobjekt
	
Ein Typ_Grundnutzung kann mehrere Grundnutzungsgeometrien haben (siehe Beziehung in der Übersicht ``Link``).

	Klasse Erschliessung_Flaecheobjekt / Erschliessung_Linienobjekt / Erschliessung_Punktobjekt
	
Eine Erschliessungsgeometrie (Fläche, Linie oder Punkt) ist immer einem Typ (Typ_Erschliessung_Flaecheobjekt / Typ_Erschliessung_Linienobjekt / Typ_Erschliessung_Punktobjekt) zugewiesen (siehe Beziehung in der Übersicht (Link)).

	Klasse Erschliessung_Flaecheobjekt_Pos / Erschliessung_Flaecheobjekt_Pos / Erschliessung_Flaecheobjekt_Pos

Beschriftet wir die Abkürzung, welche in der Klasse Typ_Erschliessung_Flaecheobjekt / Typ_Erschliessung_Linienobjekt / Typ_Erschliessung_Punktobjekt erfasst wird. Eine Beschriftung macht nur Sinn, wenn eine Abkürzung unter der Klasse Typ_Erschliessung_Flaecheobjekt / Typ_Erschliessung_Linienobjekt / Typ_Erschliessung_Punktobjekt erfasst ist. Eine Beschriftung ist nicht zwingend (siehe Beziehung in der Übersicht (Link)). 
Die Ausrichtung (Ori, HAli und VAli) und die Textgrösse kann frei gewählt werden.

	Klasse Dokument
	
siehe 2.1.1. Klasse Dokument

Objektkatalog
^^^^^^^^^^^^^
Hier EXCEL einblenden --> Link zu Beschreibung ueberlagernd_Objekt Beschreibung.docx
Unter dem jeweiligen kant. Typ könne spezielle Informationen, welche nur für den Typ gelten beschrieben werden.