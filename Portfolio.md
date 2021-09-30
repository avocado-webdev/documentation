# Portfolio der Applikation *feedMe*

<br/>

### Allgemeine Zielsetzung (stichwortartig)

<hr/>

<br/>

- Die Applikation *feedMe* soll die im Haushalt vorhandenen, bzw. für die Auswahl des jeweiligen Gerichts (Rezepts) erforderlichen Lebensmittel aufzeichnen und verfolgen
- Die Aufzeichnung der Lebensmittel erfolgt mithilfe der Verfahren der *Objekterkennung (Machine Learning)*, wodurch Makroinformationen zu den einzelnen Produkten anhand von Bildern extrahiert werden können 
- Die Informationen können beispielsweise für das Erstellen eines individuellen, an den Bedürfnissen des Benutzers angepassten Ernährungsplans herangezogen werden
- Die Anwendung fungiert folglich als *Lebensmittel-Management-System* und soll dem Benutzer einerseits, durch Vereinfachung des Prozesses der Lebensmittelverwaltung und Rezeptauswahl, eine entsprechende Zeitersparnis im Alltag verschaffen und andererseits zu einem bewussten und nachhaltigen Umgang mit Lebensmittel verhelfen
- Zudem kann die *Haltbarkeit* und der *Zustand* der Lebensmittel erkannt und bewertet werden und den Benutzer über einen baldigen Verzehr, bzw. über eine rasche Entsorgung des jeweiligen Produkts informieren
- Ebenso kann die Applikation das *Mindeshaltbarkeitsdatum* abspeichern und den Anwender folglich an einen zeitgerechten Konsum und Verzehr des Lebensmittels erinnern

<br/>

### Mögliche Alleinstellungsmerkmale (USP - Unique Selling Point)

<hr>

<br/>

**Spezialisierung auf Alternativprodukte & die Ökologie**

- Die Anwendung versucht vermehrt *vegetarische* und *vegane* Gerichte anzubieten, bzw. den Schwerpunkt auf Mahlzeiten zu setzen, welche eine fleischreduziertere und gesündere Alternative zu den herkömmlichen Gerichten bieten
- Die Applikation versucht vermehrt *regionale* und *nachhaltige* Produkte anzubieten, um entsprechend heimische Anbieter vermehrt in die Produktauswahl zu integrieren
- Durch das Abspeichern und Verfolgen des *Mindesthaltbarkeitsdatums* kann verhindert werden, dass Lebensmittel nicht unnötige entsorgt, sondern entsprechend zeitgerecht aufgebraucht werden

<br/>

**Spezialisierung auf eine spezifische Zielgruppe (Amateur- und Profisport):**

- Das Aufzeichnen von Lebensmitteln und Erstellen eines individuellen, an den Bedürfnissen des Benutzers angepassten Ernährungsplans, könnte vor allem im Bereich des *Sports (Amateur- und Profisport)* Verwendung finden

Die Spezialisierung auf Personen die ein starkes Interesse an sportlichen Aktivitäten besitzen, schränkt entsprechend das Anwendungsgebiet der Applikation drastisch ein. Dadurch kann die Zielgruppe der *normalen Anwender* folglich entfallen, wodurch eine Etablierung der Applikation am Markt deutlich schwerer fallen kann. Allerdings sind die Interessensgruppen am Sport im mitteleuropäischen Raum recht groß, wodurch entsprechend Unterstützung für die Umsetzung gefunden werden kann.

<br/>

**Spezialisierung auf eine spezifische Zielgruppe (Diätologie):**

- Die Applikation fokussiert sich auf Personen mit *Nahrungsmittelunverträglichkeiten*, wie z.B. Laktose- oder Fruktoseintoleranz, sowie Zöliakie (Glutenunverträglichkeit) und versucht entsprechend alternative Produkte und Mahlzeiten anzubieten
- Die Anwendung legt den Schwerpunkt auf Menschen mit *Essstörungen*, wie z.B. Magersucht oder Fettleibigkeit und fokussiert sich entsprechend auf die exakte Extrahierung des Kaloriengehalts und der Makronährstoffe von Lebensmitteln
- Die Applikation unterstütz Personen mit *Diabetes*

Die Spezialisierung auf Personen mit Essstörungen, bzw. Nahrungsmittelunverträglichkeiten oder Diabetes, bringt die Herausforderung der Genauigkeit der Aufzeichnung und Extrahierung mit sich. Dadurch wird die Problematik der *Haftung* und *Garantie* in die Applikation mit eingebunden. Allerdings ist der Bereich *Ernährung* in der Medizin ein recht junges Forschungsgebiet und erhöht folglich die Chance eines neuartigen Erkenntnisgewinns, wodurch die Applikation einen entsprechenden Beitrag leisten kann.

