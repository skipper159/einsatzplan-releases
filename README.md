# einsatzplan-releases

Einsatzplan: fertige Pakete (Setup, portable ZIP, Android-App) – kein Quellcode.

Dieses Repository enthält zwei getrennte Arten von Releases. Am **Tag** erkennt man, was ein Release ist:

| Tag | Was | Datei | Wer nutzt es |
|---|---|---|---|
| `server-v<Version>` | **Server-App** (Windows-Server, Einsatzplan-Webanwendung) | `Einsatzplan_Server_Setup_<Version>.exe` und `.sha256` | Die Update-Funktion im Company Management liest nur diese Releases. |
| `android-v<Version>` | **Android-App** „VLT-Pilot Mobile“ (Handy für Kolonnenführer und Mitarbeiter) | `Einsatzplan_Android_<Version>.apk` und `.sha256` | Manuelle Installation auf dem Handy. Die Server-Update-Funktion ignoriert diese Releases. |

Versionsnummern von Server und Android-App sind unabhängig voneinander (z. B. Server 2.12.1, Android-App 0.5.0).

Die Releases `v1.x` stammen aus der älteren Excel-Version.

## Serverversionen ab 2.16.0

Aktueller Serverstand ist **2.29.0**. Die Versionen nach 2.16.0 wurden am 07.11.2026 aus den vorhandenen Installern nachgetragen. Jeder Release enthält den Installer, seine SHA-256-Prüfsumme und die Änderungen dieses Versionsstands.

| Version | Versionsdatum | Schwerpunkt |
| --- | --- | --- |
| [2.29.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.29.0) | 06.11.2026 | Mengen und Abrechnungsstand je LV-Position |
| [2.28.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.28.0) | 06.11.2026 | LV-Tagesaufgaben und Nachweiszuordnung im Büro |
| [2.27.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.27.0) | 06.11.2026 | NEVARIS-Projektkorb und Auftrags-LV |
| [2.26.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.26.0) | 06.11.2026 | Verwaltung gezielt delegieren |
| [2.25.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.25.0) | 06.11.2026 | Rechtematrix nach Bereich und Aktion |
| [2.24.1](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.24.1) | 05.11.2026 | Serverunterstützung für Android-App 0.5.4 |
| [2.24.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.24.0) | 05.11.2026 | Administration, Sicherung und Hilfe |
| [2.23.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.23.0) | 05.11.2026 | Stammdaten, Geräte und Standorte |
| [2.22.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.22.0) | 05.11.2026 | Baustellen, Handys und Auswertung |
| [2.21.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.21.0) | 05.11.2026 | Planungsseiten und Tagesvertretung |
| [2.20.1](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.20.1) | 05.11.2026 | Korrekturen an Rechten, Planung und Export |
| [2.20.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.20.0) | 05.11.2026 | Personal, Fristen und Verwaltung |
| [2.19.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.19.0) | 04.11.2026 | Baustellenakte, Eingangsprüfung und Nachweise |
| [2.18.1](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.18.1) | 04.11.2026 | Gerätezugriff nach Standort |
| [2.18.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.18.0) | 04.11.2026 | Seitenaufbau, Live-Feed und Zeitleiste |
| [2.17.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.17.0) | 04.11.2026 | Planung, Suche und Wochenvorlagen |
| [2.16.2](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.16.2) | 03.11.2026 | Korrekturen an Planung und Handy-Eingang |
| [2.16.1](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.16.1) | 03.11.2026 | Geräte und Fahrzeuge übersichtlicher |
| [2.16.0](https://github.com/skipper159/einsatzplan-releases/releases/tag/server-v2.16.0) | 03.11.2026 | NEVARIS Build in der Baustellenakte |
