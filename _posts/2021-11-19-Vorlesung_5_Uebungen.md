---
title: "Uebungen zur 5. Vorlesung"
date: 2021-11-19
---
Ich machte mich zuerst nochmals an die Aufgabe mit ArchivesSpace. Diesesmal klickte ich die gewünschte XML-Datei mit der rechten Maustaste an, wählte "Save Link As..." und übernahm es in den Ordner "Downloads". Nachher gings im ArchivesSpace über Create usw wieder zum Import. Die Datei war einfach hochzuladen – wiedermal was gelernt, wenn auch nicht eines der Kernthemen in diesem Modul, aber man nimmt, was man bekommt.
Dann: "... already in use..." – ich interpretierte das so, dass diese Datei schon einmal vorhanden ist und ich (wenn auch mit Umwegen) zumindest dies richtig machte.

Nun zu DSpace: Da Samstag vorbei war, musste ich zuerst wieder eine neue Collection erstellen und nachher noch ein Dokument. Doch fand ich dieses nachher nicht mehr. Ein zweites, drittes Dokument erstellt... immer noch nichts > Moodle > BAIN > Webex > Recordings und die Vorlesung nochmals anschauen. Die Lösung war schnell klar: ich vergass den Workflow mit der Begutachtung! Doch wo finde ich in der JSPUI-Version die Dokumente? Zum Glück stellte sich der eine Dozent während der Vorlesung dieselbe Frage und quasi gemeinsam fanden wir unsere Dokumente rechts ober über MyDspace. Beim Dokument hatte dich die Buttons "Export" und "Export Items" – ich klickte beide mal an.
Im DSpace OAI-PMH Data Provider fand ich dann auch meine Collection aber für die Dokumente war es noch zu früh ("No matches fort he query"). Da ich ein wenig ungeduldig war, schnappte ich mir die Collection einer Klassenkollegin und lud mir mal dort die Metadaten eines Dokumentes runter (es sei mir verziehen):

<?xml version="1.0" encoding="UTF-8"?><?xml-stylesheet type="text/xsl" href="static/style.xsl"?><OAI-PMH xmlns="http://www.openarchives.org/OAI/2.0/" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:schemaLocation="http://www.openarchives.org/OAI/2.0/ http://www.openarchives.org/OAI/2.0/OAI-PMH.xsd"><responseDate>2021-11-25T10:18:09Z</responseDate><request verb="ListRecords" metadataPrefix="oai_dc" set="col_10673_76">http://demo.dspace.org/oai/request</request><ListRecords><record><header><identifier>oai:demo.dspace.org:10673/77</identifier><datestamp>2021-11-21T09:36:38Z</datestamp><setSpec>com_10673_75</setSpec><setSpec>com_10673_1</setSpec><setSpec>col_10673_76</setSpec></header><metadata><oai_dc:dc xmlns:oai_dc="http://www.openarchives.org/OAI/2.0/oai_dc/" xmlns:doc="http://www.lyncode.com/xoai" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dc="http://purl.org/dc/elements/1.1/" xsi:schemaLocation="http://www.openarchives.org/OAI/2.0/oai_dc/ http://www.openarchives.org/OAI/2.0/oai_dc.xsd">   
<dc:title>Beispieldokument</dc:title>   
<dc:creator>Muster, Melanie</dc:creator>   
<dc:subject>Muster</dc:subject>   
<dc:subject>Beispiel</dc:subject>   
<dc:date>2021-11-21T09:36:37Z</dc:date>   
<dc:date>2021-11-21T09:36:37Z</dc:date>   
<dc:date>2021-11-19</dc:date>   
<dc:identifier>http://hdl.handle.net/10673/77</dc:identifier>   
<dc:language>de</dc:language>   
<dc:relation>Beispiel;01</dc:relation>   
<dc:rights>Attribution-ShareAlike 3.0 United States</dc:rights>   
<dc:rights>http://creativecommons.org/licenses/by-sa/3.0/us/</dc:rights>   
<dc:format>application/pdf</dc:format>   
</oai_dc:dc></metadata></record></ListRecords></OAI-PMH>   

Sieht doch ganz passabel aus, oder?