<br/>

### Möglichkeiten & Herausforderungen der Aufzeichnung

<hr/>

<br/>

Allgemein gibt es die folgenden Herangehensweisen für die Aufzeichnung der Lebensmittel:

- Der Aufzeichnungsprozess der Applikation erfolgt mithilfe einer *Kamera* oder *Videokamera* (mobil oder stationär) und verwendet entsprechend die Verfahren der Objekterkennung zum Einlesen der Produkte und extrahieren der erforderlichen Informationen
- Es werden die *Kassenbelege (Kassabons)* der gekauften Lebensmittel fotografiert und die Informationen mithilfe der Verfahren der Texterkennung extrahiert und in die Anwendung übertragen

Die folgende Abbildung veranschaulicht den möglichen Aufbau eines Kassenbelegs und die darauf enthaltenten Informationen:

<br/>

<div align="center">
    <img src="./img/kassenbeleg.jpg" alt="Kassenbeleg Beispiel" height="720px">
</div>

<br/>

**Vor- & Nachteile der verschiedenen Herangehensweisen:**

**Kassenbeleg, Kassabon**:

- Auf dem Kassenbeleg können Produkte aufgelistet werden, die keine Lebensmittel sind und folglich nicht für Anwendung selbst relevant sind, wodurch bestimmte Artikel entsprechend herausgefiltert werden müssen
- Die Kassenbelege können, abhängig von dem jeweiligen Supermarkt, unterschiedlich aufgebaut und strukturiert sein, bzw. die Lebensmittel mehr oder weniger genau beschreiben
- Die Produktbezeichnung auf dem Kassenbeleg ist nicht eindeutig und einheitlich (z.B. Mayonnaise, Granada), wodurch eine Kategorisierung der Lebensmittel zusätzlich erschwert wird
- Zum Teil sind relevante Angaben zu dem Produkt, wie z.B. Gewicht oder Menge, auf dem Kassenbeleg vorhanden
- Der Kassenbeleg könnte zukünftig so aufgebaut und strukturiert werden, dass für die Applikation relevante Informationen extrahiert werden können, z.B. durch die Generierung eines spezifischen QR-Codes, welcher sich einfach abfotografieren lässt
- Problematisch könnte allerdLings der Eingriff in bereits bestehende Systeme, sowie in die Philosophie der Lebensmittelhersteller und Supermarktbetreiber sein
- Zudem gestaltet sich der Prozess der Veränderung der Lebensmittelbezeichnung, bzw. der Struktur und Beschriftung des Kassenbelegs als langwierig

<br/>

### Notizen & Tools

<hr/>

<br/>
- Zielgruppe(n): Erwerbstätige Person, die aufgrund des strikten Alltags, wenig Zeit für das Kochen von Mahlzeiten entbeeren kann, sich allerdings gesünder, bewusster und nachhaltiger Ernähren möchte
- Ebenso gestaltet sich der Lebensmitteleinkauf (Lebensmittelmanagement) als recht zeitintensiv und die Entscheidungsfindung des zu kochenden Gerichts äußerst mühsam
- Fotografieren der Inhaltstoffe eines Produkts, die auf der Rückseite abgebildet sind
- Verwendung der Verfahren der Texterkennung, um entsprechend Informationen zu extrahieren und in die Applikation zu übertragen, wodurch beispielsweise verpackte Lebensmittel erfasst werden können

<br/>

**Label Studio:**

*Label Studio* ist ein Open-Source-Tool zum Labeln (Beschriften) von Datensätzen: <br/>
https://labelstud.io/


<br/>

### Meeting, am 30.09.2021

<br/>

**Allgemeiner Leitfaden:**

- Themenfindung, Abwägung und Erweiterung der bisher vorgeschlagenen Ansätze
- Entscheidungsfindung der Zielgruppe - für welche Personen können und wollen wir ein Produkt schaffen, welches eine entsprechende Erleichterung und Verbesserung im Alltag schaffen kann
- Mögliche Problemstellungen in dem gewählten Ansatz besprechen - was könnte unser Beitrag dazu sein, um den ensprechenden Herausforderungen entgegenzuwirken
- weitere Vorgehensweise besprechen (Meeting mit Lukas Huber, Antrag auf Förderung, etc.)

<br/>

**Notizen:**
