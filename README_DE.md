# BE Assessment II


## Beantworte die folgenden Fragen

1.  (multiple choice) ORM...

    - [ ] steht für "Object-Relational-Mapper"
    - [ ] nutzt eine objektorientierte Programmiersprache als Technik zum Zugriff auf relationale Datenbanken
    - [ ] konzentriert sich mehr auf Geschäftslogik und weniger auf das Schreiben von Schnittstellen
    - [ ] alle Aussagen treffen zu

2.  (W/F) Ein ORM verknüpft (engl. "map") ein Objekt-Modell mit einer relationalen Datenbank. Ein ODM verknüpft ein Objekt-Modell mit einer Dokumenten-Datenbank.

    - [ ] Wahr
    - [ ] Falsch

3.  (Tippen Sie Ihre Antwort) Wie kann Mongoose für eine Anwendung installiert werden?

    - 

4.  (Mehrfachantwort) Welche der folgenden Aussagen sind richtig?

    - [ ] ‘Collections’ in Mongo sind äquivalent zu Tabellen einer relationalen Datenbank.
    - [ ] ‘Schema’ in Mongo wird über eine Tabellen-Definition definiert.
    - [ ] ‘Documents’ sind äquivalent zu Reihen von Daten in SQL.
    - [ ] 'Models' sind Konstruktoren höherer Ordnung und erzeugen Dokument-Instanzen, die äquivalent zu Einträgen einer relationalen Datenbank sind.

5.  (W/F) Ein Mongoose-Schema definiert die Dokumentstruktur, Standard-Werte, Prüffunktionen (engl. "validators"), usw.

    - [ ] Wahr
    - [ ] Falsch

6.  (Mehrfachantwort) Welche der folgenden Schema-Typen sind in Mongoose sind verfügbar?

    - [ ] Array
    - [ ] Boolean
    - [ ] Buffer
    - [ ] Object
    - [ ] Mixed
    - [ ] ObjectId

7.  (W/F) Sollte eine neue Verbindung für jede Datenbank-Operation auf- und abgebaut werden?

    - [ ] Nein. Baue die Verbindung beim Start der Anwendung auf und lasse sie offen bis die Anwendung endet.
    - [ ] Ja. Die Verbindung wird automatisch von der Anwendung abgebaut, sobald die Operation abgeschlossen ist.

8.  (Mehrfachantwort) Das Schema beschreibt die Attribute der Eigenschaften, die durch die Anwendung manipuliert werden. Zu diesen Attributen gehören:

    - [ ] ob der Wert erforderlich (engl. "required") ist
    - [ ] der Datentyp
    - [ ] ob der Wert eindeutig (engl. "unique") ist

9.  (W/F) Eine ObjectId ist ein spezieller Typ der typischerweise für eindeutige IDs (engl. "unique identifiers") genutzt wird.

    - [ ] Wahr
    - [ ] Falsch

10.  (W/F) Eine ObjectId wird typischerweise durch einen "24 Hexadezimal Character String" repräsentiert, bspw. '5e4bad2a0ab24550afceed7a'.

    - [ ] Wahr
    - [ ] Falsch

11.  (Mehrfachantwort) Welche der folgenden Aussagen treffen auf den Vorgan der "Population" zu?

    - [ ] Ist der Prozess automatisch spezifizierte Pfade im Dokument mit Dokumenten aus anderen "Collection(s)" zu ersetzen.
    - [ ] Ein/mehrere Dokumente oder einfache (engl. "plain") Objekte oder alle von einer Abfrage zurückgegebenen Objekte mit Werten zu füllen (engl. "populate").
    - [ ] Ist in jeder Anwendung für mindestens ein Dokument erforderlich (engl. "required").
    - [ ] alle Aussagen treffen zu

12.  (W/F) Mit Prüffunktionen (engl. "validators") in Mongoose können Duplikate in Datenbanken verhindert werden. Eine Prüffunktion ist eine Middleware und wird im SchemaType definiert. Eine eigene Prüffunktion kann im Schema definiert werden, oder es werden Mongoose eigene (engl. "built in") Prüffunktionen genutzt.

    - [ ] Wahr
    - [ ] Falsch

13.  (multiple choice) Wie wird eine Verbindung mit einer lokalen MongoDB-Instanz aufgebaut?

    - [ ] mongoose.connect('https://localhost:27017/myapp', {useNewUrlParser: true});
    - [ ] mongoose.connect('ssh://localhost:27017/myapp', {useNewUrlParser: true});
    - [ ] mongoose.connect('mongodb://localhost:27017/myapp', {useNewUrlParser: true});
    - [ ] mongoose.connect('mongoose://localhost:27017/myapp', {useNewUrlParser: true});

14.  (multiple choice) Die "timestamps"-Option führt dazu, dass Mongoose die Felder 'createdAt' und 'updatedAt' zum Schema hinzufügt.

    - [ ] Wahr
    - [ ] Falsch

15.  (W/F) Die "bcrypt" Hash-Funktion erlaubt es eine Passwort-Sicherheits-Plattform zu bauen, die mit der Rechenkraft skaliert und jedes Passwort mit einem "Salt" versieht und dann den Hash-Wert berechnet. Sie kann nur mit JavaScript genutzt werden.

    - [ ] Wahr
    - [ ] Falsch

16.  (multiple choice) "JSON Web Tokens" können genutzt werden, um

    - [ ] ein Token zu generieren, zu dekodieren und zu speichern
    - [ ] ein Token zu dekodieren, zu verifizieren und zu generieren.
    - [ ] ein Token zu generieren, zu verifizieren und hochzuladen.
    - [ ] keine Aussagen treffen zu

17.  (Mehrfachantwort) Was ist Teil eines "JWT Token"?

    - [ ] Header
    - [ ] Payload
    - [ ] Signature
    - [ ] Hash

18.  (W/F) Multipart-Requests kombinieren ein oder mehrere Datensätze in einen einzelnen "Body", jeweils mit Trenner (engl. "boundary") versehen. Typischerweise werden solche Requests genutzt, um Dateien hochzuladen und Daten mehrerer Typen innerhalb eines einzelnen Requests zu übermitteln (z. B. eine Datei zusammen mit einem JSON-Objekt).

    - [ ] Wahr
    - [ ] Falsch

19.  (W/F) "CSRF" ist die Abkürzung für "Cross-Site Response Forgery".

    - [ ] Wahr
    - [ ] Falsch

20.  (W/F) Ein HTTP-Cookie ist eine kleine Menge von Daten, die auf dem Computer des Nutzers durch den Web-Browser gespeichert wird. Cookies sind entwickelt worden, um eine zuverlässige Methode zu haben, damit Websites zustandsbehaftete Informationen speichern können oder um die Browsing-Aktivität eines Nutzers nachvollziehen zu können.

    - [ ] Wahr
    - [ ] Falsch
