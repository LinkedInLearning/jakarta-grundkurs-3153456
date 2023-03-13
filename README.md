# Jakarta Grundkurs

Dies ist das Repository für den **LinkedIn Learning** Kurs `Jakarta Grundkurs`. Den gesamten Kurs finden Sie auf [LinkedIn Learning][lil-course-url].

![COURSENAME][lil-thumbnail-url] 

Jakarta EE ist der Nachfolger von Java EE (Enterprise Edtion) und stellt eine Erweiterung der Programmiersprache Java zur Entwicklung von Cloud Native Enterprise-Anwendungen dar. Dieses Videotraining vermittelt Ihnen die Grundlagen, um selbständig eigene Jakarta-EE- Projekte umzusetzen: Zunächst lernen Sie die wichtigsten Komponenten der Jakarta-Plattform kennen und sehen, was es heißt, ein Projekt von Java EE zu Jakarta EE zu migrieren. Sie implementieren REST-Web-Services mit JAX-RS und JSON-B und lernen, wie sie mithilfe von CDI Dependency Injection und Inversion of Control unkompliziert umsetzen können.  Anhand von Code-Challenges am Ende jeden Kapitels können Sie das Erlernte sofort testen und Ihre Lösung auch gleich mit der von Ihrem Trainer angebotenen Solution vergleichen.

## Anleitung

Dieses Repository hat Branches für jedes Video im Kurs. Verwenden Sie das Ausklappmenü "Branch: ..." in GitHub um zwischen den unterschiedlichen Branches hin und her zu wechseln bzw. um bei einem spezifischen Status einzusteigen. Oder Sie fügen `/tree/BRANCH_NAME` der URL hinzu um direkt in den gewünschten Branch zu wechseln.

## Branches
Alle Inhalte sind direkt im `master`-Branch abgelegt.

## Installation

1. Um diese Übungsdateien nutzen zu können, müssen Sie folgendes installiert haben:
   - JDK8 (z.B. Eclipse Temurin)
   - Apache Maven
   - Eclipse Glassfish 6.0.0
2. Klonen Sie das Repository in Ihre lokale Maschine unter Verwendung von Terminal (Mac), CMD/PS (Windows) oder ein anderes Werkzeug mit grafischer Bedienoberfläche wie SourceTree.
3. Bauen Sie das Jakarta Artefakt mithilfe von Maven und deployen Sie es in den laufenden Glassfish Server:
   - `mvn package`
   - `cp target/example.war $GLASSFISH_HOME/domains/domain1/autodeploy/   

### Autor

**Kevin Wittek**

_Software Engineer, Coach & Trainer_

Sie finden [weitere Kurse von Kevin Wittek](https://www.linkedin.com/learning/instructors/kevin-wittek) auf LinkedIn Learning. Folgen Sie ihm auf [LinkedIn](https://www.linkedin.com/in/kevin-wittek?trk=lil_instructor) und [Twitter](https://twitter.com/kiview). 

[lil-course-url]: https://www.linkedin.com/learning/jakarta-ee-grundkurs/cloud-native-enterprise-anwendungen-mit-jakarta-ee-entwickeln
[lil-thumbnail-url]: https://cdn.lynda.com/course/3153456/3153456-1644313556981-16x9.jpg
