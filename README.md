# discord-bot-erklaerung

Discord-Bot **„Hermes Agent"** — Verifizierungs-Materialien für das Discord-Developer-Portal.

## Zweck dieses Repos

Dieses Repository enthält ausschließlich die Dokumente, die Discord im Rahmen der App-Verifizierung verlangt:

| Datei | Zweck | Discord-Portal-Feld |
|---|---|---|
| [terms-of-service.md](./terms-of-service.md) | Nutzungsbedingungen des Bots | „Terms of Service URL" |
| [privacy.md](./privacy.md) | Datenschutzerklärung | „Privacy Policy URL" |
| [app-description.md](./app-description.md) | Kurzbeschreibung der App | „Description" |

Der zugehörige Quellcode und die Hermes-VTOL-Projektdokumentation liegen getrennt:
- Projekt-Dokumentation: [rotorbase/Hermes-VTOL](https://github.com/rotorbase/Hermes-VTOL) (public)

## Verwendung im Discord-Developer-Portal

Nach Merge auf `main` sind die Dateien unter folgenden **GitHub-URLs** erreichbar (im Portal als externe Links eintragen):

- **Terms of Service:**
  `https://github.com/rotorbase/discord-bot-erklaerung/blob/main/terms-of-service.md`
- **Privacy Policy:**
  `https://github.com/rotorbase/discord-bot-erklaerung/blob/main/privacy.md`

Die Kurzbeschreibung aus [app-description.md](./app-description.md) wird in das Textfeld „Description" im Portal kopiert.

## Verifizierungs-Checkliste

- [ ] Team-Ownership: App einem Developer-Team zugewiesen
- [ ] 2FA aktiviert auf dem Discord-Account
- [ ] General Information ausgefüllt (Description + ToS-URL + Privacy-URL)
- [ ] Install-Link im OAuth2-URL-Generator erzeugt und im App-Profil eingetragen
- [ ] Bot-Tab → Privileged Gateway Intents: ☑ Server Members Intent + ☑ Message Content Intent → **Save Changes**
- [ ] Verifizierung beantragt (falls vom Portal verlangt)

## Kontakt

rotorbase@speculatrix.de
