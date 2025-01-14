# Zeitstempel-System 🕒

Ein einfaches Zeitstempel-System, mit dem sich Nutzer registrieren, einloggen und ihre Aktivitätszeit verfolgen können.

## 📖 Funktionen

- **Benutzerregistrierung**:  
  Neue Nutzer können sich mit ihren Zugangsdaten registrieren.

- **Login**:  
  Nach der Registrierung können sich Nutzer einloggen und ein einfaches Userinterface sehen. Dort können sie sich ein- und ausstempeln.

- **Timer**:  
  Über den Einstempeln/Ausstempeln-Knopf kann der Nutzer den Timer starten oder stoppen.
    - **Einstempeln**: Startet den Timer.
    - **Ausstempeln**: Stoppt den Timer und speichert die aufgezeichnete Zeit in der Datenbank.

- **Datenbankintegration**:  
  Alle Nutzerdaten und Zeitstempel werden sicher in einer PostgreSQL-Datenbank gespeichert.

## 🌟 Geplante Features
Das sind die Features die vielleicht passieren.
Mit hoher Wahrscheinlichkeit nicht da dies einfach nur ein kleines Freizeitprojekt ist.
Falls diese Features doch gewollt sind, gerne ein Issue erstellen oder selber hinzufügen :D
- **Dashboard**: Übersicht der Zeitstempel und Statistiken pro Nutzer.
- **Admin-Bereich**: Verwaltung von Nutzern und deren Zeitstempeln.
- **API-Integration**: Bereitstellung von REST-Endpoints zur Interaktion mit externen Systemen.
- **Front-End**: Naja brauch man halt damits cool aussieht
- **Mobile**: Anpassung auf Mobile-UI, vielleicht React Native App

## 📋 Anforderungen

- **Java 17** oder neuer
- **Spring Boot** (Framework für die Backend-Entwicklung)
- **PostgreSQL** (Datenbank zur Speicherung von Nutzerdaten und Zeitstempeln)
- **Maven** (für Abhängigkeitsmanagement und Build-Prozess)

## 🚀 Installation

1. **Projekt klonen**:
   ```bash
   git clone https://github.com/Rxbsi/stempelsystem
   cd stempelsystem
