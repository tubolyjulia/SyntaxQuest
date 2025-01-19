# SyntaxQuest

Dies ist ein persönliches Projekt, das darauf abzielt, eine Webanwendung zu erstellen, die mir hilft, 
Java-Syntax zu üben und meine Fähigkeiten zu verbessern.

## Nächste Schritte / To-Do

### 1. Benötigte Technologien
Um die Anwendung erfolgreich zu entwickeln, benötige ich die folgenden Technologien und Tools:

- **Java 17 oder höher**
    - Die Anwendung wird mit Java 17 entwickelt.
- **Spring Boot**
    - Für die Backend-Entwicklung und die Erstellung einer RESTful API.
- **Spring Security**
    - Um grundlegende Sicherheitsfunktionen wie Authentifizierung und Autorisierung zu implementieren.
- **Maven**
    - Für die Verwaltung von Abhängigkeiten und das Build-Management.
- **H2-Datenbank (für die lokale Entwicklung)**
    - Eine eingebettete Datenbank für die Entwicklung und Tests.
- **Thymeleaf oder ein anderes Frontend-Template (optional)**
    - Falls ein einfaches Frontend benötigt wird.
- **GitHub**
    - Für die Versionskontrolle und das Hosting des Repositories.
- **Logging (Logback/Log4j2)**
    - Zum Implementieren von Log-Meldungen und Fehlerbehandlung in der App.

### 2. Schritt-für-Schritt-Plan

1. **Spring Boot Setup:**
    - Ein neues Spring Boot-Projekt erstellen, um die grundlegende Struktur zu erstellen.
    - Spring Boot Initializr verwenden, um schnell zu starten: [https://start.spring.io/](https://start.spring.io/).

2. **Spring Security einrichten:**
    - Eine einfache Authentifizierung einrichten (z. B. Benutzeranmeldung mit Benutzername und Passwort).
    - Benutzerrollen definieren und das Zugriffskontrollmodell umsetzen (z. B. Admin vs. Benutzer).

3. **Datenbank konfigurieren:**
    - Eine einfache Datenbankstruktur entwerfen (z. B. Tabellen für Benutzer und Übungen).
    - Die Verbindung zur Datenbank einrichten (z. B. mit H2 oder MySQL für spätere Erweiterung).

4. **REST API erstellen:**
    - Endpoints für Benutzer-Interaktionen definieren (z. B. `GET /exercises`, `POST /submitAnswer`).
    - JSON-Response mit Rückmeldungen zu den Aufgaben und Lösungen einbauen.

5. **Frontend entwickeln (optional):**
    - Wenn nötig, eine einfache Benutzeroberfläche erstellen, die über Thymeleaf oder ein anderes Template-Engine angezeigt wird.

6. **Tests implementieren:**
    - Unit-Tests für die wichtigsten Funktionalitäten (z. B. Benutzerregistrierung, Login, Übungen).
    - Integrationstests für die REST API.

7. **Dokumentation:**
    - Das Projekt weiter dokumentieren, um zu erklären, wie die API und die App insgesamt verwendet werden.
   
8. **Logging hinzufügen:**
    - Logback (oder Log4j2) für die Protokollierung von Ereignissen und Fehlern einrichten.
    - Wichtige Ereignisse wie Anmeldungen, API-Anfragen, Fehler und Systemstatus protokollieren.
    - Beispiel: `logger.info("User successfully logged in.");`

### 3. Weitere Ressourcen

- [Spring Boot Documentation](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [Spring Security Guide](https://spring.io/guides/topicals/spring-security-architecture/)
- [Maven Documentation](https://maven.apache.org/guides/)
- [Logback Documentation](http://logback.qos.ch/)
- [Log4j2 Documentation](https://logging.apache.org/log4j/2.x/)

## Nächste Aufgaben:

1. **Spring Boot-Projekt erstellen.**
2. **Spring Security einrichten und einfache Authentifizierung implementieren.**
3. **Datenbank mit Benutzerdaten und Übungen erstellen.**
4. **REST API mit Endpoints für Übungen und Benutzeranmeldung entwickeln.**
5. **Logging mit Logback einrichten und grundlegende Log-Meldungen implementieren.**

## Lizenz

Dieses Projekt ist für den persönlichen Gebrauch und als Übung gedacht. Es ist nicht für kommerzielle Zwecke bestimmt.
Alle Rechte vorbehalten.
