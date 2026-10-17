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
| 2026-10-09 10:10 | kickhouse_95_ugg_goldenstar-clog_chestnut.jpg | UGG Goldenstar Clog „Chestnut" | https://www.instagram.com/p/DeQZ5kekYXn/ |
| 2026-10-09 14:10 | kickhouse_94_ugg_lace-low-moc_chestnut.jpg | UGG Lace Low Moc „Chestnut" | https://www.instagram.com/p/DeQ1YQFlRTh/ |
| 2026-10-09 20:18 | kickhouse_93_ugg_ballet-flat_sand.jpg | UGG Ballet Flat „Sand" | https://www.instagram.com/p/DeRfdwQIHR7/ |
| 2026-10-10 10:10 | kickhouse_92_ugg_mary-jane-platform_sand.jpg | UGG Mary Jane Platform „Sand" | https://www.instagram.com/p/DeS-sdAAOFF/ |
| 2026-10-10 14:10 | kickhouse_91_ugg_classic-ultra-mini_chestnut.jpg | UGG Classic Ultra Mini „Chestnut" | https://www.instagram.com/p/DeTaJvgFbrE/ |
| 2026-10-10 20:10 | kickhouse_90_ugg_lowmel_sand.jpg | UGG Lowmel „Sand" | https://www.instagram.com/p/DeUDUraoG0W/ |
| 2026-10-11 10:10 | kickhouse_89_ugg_lowmel_chestnut.jpg | UGG Lowmel „Chestnut" | https://www.instagram.com/p/DeVjgAsAN_u/ |
| 2026-10-11 14:10 | kickhouse_88_ugg_tasman_chestnut.jpg | UGG Tasman „Chestnut" | https://www.instagram.com/p/DeV-8ObFZp5/ |
| 2026-10-11 20:10 | kickhouse_87_ugg_tazz-platform_chestnut.jpg | UGG Tazz Platform „Chestnut" | https://www.instagram.com/p/DeWoI9Bm-N3/ |
| 2026-10-12 10:11 | kickhouse_86_on_cloud-x_light-grey.jpg | On Cloud X „Light Grey" | https://www.instagram.com/p/DeYIUENAEX9/ |
| 2026-10-12 14:17 | kickhouse_85_on_cloudvista_sand-black.jpg | On Cloudvista „Sand/Black" | https://www.instagram.com/p/DeYkhw_Ff50/ |
| 2026-10-12 20:19 | kickhouse_84_on_cloudvista_sand-olive-2.jpg | On Cloudvista „Sand/Olive" | https://www.instagram.com/p/DeZN9H3mzle/ |
| 2026-10-13 10:10 | kickhouse_83_on_cloudsurfer-trail_sand-olive.jpg | On Cloudsurfer Trail „Sand/Olive" | https://www.instagram.com/p/DeatByRjQ-7/ |
| 2026-10-13 14:11 | kickhouse_82_on_cloudboom-strike_white-orange-2.jpg | On Cloudboom Strike „White/Orange" | https://www.instagram.com/p/DebInP5lfYT/ |
| 2026-10-15 10:09 | kickhouse_81_on_cloudboom-strike_white-orange.jpg | On Cloudboom Strike „White/Orange" | https://www.instagram.com/p/Def2i6SDSgX/ |
| 2026-10-15 14:10 | kickhouse_80_on_cloudswift_grey.jpg | On Cloudswift „Grey" | https://www.instagram.com/p/DegSGH6FeIt/ |
| 2026-10-15 20:10 | kickhouse_79_on_cloudrunner_white.jpg | On Cloudrunner „White" | https://www.instagram.com/p/Deg7Vv3FdQA/ |
| 2026-10-16 10:10 | kickhouse_78_on_cloudsurfer_cream-3.jpg | On Cloudsurfer „Cream/Grey" | https://www.instagram.com/p/DeibaBOjTE6/ |
| 2026-10-16 14:13 | kickhouse_77_on_cloudsurfer_white.jpg | On Cloudsurfer „White" | https://www.instagram.com/p/Dei3L55FbBE/ |
| 2026-10-16 20:13 | kickhouse_76_on_cloudrunner_grey.jpg | On Cloudrunner „Grey" | https://www.instagram.com/p/DejgdWJIOkH/ |
| 2026-10-17 10:10 | kickhouse_75_on_track-spike_white.jpg | On Track Spike „White" | https://www.instagram.com/p/DelAQrCAHjG/ |
| 2026-10-17 14:10 | kickhouse_74_on_cloudmonster_white-lime.jpg | On Cloudmonster „White/Lime" | https://www.instagram.com/p/DelbqipFRDM/ |
