---
title: "This is the end"
date: 2022-01-18
---

**Nachtrag 1**: ich fragte endlich wegen dem Datenaustausch unserer Buchhandlung bei der Stammdatenbetreuung bei Thaila in Hagen nach (wo unser Server steht) und erhielt zügig eine Antwort. Viele Lieferanten benützen proprietäre Formate, welche also nur für den jeweiligen Lieferant gelten. Die Daten vom VLB und auch von Zeitfracht (ehem KNV), BZ und Libri werden in ONIX übertragen. ONIX (musste ich zuerst nachschauen) steht für ONline Information eXchange und ist ein Datenformat für bibliografische Artikel, das über die ganze Verwertungskette des Buchhandels funktionieren sollte. Es basiert wie viele andere Formate auch auf XML.
Thalia hat mit ThaliaLight noch ein eigenes Format für kleine Verlage, damit diese die Daten im .csv-Format zur Verfügung stellen können.   
Die Aufbereitung geschieht über einen Seeburger Konverter für das SAP Pricat-IDoc. => Seeburger ist ein Unternehmen unter anderem für den Bereich Datenaustausch, auf SAP basiert unser System und Pricat ist wiederum ein Format für Katalogs- und Preisformaten.   
Und da die Daten vom FTP Server abgeholt werden, geht man beim Protokoll von FTP aus – File Transfer Protocol: ein Protokoll für den Transfer von Dateien (es war einmal das Modul ARIS...)   
   
**Nachtrag 2** - offene Fragen zu BIBFRAME: am Beispiel "Winnie-the-Pooh" (das Original, nicht der Disney-Verschnitt!) konnte ich nachvollziehen, dass der Illustrator Ernst H. Shepard auch als *Agent* gilt aber mit der *role "illus."*
    
></bf:agent>   
<bf:role >   
<bf:Role >   
<rdfs:label >illus</rdfs:label>   
</bf:Role>   
</bf:role>    

... und sofern ich das BIBFRAME(XML) richtig interpretiere ist die ISBN eine SubClass vom *identifier* und dieser kommt beim XML zwischen den Einträgen von *Instance*.   
=> [https://id.loc.gov/tools/bibframe/compare-lccn/full-rdf?find=73174934](https://id.loc.gov/tools/bibframe/compare-lccn/full-rdf?find=73174934)   
   
Unsere Donzenten rechnen damit, dass MARC21 mindestens noch ein Jahrzehnt gültig bleiben wird.... topp, die Wette gilt!   
   
      
**Was bleibt nach einem Semester BAIN?**  
Als erstes zum Rückblick möchte ich bemerkten, das ich anstelle von "ich lernte" eher "ich hatte Einblick" anwenden sollte, denn die vielen verschiedenen Anwendungen unter Anleitung reichten nicht wirklich zum Lernen. Aber ich erhielt einen Überblick über den Umgang mit Katalogs- und Metadaten. Also wie wir sie in Systemen (*Koha, ArchivesSpace, DSpace*) erstellen und wie wir sie in ein anderes System (*VuFind, mit Hilfe von Solr*) übertragen. Dazu muss man die Daten zuerst sammeln oder "ernten" (*OAI-PMH / VuFindHarvest*) und dann vom einen Format (*DublinCore, EAD*) in ein anderes (*MARC21 XML / mit Hilfe von marcEDIT*) umwandeln. Für mich persönlich hätte man auch öfters die Übersichtsgrafik anwenden können, um zu zeigen wo wir stehen.

Von den Themen blieb mir ebenfalls BIBFRAME irgendwie und irgendwo im Kopf hängen. Sicher auch, weil es das letzte Thema vor dem Abschluss war; aber ebenso, weil es mir wieder half eine Verbindung zu in diesem Studium bereits gelerntem zu knüpfen: Semantische Systeme, Datensysteme/Entity Relationship Model oder auch indirekt Bibliotheksmanagement (siehe Eintrag zur 9. Vorlesung).   
Oder wenn wir von Archiven und dessen Regeln und Normen sprachen: RiC wurde bereits in den Vorlesungen zu WOR2/Archivische Erschliessung erwähnt. Allerdings ging das mir in der damaligen Menge von Informationen völlig unter und vergessen. In diesen Unterlagen zur Archivischen Erschliessung stiess ich soeben auch auf den Ausdruck *Crosswalks* und dass diese zum Beispiel mit Hilfe von Mapping auf Dublin Core gemacht werden können.

Solche Verknüpfungen erwähnte ich unter Erwartungen und konkrete Beispiele gab es (zum Glück) noch mehrmals im Lerntagebuch:   
* *vertikale und horizontale Suchmaschinen*   
* *RDA*   
* *ISAD(G) und EAD*
   
      
Diese "Links" helfen mir, ein Bild/einen Überblick über den Stoff zu erhalten – und erhöhen den Lerneffekt. Das Format des Lerntagebuches half da ebenfalls. Bei einer Prüfung hätte ich wieder "Wissensbulemie" betreiben müssen - siehe erster Eintrag.   
Ich erstellte quasi mein eigenes "semantische System" zusammen oder ein "mental Model" (in diesem Semester waren auch SESY und USAB dran).   
Dazu noch: allgemein habe ich das Gefühl, dass solche Verbindungen zwischen den Modulen für uns Studentinnen und Studenten hilfreich sein könnten und eigentlich gefördert werden müssten – aber hier ist nicht die Stelle, um dies weiter auszuführen.

Und zu guter Letzt: Das Buch "Raspberry Pi für Kids" liegt nun wirklich bei mir bereit, um nach dem Studium gelesen und angewendet zu werden – wie so vieles, welches ich in den letzten vier Jahre auf "nach dem Studium" verschoben habe... seufz!
   
In diesem Sinne: *Macht's gut und danke für den Fisch!*   
   
![grafik](https://user-images.githubusercontent.com/90788030/150500696-7141e48d-e420-4f6d-bca8-1074fc810553.png)   
(An Anlehnung an die 6. Vorlesung/MarcEdit; es sind zwar nicht unsere Hunde aber die Hundedame links ist der Patenhund meiner Frau - NEBEN meiner Frau, nicht sie selber!)   



