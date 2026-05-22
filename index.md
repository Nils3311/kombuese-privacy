---
layout: default
title: Datenschutzerklärung — Kombüse
description: Datenschutzerklärung für die iOS-App Kombüse
---

# Datenschutzerklärung

**App:** Kombüse (iOS)
**Verantwortlicher:** Nils Hoffmann, hofnil@web.de
**Stand:** 22. Mai 2026

---

## Kurz und ehrlich

Kombüse ist eine Rezepte- und Einkaufs-App für den Familienalltag. Sie speichert deine Daten **lokal auf deinem Gerät** und — wenn iCloud auf deinem Gerät aktiv ist — in deiner **persönlichen iCloud**. Es gibt **keine eigenen Server**, **kein Tracking**, **keine Werbung** und **keine Analytics**.

KI-Funktionen (Rezept-Import, Bild-Generierung, Tag-Vorschläge) nutzen einen **selbst eingetragenen OpenRouter-API-Key**. Ohne Key bleibt Kombüse voll nutzbar — nur die KI-Aktionen sind deaktiviert.

---

## Welche Daten verarbeitet Kombüse?

| Datenart | Wo gespeichert | Wer hat Zugriff |
|---|---|---|
| Rezepte, Zutaten, Einkaufslisten, Tags, Läden | Lokal auf dem Gerät und in deiner privaten iCloud-Datenbank | Nur du; bei iCloud-Sharing zusätzlich die Personen, die du explizit einlädst |
| Bilder zu Rezepten | Lokal/iCloud (siehe oben) | Nur du bzw. eingeladene Sharing-Partner |
| OpenRouter-API-Key | Im verschlüsselten Keychain des Geräts | Nur du; verlässt das Gerät nur in API-Calls an OpenRouter |
| Inhalte, die du an die KI sendest | Werden bei jedem KI-Call an OpenRouter übertragen | OpenRouter laut deren AGB; siehe unten |
| Sprachaufnahmen im Kochmodus | Werden lokal auf dem Gerät verarbeitet (Apple Speech Recognition) | Niemand außerhalb des Geräts |
| Apple-iCloud-Account-Informationen | Werden ausschließlich von Apple verwaltet | Nur du, gemäß Apple-Datenschutz |

Kombüse verarbeitet **keine** Werbe-Identifier (IDFA), **keine** Standortdaten, **keine** Kontakte, **keine** Telemetrie, **keine** Crash-Reports an eigene Server.

---

## iCloud und Sharing

Wenn du auf deinem Gerät bei iCloud angemeldet bist, synchronisiert Kombüse deine Daten automatisch über deine **private iCloud-Datenbank** zwischen deinen Geräten. Die Daten liegen in Apples Rechenzentren — der App-Entwickler hat **keinen Zugriff** auf deine iCloud-Inhalte.

Wenn du dein Kochbuch über die Funktion **„Teilen"** mit anderen Personen teilst, bekommen genau diese Personen Lese- bzw. Schreibzugriff auf den geteilten Inhalt. Apple verwaltet die Einladung über sein CKShare-System. Du kannst Teilnehmer jederzeit wieder entfernen und das Teilen beenden.

---

## OpenRouter (KI-Funktionen)

Wenn du in den Einstellungen einen **OpenRouter-API-Key** hinterlegst und KI-Funktionen nutzt (z.B. Rezept aus URL importieren, Bild zum Rezept generieren, Tag-Vorschläge), überträgt Kombüse:

- Die Rezept-URL oder den Rezept-Text (für Import)
- Den Rezepttitel und gefilterte Hauptzutaten (für Bild-Generierung)
- Tag-Listen und Rezept-Metadaten (für Tag-Matching)

