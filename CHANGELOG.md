# Changelog

Alle relevanten Änderungen an diesem Projekt werden hier dokumentiert.

Das Format basiert auf [Keep a Changelog](https://keepachangelog.com/de/1.1.0/) und folgt [Semantic Versioning](https://semver.org/lang/de/).

## [1.0.0] - 2026-03-31

### Hinzugefügt
- Interaktive 120-Sekunden-Simulation mit 6 Szenen (WhatsApp, Instagram, TikTok, Homescreen, iMessage, Hilfsangebote)
- Pausierbares Timer-System für Workshop-Einsatz (alle Timer, Sounds, Uhr eingefroren)
- Web Audio API Sound-Engine (App-spezifische Benachrichtigungstöne)
- Echtzeit-Uhr und heutiges Datum auf dem simulierten Phone
- Firebase Realtime Database View-Counter mit Tageslimit (5000/Tag)
- Mehrsprachigkeit (Deutsch + Englisch) via i18n-System
- Automatische Spracherkennung (URL-Parameter, localStorage, Browser-Sprache)
- Konfigurierbare Helpline auf der CTA-Seite (Logo, Slogan, Links über config.js)
- Content Security Policy mit SRI-Hashes für externe Scripts
- Impressum-Modal im Phone-Frame-Design (DSGVO-konform)
- Erweiterter Disclaimer (Markenrechte, keine Plattform-Verbindung, optionaler Genehmigungshinweis)
- 84 Unit-Tests mit 1698 Assertions (QUnit)
- JSDoc-Dokumentation für alle Funktionen
- Open-Source-Dokumentation (README, CONTRIBUTING, SECURITY, LICENSE, CHANGELOG)
- Automatisches Cache-Busting bei Deploy (scripts/cache-bust.sh)
- Icon-Download-Script für Forks (setup.sh)
- GitHub Issue Templates, FUNDING.yml
