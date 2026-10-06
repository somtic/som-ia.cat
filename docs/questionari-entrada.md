# Som-IA — Qüestionari d'entrada

> Document viu de l'equip Som-IA. Última revisió: octubre 2026.

Quan algú demana entrar al grup de Telegram de Som-IA.cat, el bot `@somtic_bot`
li fa unes quantes preguntes per **missatge privat**. Serveix per presentar-se
sense fricció i perquè l'equip tingui context abans d'aprovar l'entrada. **No cal
escriure res**: totes les respostes es fan tocant botons.

Aquest document recull les preguntes i opcions actuals, perquè qualsevol pugui
proposar-ne millores.

## Com funciona

- S'inicia amb `/start` al privat del bot.
- Cada pregunta d'una sola opció **avança sola** en tocar-la.
- L'última pregunta és de **multi-selecció**: es marquen/desmarquen opcions i es
  tanca amb «Enviar ✅».
- El bot desa les respostes juntament amb l'`@usuari` de Telegram i avisa els
  administradors. Si el qüestionari està complet, l'entrada s'aprova
  automàticament.

## Preguntes

### 1. Com has arribat a Som-IA.cat?

Una opció.

- Xarxes socials
- Cercant a Google
- Un conegut o membre
- Una xerrada o esdeveniment
- Altres

### 2. Què t'ha interessat de Som-IA.cat?

Una opció.

- L'equip consultor
- El programari lliure
- Projectes amb el tercer sector
- Aprendre i fer xarxa
- Altres

### 3. Quin és el teu àmbit principal amb la IA?

Una opció.

- Desenvolupament
- Dades o models (ML)
- Producte o disseny
- Infraestructura o DevOps
- Estratègia o consultoria
- Docència o divulgació
- Altres

### 4. Què fas amb IA?

Una opció.

- A la feina o professionalment
- Projectes personals
- Estudis o recerca
- Encara no hi faig res
- Altres

### 5. Quin nivell hi tens?

Una opció.

- Hi estic començant
- Hi treballo sovint
- En sóc expert/a

### 6. Vols col·laborar en projectes?

Una opció.

- Sí, activament
- Segons el projecte
- De moment, només aprendre

### 7. Quines eines o tecnologies domines?

Multi-selecció (es pot triar més d'una).

- Python
- JavaScript o TypeScript
- Frontend o web
- Backend o APIs
- Dades o SQL
- ML o models (PyTorch...)
- Prompting o apps LLM
- Infra, Docker o DevOps
- Disseny o UX
- Altres

## Com proposar millores

- Obre una **issue** al repositori (o un PR) explicant el canvi: una pregunta
  nova, opcions diferents, reordenar-les, etc.
- La definició que fa servir el bot viu a `bot/config.yaml`
  (`onboarding.questions`), fora d'aquest repositori públic. Mantenim aquest
  document sincronitzat amb allò que pregunta el bot.
- Criteris de disseny: preguntes curtes, en català, respostables amb un toc i que
  ajudin a conèixer la persona sense fer-la sentir interrogada.