an OpenRouter (https://openrouter.ai). OpenRouter ist ein US-amerikanischer Routing-Dienst, der die Anfrage je nach gewähltem Modell an Anbieter wie Anthropic, OpenAI oder Google weiterleitet.

Bitte beachte OpenRouters **eigene Datenschutzerklärung**: https://openrouter.ai/privacy

Die Verbindung erfolgt direkt von deinem Gerät zu OpenRouter, ohne Zwischenschritt über andere Server. Kombüse loggt **nichts** außerhalb deines Geräts.

Wenn du keine KI-Funktionen nutzt oder keinen API-Key hinterlegst, werden **keine** Daten an OpenRouter übertragen.

---

## Mikrofon und Spracherkennung

Im Kochmodus kannst du per Sprachbefehl (z.B. „Nächster Schritt", „Timer starten") navigieren. Dafür nutzt Kombüse:

- **Mikrofonzugriff** (`NSMicrophoneUsageDescription`)
- **Spracherkennung** (`NSSpeechRecognitionUsageDescription`) via Apples eingebautes `SFSpeechRecognizer`-Framework

Die Spracherkennung läuft, wo immer Apple das technisch unterstützt, **lokal auf dem Gerät**. Es findet **keine** Übertragung von Audio an OpenRouter, an einen App-Entwickler-Server oder an Dritte statt — nur an Apples System-API.

Du kannst Mikrofon und Spracherkennung jederzeit in den iOS-Einstellungen unter Datenschutz widerrufen.

---

## Lokale Benachrichtigungen und Timer

Kombüse nutzt Apples **AlarmKit** für Kochtimer (`NSAlarmKitUsageDescription`). Die Timer laufen vollständig lokal — es gibt keine Push-Notifications von einem Server.

---

## Wie kannst du deine Daten löschen?

- **Komplett:** App deinstallieren. Lokale Daten werden mit der App entfernt.
- **iCloud-Daten:** in den Einstellungen → „Lokale Daten zurücksetzen" oder über die iOS-Einstellungen → iCloud → Kombüse → Daten löschen.
- **OpenRouter-API-Key:** in den App-Einstellungen → „API-Key entfernen". Der Key wird sofort aus dem Keychain gelöscht.
- **Geteilte Bibliotheken:** in den Einstellungen → „Sharing" → Personen entfernen oder Sharing beenden.

Eine separate Anfrage an den Entwickler ist nicht nötig, da der Entwickler keinen Zugriff auf deine Daten hat.

---

## Kinder

Kombüse richtet sich an Erwachsene und Familien. Die App erfasst aktiv **keine** Daten von Kindern. Inhalte (Rezepte) werden vom Nutzer selbst angelegt.

---

## Änderungen dieser Datenschutzerklärung

Wenn sich die Verarbeitung wesentlich ändert, wird diese Seite aktualisiert. Das Änderungsdatum oben gibt den jeweils aktuellen Stand wieder. Für TestFlight- und App-Store-Versionen gilt jeweils die Version, die zum Zeitpunkt der Installation veröffentlicht war.

---

## Kontakt

Bei Fragen zum Datenschutz oder zur App:

**Nils Hoffmann**
E-Mail: [hofnil@web.de](mailto:hofnil@web.de)

---

<a id="english"></a>

# Privacy Policy (English)

**App:** Kombüse (iOS)
**Controller:** Nils Hoffmann, hofnil@web.de
**Last updated:** 2026-05-22

## Summary

Kombüse is a recipe and shopping list app for families. Your data is stored **locally on your device** and — when iCloud is enabled — in your **personal iCloud**. There are **no developer servers**, **no tracking**, **no advertising**, and **no analytics**.

AI features (recipe import, image generation, tag suggestions) require a **user-provided OpenRouter API key**. Without a key, Kombüse remains fully functional — only AI actions are disabled.

## Data processed

| Type | Stored where | Who has access |
|---|---|---|
| Recipes, ingredients, shopping lists, tags, stores | Locally on device and in your private iCloud database | Only you; people you explicitly invite for sharing |
| Recipe images | Local / iCloud | Only you / sharing participants |
| OpenRouter API key | Device Keychain (encrypted) | Only you; transmitted only in direct API calls to OpenRouter |
| Content sent to AI | Transmitted to OpenRouter per call | OpenRouter per their terms |
| Voice input during cooking mode | Processed locally on device via Apple Speech Recognition | No one outside the device |
| Apple iCloud account info | Managed exclusively by Apple | Only you, per Apple's privacy policy |

Kombüse processes **no** advertising identifiers (IDFA), **no** location data, **no** contacts, **no** telemetry, **no** crash reports sent to developer-owned servers.

## iCloud and Sharing

When signed in to iCloud, Kombüse automatically syncs across your devices via your **private iCloud database**. Data is stored in Apple's data centers — the developer has **no access** to your iCloud content.

When you share a cookbook with others through the in-app **„Share"** function, those specific people get read or write access to the shared content via Apple's CKShare system. You can remove participants and stop sharing at any time.

## OpenRouter (AI features)

If you configure an **OpenRouter API key** in settings and use AI features (import from URL, generate image, suggest tags), Kombüse transmits:

- Recipe URL or recipe text (for import)
- Recipe title and filtered main ingredients (for image generation)
- Tag lists and recipe metadata (for tag matching)

to OpenRouter (https://openrouter.ai), a US-based routing service that forwards requests to providers such as Anthropic, OpenAI, or Google depending on the chosen model. Please review OpenRouter's own privacy policy: https://openrouter.ai/privacy

The connection goes directly from your device to OpenRouter, without an intermediate server. Kombüse logs **nothing** outside your device.

If you don't use AI features or don't configure a key, **no** data is sent to OpenRouter.

## Microphone and Speech Recognition

In cooking mode, you can navigate by voice command (e.g. „next step", „start timer"). Kombüse uses:

- **Microphone access** (`NSMicrophoneUsageDescription`)
- **Speech recognition** (`NSSpeechRecognitionUsageDescription`) via Apple's built-in `SFSpeechRecognizer`

Where supported by Apple, speech recognition runs **on-device**. **No audio is transmitted** to OpenRouter, to any developer-owned server, or to third parties — only to Apple's system APIs.

You can revoke microphone and speech permissions at any time in iOS Settings → Privacy.

## Local Notifications and Timers

Kombüse uses Apple's **AlarmKit** (`NSAlarmKitUsageDescription`) for cooking timers. Timers run entirely locally; there are no push notifications from a server.

## How to delete your data

- **Everything:** uninstall the app. Local data is removed with the app.
- **iCloud data:** in-app Settings → „Reset Local Data" or via iOS Settings → iCloud → Kombüse → Delete Data.
- **OpenRouter API key:** in-app Settings → „Remove API Key" — instantly deleted from Keychain.
- **Shared libraries:** in-app Settings → „Sharing" → remove participants or stop sharing.

No separate request to the developer is required because the developer has no access to your data.

## Children

Kombüse targets adults and families. The app actively collects **no** data from children. Recipe content is created by the user.

## Changes to this policy

Material changes are reflected on this page; the date above shows the current version. The TestFlight or App Store version in use at install time applies for that installation.

## Contact

Questions about privacy or the app:

**Nils Hoffmann**
Email: [hofnil@web.de](mailto:hofnil@web.de)
