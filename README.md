# einsatzplan-releases

Einsatzplan: fertige Pakete (Setup, portable ZIP, Android-App) – kein Quellcode.

Dieses Repository enthält zwei getrennte Arten von Releases. Am **Tag** erkennt man, was ein Release ist:

| Tag | Was | Datei | Wer nutzt es |
|---|---|---|---|
| `server-v<Version>` | **Server-App** (Windows-Server, Einsatzplan-Webanwendung) | `Einsatzplan_Server_Setup_<Version>.exe` und `.sha256` | Die Update-Funktion im Company Management liest nur diese Releases. |
| `android-v<Version>` | **Android-App** „VLT-Pilot Mobile“ (Handy für Kolonnenführer und Mitarbeiter) | `Einsatzplan_Android_<Version>.apk` und `.sha256` | Manuelle Installation auf dem Handy. Die Server-Update-Funktion ignoriert diese Releases. |

Versionsnummern von Server und Android-App sind unabhängig voneinander (z. B. Server 2.12.1, Android-App 0.5.0).

Die Releases `v1.x` stammen aus der älteren Excel-Version.
