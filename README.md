# Aufgabe Makroarchitektur Teil 1 (Modulith + Theorie)


1. Theorie: Recherchiere zu folgenden Fragestellungen und fasse deine Erkenntnisse übersichtlich und illustrativ zusammen!

    - Was ist Sofwarearchitektur?
    Softwarearchitektur bezeichnet die grundlegende Struktur einer Software, einschließlich der Art und Weise, wie diese Struktur ihre Verhaltensaspekte behandelt. Sie umfasst die Funktionen und Eigenschaften, die nützlich sind, wenn das Softwareprodukt ein System bildet oder ein Systemteil ist. Es handelt sich dabei um die Definition der Systemkomponenten, ihrer externen Eigenschaften und ihrer Beziehungen zueinander und zur Umgebung.
    Die Softwarearchitektur ist entscheidend für das Verständnis, wie ein System oder eine Softwareanwendung funktioniert. Sie bietet einen Plan und ein koordiniertes Regelwerk, das dazu beiträgt, die Komplexität eines Systems zu bewältigen. Hierbei handelt es sich um Regeln, die bei der Konstruktion des Systems helfen, etwa um Standards und Richtlinien.
    Im Allgemeinen kann die Softwarearchitektur verschiedene Sichten oder Perspektiven umfassen, darunter:

        - Strukturansicht: Wie ist die Software in Module oder Komponenten unterteilt und wie interagieren diese miteinander?

        - Verhaltensansicht: Wie verhalten sich die einzelnen Komponenten und das Gesamtsystem in Bezug auf bestimmte Eingaben oder Ereignisse?

        - Praktische Ansicht: Wie wird die Software in der realen Welt eingesetzt, wie kann sie gewartet und erweitert werden, und welche nicht-funktionalen Anforderungen (z. B. Leistung, Sicherheit, Zuverlässigkeit) muss sie erfüllen?

    Die Softwarearchitektur dient auch als Kommunikationsmittel zwischen den verschiedenen Stakeholdern (wie Entwicklern, Projektmanagern, Kunden usw.), da sie einen gemeinsamen Rahmen für das Verständnis der wichtigsten Designentscheidungen bietet. Sie unterstützt zudem die Planung und Abstimmung von Aufgaben während des gesamten Softwareentwicklungslebenszyklus.

    - Wie kann man Softwarearchitektur dokumentieren?
    Die Dokumentation der Softwarearchitektur ist ein wichtiger Teil des Entwicklungsprozesses. Sie dient als Leitfaden für das Entwicklerteam und ermöglicht eine bessere Kommunikation mit Stakeholdern. Sie kann auch dazu beitragen, die Qualität der Software zu verbessern und die Wartung zu erleichtern. Es gibt verschiedene Ansätze zur Dokumentation der Softwarearchitektur, aber hier sind einige grundlegende Schritte und Methoden, die oft verwendet werden:

        - Architekturbeschreibung: Der erste Schritt besteht darin, eine Übersicht über die Architektur zu erstellen. Dies sollte eine klare und prägnante Beschreibung der Gesamtstruktur und der einzelnen Komponenten umfassen, einschließlich ihrer Beziehungen zueinander und zur externen Umgebung.

        - Diagramme: Visuelle Darstellungen können oft hilfreich sein, um die Struktur und das Verhalten der Software zu veranschaulichen. Dazu können UML-Diagramme (Unified Modeling Language) wie Klassendiagramme, Sequenzdiagramme und Zustandsdiagramme gehören.

        - Technische Details: Detaillierte Informationen über die einzelnen Komponenten und ihre Beziehungen können ebenfalls hilfreich sein. Dies kann die Spezifikationen der Komponenten, die verwendeten Technologien und Plattformen, Datenstrukturen, Algorithmen und mehr umfassen.

        - Nicht-funktionale Anforderungen: Diese sollten ebenfalls dokumentiert werden, einschließlich der Leistungs-, Sicherheits-, Zuverlässigkeits- und anderen Anforderungen, die die Software erfüllen muss.

        - Entwurfsentscheidungen: Dokumentieren Sie die Gründe für bestimmte Entwurfsentscheidungen. Dies kann helfen, zukünftige Entscheidungen zu informieren und bietet einen Einblick in den Prozess der Softwareentwicklung.

        - Richtlinien zur Wartung und Erweiterung: Diese können dazu beitragen, die langfristige Wartung und Erweiterung der Software zu erleichtern.

    Es gibt auch verschiedene Standards und Rahmenwerke zur Dokumentation der Softwarearchitektur, wie das ISO/IEC/IEEE 42010:2011, das eine Anleitung zur Dokumentation der Softwarearchitektur bietet, und das "4+1" Architekturmodell, das einen Ansatz zur Darstellung von Architekturen unter Verwendung von mehreren, miteinander verbundenen Sichten bietet.

    - Welches sind die wichtigsten Eigenschaften von Langlebigen Softwarearchitekturen (Lilienthal)?
    Carola Lilienthal ist eine anerkannte Expertin auf dem Gebiet der Softwarearchitektur, insbesondere in Bezug auf langlebige Softwarearchitekturen und das Management technischer Schulden. In ihrem Buch "Langlebige Software-Architekturen: Technische Schulden analysieren, begrenzen und abbauen" betont sie mehrere Schlüsseleigenschaften und Praktiken, die dazu beitragen, die Lebensdauer einer Softwarearchitektur zu verlängern:

        - Verständlichkeit: Die Architektur sollte leicht zu verstehen und klar dargestellt sein, damit Entwickler sie effizienter warten und erweitern können.

        - Konsistenz: Eine einheitliche und konsistente Architektur hilft dabei, Fehler zu reduzieren und das Verständnis des Systems zu erleichtern.

        - Nachvollziehbarkeit: Entscheidungen, die die Architektur beeinflussen, sollten gut dokumentiert und begründet sein. Dies erleichtert zukünftige Wartungs- und Weiterentwicklungsaufgaben.

        - Robustheit: Eine robuste Architektur sollte in der Lage sein, Änderungen in den Anforderungen oder der Umgebung zu bewältigen, ohne dass umfangreiche Umstrukturierungen oder Umbauten erforderlich sind.

        - Minimierung technischer Schulden: Technische Schulden sollten so weit wie möglich minimiert werden. Dies beinhaltet die bewusste Anerkennung und Überwachung solcher Schulden und die Anstrengung, sie im Laufe der Zeit abzubauen.

        - Fokus auf Qualität: Die Architektur sollte Qualitätsanforderungen wie Leistung, Sicherheit und Zuverlässigkeit von Anfang an berücksichtigen und diese nicht als nachträgliche Überlegung behandeln.

        - Evolutionäre Entwicklung: Die Architektur sollte flexibel genug sein, um sich mit der Zeit weiterzuentwickeln und sich an verändernde Anforderungen anzupassen.

    Diese Merkmale tragen dazu bei, dass die Softwarearchitektur langlebig ist, also eine hohe Lebensdauer und Anpassungsfähigkeit hat. Die Idee ist, eine Balance zwischen den aktuellen Anforderungen und der langfristigen Wartbarkeit und Erweiterbarkeit der Software zu finden.

    - Was ist ein Modulith?
    Der Begriff "Modulith" wurde von Oliver Drotbohm geprägt und wird verwendet, um eine bestimmte Art von Softwarearchitektur zu beschreiben. Ein Modulith ist ein monolithisches System, das aber intern so strukturiert ist, dass es modulare Eigenschaften aufweist. Das heißt, es ist in eigenständige Module unterteilt, die jeweils eine bestimmte Aufgabe oder Funktion erfüllen.

    Jedes Modul eines Moduliths sollte so konzipiert sein, dass es unabhängig von den anderen funktionieren kann. Die Kommunikation zwischen den Modulen erfolgt über definierte Schnittstellen. Dies ermöglicht eine klare Trennung von Zuständigkeiten und verbessert die Übersichtlichkeit und Wartbarkeit des Systems.

    Ein Modulith ist somit ein Kompromiss zwischen einem Monolithen und einer Microservices-Architektur. Er bietet viele Vorteile der Microservices (wie die Modularität und die Isolierung der Komponenten) ohne einige der Herausforderungen, die mit der Verwaltung einer verteilten Architektur verbunden sind (wie Netzwerklatenz, Datenkohärenz und komplexe Service-Orchestrierung).

    Es ist wichtig zu beachten, dass ein Modulith nicht nur eine zufällige Sammlung von Modulen ist. Es erfordert eine sorgfältige Planung und Architektur, um sicherzustellen, dass jedes Modul effektiv isoliert ist und gleichzeitig effizient mit den anderen Modulen kommunizieren kann.

    - Wie funktioniert die Ports and Adapters Architektur?
    Die Ports and Adapters Architektur, auch bekannt als Hexagonal Architektur, wurde von Alistair Cockburn entwickelt. Sie zielt darauf ab, die Anwendung von den Details der Infrastruktur zu entkoppeln, um die Unabhängigkeit und Austauschbarkeit zu erhöhen.
    Hier ist eine vereinfachte Beschreibung davon, wie die Ports and Adapters Architektur funktioniert:

        - Die Anwendung im Zentrum (Hexagon): Die Geschäftslogik der Anwendung, auch als "Domain Model" bezeichnet, bildet das Zentrum der Architektur. Diese Kernkomponente ist unabhängig von den technologischen Details der Anwendung und sollte in einer idealen Welt ohne Kenntnis von Datenbanken, Benutzeroberflächen oder externen Systemen existieren können.

        - Ports: Ports repräsentieren die Schnittstellen, durch die die Anwendung mit der Außenwelt interagiert. Es gibt primäre Ports, die von der Anwendung selbst genutzt werden, um ihre Funktionalität zur Verfügung zu stellen (z.B. Services, die von einer Benutzeroberfläche genutzt werden), und sekundäre Ports, die von der Anwendung genutzt werden, um auf externe Ressourcen zuzugreifen (z.B. Datenbanken, Webdienste).

        - Adapters: Adapter sind Implementierungen, die zu einem Port passen und die Kommunikation zwischen der Anwendung und der Außenwelt ermöglichen. Sie übersetzen Anfragen und Daten zwischen den Formaten, die von der Anwendung und den externen Systemen verwendet werden. Zum Beispiel könnte ein Adapter eine Datenbankanfrage in einen Aufruf an die Geschäftslogik der Anwendung umwandeln.

    Der Hauptvorteil dieser Architektur besteht darin, dass sie die Anwendung von der Infrastruktur entkoppelt. Dies bedeutet, dass man Teile der Infrastruktur (wie Datenbanken oder Benutzeroberflächen) ändern oder austauschen kann, ohne die Kernlogik der Anwendung zu beeinflussen. Dies erhöht die Flexibilität und erleichtert das Testen der Anwendung.

    - DDD: Was sind die wesentlichen Bausteine des modellgetriebenen Entwurfs (Taktische Pattern) aus DDD?
    Beim Domain-Driven Design (DDD) gibt es eine Reihe von "taktischen Mustern" oder Bausteinen, die zur Implementierung des modellgetriebenen Entwurfs verwendet werden. Die folgenden sind die wichtigsten:

        - Entity (Entität): Eine Entität ist ein Objekt, das nicht nur durch seine Attribute, sondern vor allem durch eine Kontinuität und Identität über die Zeit und über verschiedene Darstellungen hinweg definiert ist. Ein Beispiel für eine Entität könnte ein bestimmter Benutzer in einem System sein.

        - Value Object (Wertobjekt): Ein Value Object ist ein Objekt, das Attribute hat, aber keine eindeutige Identität benötigt. Sie sind oft unveränderlich und können frei ersetzt und zwischen Objekten ausgetauscht werden. Beispiele sind Dinge wie Farben, Geldbeträge oder Adressen.

        - Aggregate: Ein Aggregate ist eine Ansammlung von Objekten, die als Einheit behandelt werden. Es gibt ein Wurzelobjekt (Aggregate Root), über das alle Interaktionen mit dem Aggregate laufen. Dieses Muster wird verwendet, um Konsistenzgrenzen zu gewährleisten und Datenintegrität zu sichern.

        - Domain Event (Domänenereignis): Ein Domain Event ist etwas, das in der Domäne passiert und von Bedeutung ist. Es wird oft verwendet, um zustandsändernde Ereignisse zu modellieren, die für das Geschäft relevant sind.

        - Service: Ein Service ist eine Operation, die nicht natürlich als Methode eines Value Objects oder einer Entität passt. Sie definieren Handlungen, die vom Modell ausgeführt werden können.

        - Repository: Ein Repository stellt eine Sammlung von Objekten zur Verfügung, die Sie speichern und abrufen können. Es stellt oft Methoden zur Verfügung, um Objekte basierend auf bestimmten Kriterien zu finden.

        - Factory: Eine Factory wird verwendet, um die Erstellung komplexer Objekte und Aggregate zu kapseln.

    Diese taktischen Muster sind Bestandteile eines größeren "strategischen Design", das auch Kontexte, Bounded Contexts, und die Beziehungen zwischen ihnen (Kontextzuordnung) beinhaltet. DDD ist ein mächtiges Werkzeug für das Modellieren komplexer Geschäftslogik und diese taktischen Muster sind die Bausteine, mit denen dieses Modell erstellt wird.

2. Abgabe der Architekturanalyse des bestehenden erplite-Backends
    - Dokumentation (texthelle Beschreibung, Codeauszüge, C4-Diagramme, Klassendiagramme) der Ports-Und-Adapters-Architektur und der DDD-Bestandteile (taktische Muster) von Ordermanagement anhand der gegebenen Anwendungsfälle, die schon implementiert sind:
Bestellung aufgeben
Bestellung auf bezahlt setzen
Packliste generieren
Packlistenitems abhaken
Bestellung auf IN_DELIVERY setzen wenn alle Packlistenitems gepackt sind
    - Dokumentation (texthelle Beschreibung, Codeauszüge, Diagramme, C4-Diagramme, Klassendiagramme) der "Architektur" von Stockmanagement anhand der gegebenen Anwendungsfälle, die schon implementiert sind:
Packingliste anlegen
Packingitems als verpackt markieren