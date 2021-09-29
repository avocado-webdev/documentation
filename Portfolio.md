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

- Die Anwendung versucht vermehrt *vegetarische* und *vegane* Gerichte anzubieten, bzw. den Schwerpunkt auf Mahlzeiten zu legen, welche eine fleischreduziertere und gesündere Alternative zu den herkömmlichen Produkten bieten
- Die Anwendung versucht vermehrt *regionale*, *nachhaltige* Produkte anzubieten, um entsprechend heimische Anbieter vermehrt in die Produktauswahl zu integrieren
- Durch das Abspeichern und Verfolgen des Mindesthaltbarkeitsdatum kann verhindert werden, dass Lebensmittel nicht unnötig weckgeworfen und entsprechend zeitgerecht aufgebraucht werden

<br/>

**Spezialisierung auf eine spezifische Zielgruppe (Amateur- und Profisport):**

- Das Aufzeichnen von Lebensmitteln und Erstellen eines individuellen, an den Bedürfnissen des Benutzers angepassten Ernährungsplans könnte vor alle in vielen Bereichen des *Sports* (Amateur- und Profisport) Anwendung finden
- Speziell Personen die aus beruflichen Gründen sportliche Aktivitäten ausüben (Leistungssportler) sind darauf bedacht, sich entsprechend gesund, ausgewogen und individuell zu ernähren

<br/>

**Spezialisierung auf eine spezifische Zielgruppe (Diätologie, Medizin):**

- Die Applikation fokussiert sich auf Personen mit *Nahrungsmittelunverträglichkeiten*, wie z.B. Laktose- oder Fruktoseintoleranz, sowie Zöliakie (Glutenunverträglchkeit) und versucht entsprechend alternative Produkte bzw. Mahlzeiten anzubieten
- Die Anwendung legt den Schwerpunkt auf Menschen mit *Essstörungen* bzw. besonderem Essverhalten, wie z.B. Magersucht oder Fettleibigkeit und fokussiert sich entsprechend auf die exakte Extrahierung der in den Lebensmitteln enthaltenen Kalorien und Maktronährstoffe, sowie auf den gesamtheitlichen Kalorienumsatz
- Die Applikation versucht Personen mit *Diabetes* in ihrer Ernährung zu unterstützen

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

### Notizen & Tools

<hr/>

<br/>

- Fotografieren der Inhaltstoffe eines Produkts, die auf der Rückseite abgebildet sind
- Verwendung der Verfahren der Texterkennung, um entsprechend Informationen zu extrahieren und in die Applikation zu übertragen, wodurch beispielsweise verpackte Lebensmittel erfasst werden können

<br/>

**Label Studio:**

*Label Studio* ist ein Open-Source-Tool zum Labeln (Beschriften) von Datensätzen: <br/>
https://labelstud.io/

