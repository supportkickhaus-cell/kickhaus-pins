# KICKHOUSE — Instagram-Protokoll (Konto store.kickhaus)

Diese Datei ist maßgeblich für die Instagram-Aufgabe. Nach jedem Post muss sie
aktualisiert werden, sonst wird doppelt gepostet.

## Feste Werte

- Composio-Instagram-Account: `instagram_typify-thanan` (= store.kickhaus). Bei JEDEM Instagram-Aufruf als `account` mitgeben.
- ig_user_id: `29946684561586646`
- Andere Instagram-Accounts (thecloc_watches, trikotdistrict, fabrikstadt_gz) NIEMALS benutzen.
- Bild-Raw-URL: `https://raw.githubusercontent.com/supportkickhaus-cell/kickhaus-pins/main/<datei>`
- Pro Lauf genau EIN Post, Einzelbild.

## Bildauswahl

Instagram läuft **rückwärts** durch die Poster (von `kickhouse_97` abwärts), damit
sich Instagram und Pinterest nicht überschneiden — Pinterest arbeitet vorwärts ab 01.

Regel: Das Bild mit der **höchsten** `kickhouse_<Nr>`-Nummer nehmen, das
(a) im Repo vorhanden ist und (b) noch nicht in der Tabelle „Gepostet" steht.
Ist keins mehr übrig: nichts posten, User informieren, aufhören.

Modelltitel, Modelltext und Modell-Hashtags kommen aus `kickhouse-queue.md` —
dort steht zu jedem Bild der passende Eintrag. Nichts erfinden.

## Textformat (Caption)

```
KICKHOUSE – <Modelltitel>

<Modelltext>

<Modell-Hashtags>

👑 KICKHOUSE – Luxury Kicks. Exclusive Style. 🔥
📱 WhatsApp: +86 195 8628 6566
#Kickhouse #LuxurySneakers #SneakerCulture #Sneakerhead #DesignerSneakers #StreetwearLuxury #ExclusiveKicks #PremiumStyle #FreshKicks #SneakerCommunity #KicksDaily
```

Caption als normalen Text übergeben (NICHT URL-kodieren). Nach dem Posten mit
INSTAGRAM_GET_IG_MEDIA prüfen, dass die Hashtags als „#…" angekommen sind, nicht als „%23…".
alt_text = Modelltitel. Niemals THE-CLOC-Texte oder die CLOC-WhatsApp-Nummer verwenden.

## Gepostet

| Datum (UTC+8) | Bild | Modell | Permalink |
|---|---|---|---|
| 2026-10-08 18:20 | kickhouse_97_ugg_tazz-platform_chestnut-2.jpg | UGG Tazz Platform „Chestnut" | https://www.instagram.com/p/DeOtKlQFYgw/ |
| 2026-10-08 20:11 | kickhouse_96_ugg_classic-ultra-mini-platform_chestnut.jpg | UGG Classic Ultra Mini Platform „Chestnut" | https://www.instagram.com/p/DeO535zoP0q/ |
