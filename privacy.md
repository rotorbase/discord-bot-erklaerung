# Datenschutzerklärung — Hermes Agent Discord-Bot

**Letzte Aktualisierung:** 2026-09-29

Diese Datenschutzerklärung beschreibt, welche Daten der Discord-Bot „Hermes Agent" erhebt und wie sie verarbeitet werden.

## 1. Verantwortlicher

Verantwortlich für die Datenverarbeitung ist der Betreiber des Bots. Kontakt: rotorbase@speculatrix.de

## 2. Welche Daten wir erheben

### 2.1 Discord-Metadaten

- **Discord-User-ID**: zur Authentifizierung gegen unsere Allow-Liste
- **Channel-ID und Message-ID**: technisch erforderlich, um deine Nachricht zuzuordnen und die Antwort zuzustellen
- **Timestamp** der Nachricht: zur Protokollierung

### 2.2 Gesprächsinhalte

- Deine an den Bot gerichteten Nachrichten
- Die Antworten des Sprachmodells
- Diese Inhalte werden in unserer privaten Backend-Datenbank gespeichert, um Kontext über mehrere Nachrichten hinweg zu erhalten und für Auditzwecke

### 2.3 Technische Metadaten

- Standardmäßige Discord-API-Metadaten (z. B. Antwortzeit, Fehlercodes)
- Wir protokollieren keine IP-Adressen über das hinaus, was Discord ohnehin in seiner API übermittelt

## 3. Was wir NICHT tun

- Wir verkaufen deine Daten nicht an Dritte
- Wir verwenden deine Gespräche nicht, um Modelle Dritter zu trainieren
- Wir teilen deine Gesprächsinhalte nicht ohne deine ausdrückliche Zustimmung

## 4. Wo Daten gespeichert werden

Gespräche werden auf einem privaten virtuellen Server bei Hostinger (EU-Standort) gespeichert. Der Zugang ist durch SSH-Keys und Token-basierte Authentifizierung geschützt.

## 5. Speicherdauer

- Gesprächsverläufe: 90 Tage, danach automatisch gelöscht
- Allow-List-Einträge: bis du ihre Löschung beantragst
- Log-Dateien: 30 Tage
- Auf Anfrage längere Aufbewahrung für laufende Projekte möglich

## 6. Deine Rechte (DSGVO)

Du hast folgende Rechte:

- **Auskunft** (Art. 15 DSGVO): Du kannst erfragen, welche Daten wir über dich haben
- **Berichtigung** (Art. 16): Du kannst unrichtige Daten korrigieren lassen
- **Löschung** (Art. 17): Du kannst die Löschung deiner Daten verlangen
- **Einschränkung der Verarbeitung** (Art. 18)
- **Datenübertragbarkeit** (Art. 20): Du kannst deine Daten in einem maschinenlesbaren Format anfordern
- **Widerspruch** (Art. 21)

Anfragen richte bitte an rotorbase@speculatrix.de. Wir bearbeiten Anfragen innerhalb von 14 Tagen.

## 7. Sicherheit

- SSH-Zugang zum Backend nur mit Schlüsselpaar, kein Passwort-Login
- Discord-Token in einer separaten, nicht öffentlichen Konfigurationsdatei
- Allow-Liste verhindert, dass Unbefugte den Bot nutzen
- Regelmäßige Updates des Hostsystems

## 8. Sprachmodell und Drittlandtransfer

Antworten werden von einem KI-Sprachmodell eines Drittanbieters (Anthropic, betrieben via MiniMax) generiert. Dabei werden deine Nachrichten an diesen Anbieter übermittelt. Der Anbieter verarbeitet die Daten nach eigenen Verträgen mit uns; eine Nutzung für Training findet nicht statt.

## 9. Änderungen

Wir können diese Datenschutzerklärung aktualisieren. Wesentliche Änderungen werden dir über den Bot mitgeteilt.

## 10. Kontakt und Beschwerderecht

Bei Fragen: rotorbase@speculatrix.de
Beschwerderecht bei der zuständigen Aufsichtsbehörde (in Deutschland: die Landesdatenschutzbehörde deines Bundeslandes).
