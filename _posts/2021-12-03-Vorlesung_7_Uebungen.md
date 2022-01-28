---
title: "Übungen zur 7.Vorlesung"
date: 2021-12-03
---

Ich muss noch vorausschicken, dass ich erst kurz vor der achten Vorlesung zum Schauen des Videos "VuFind: Configuring Search and Facet Settings" kam. Grund dafür waren Probleme bei der Installation von VuFind. Zweimaliges Zurücksetzen und erneutes Installieren halfen leider auch nicht.   
Weitere Abklärungen der Dozenten ergaben, dass von der früheren KOHA-Installation her, der Webserver irrtümlich versuchte Anfragen an KOHA anstatt an VuFind weiterzuleiten. Ob es irgendwie mit den Problemen bei der KOHA-Installation zusammenhängt? Ich fragte mal bei den Dozenten nach. Falls ja, reiche ich die Antwort noch nach.

So widmete ich mich danach dem Video zu den Such- und Facetteneinstellungen. Mein Problem war und ist, dass ich bei dieser Materie schon auf Deutsch und gut & geduldig erklärt nicht immer ganz einfach folgen konnte und so wurde es auf Englisch leider nicht einfacher. Wäre es die Idee gewesen, dass wir selber in den Code gehen und diese Änderungen bei den Begriffen der Suchoptionen oder bei der Reihenfolge der Treffer nachmachen? Wenn ja, hatte ich es völlig verpasst, wie ich dorthin komme. Also schaute und hört ich einfach zu und versuchte den Faden nicht zu verlieren. Bei der jeweiligen Demonstration konnte ich es auch nachvollziehen, wieso zum Beispiel "Author" zu "Person who created Stuff" wird – könnte man von mir aus gleich so lassen. Und bei der Anzahl angezeigten Treffer wäre ich für "42", da 42 ja die Antwort auf alles ist.

PS: Gemäss Dozenten ist ein Zusammenhang zwischen den Installationsproblemen bei KOHA und VuFind sehrwahrscheinlich. Gemäss Herrn Sebastian Meyer seien im Apache Webserver die Einstellungen für die KOHA-Installation verändert worden. Was mich nur irritiert ist, dass weder ich noch Herr Felix Lohmeier etwas an Apache änderten. Er benützte die Befehle:   
"sudo systemctl restart koha-common"   
"sudo koha-remove bibliothek"   
"sudo koha-create --create-db bibliothek"   
Womit nachher alles funktionierte. Höchstens mir wäre bei der ersten erfolglosen Installationn von KOHA ungewollt ein Fehler unterlaufen und hätte Änderungen bei Apache vorgenommen.
