# som-ia.cat

Landing de **Som-IA**: un grup petit de persones que treballen amb
intel·ligència artificial a Catalunya. Crida + mínima informació + misteri.

- **Web**: https://som-ia.cat (estàtica, sense build)
- **Idioma**: català
- **Món visual**: cartell cooperatiu (paper, tinta, vermell)

## Estructura

```
index.html                  # teaser: hero + marquesina + 3 línies + CTA Telegram
assets/css/som-ia.css       # estils vanilla (sense CDN ni JS)
assets/fonts/               # Bricolage Grotesque (OFL, auto-allotjada)
robots.txt
bot/                        # bot de Telegram @somtic_bot (servei systemd)
openspec/                   # specs + changes (OpenSpec)
DEPLOY.md                   # procediment de deploy a host1
```

El contingut extens (serveis, equip, FAQ, formulari) és al git per a fases futures.

## Deploy

Vegeu `DEPLOY.md` (scp a host1, usuari `somtic`, sense reloads).

## Bot de Telegram

Vegeu `bot/README.md`. Servei `somia-bot.service` al Geekom:
benvinguda, antispam, assistent IA i aprovacions d'entrada.
