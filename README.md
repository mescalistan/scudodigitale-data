# Scudo Digitale – dati pubblici

Dati pubblici usati dall'app Android **Scudo Digitale** (protezione anti-truffa).

- `official_phones.json`: numeri ufficiali di assistenza e blocco carte di banche ed enti italiani, presi dai
  loro siti. L'app lo scarica una volta al giorno per riconoscere le truffe telefoniche ("finto operatore"):
  per ogni ente c'è anche `official_display_number`, il numero ufficiale
  suggerito alla persona, e `phone_support: false` per chi non ha assistenza telefonica. Il controllo avviene sul telefono e l'app non invia mai il testo dei messaggi né i numeri ricevuti.
- `privacy-policy.html`: informativa sulla privacy dell'app (pubblicata con GitHub Pages).
- `legal-disclaimer.html`: note legali e limitazione di responsabilità (le stesse mostrate nell'app).

Il file viene validato dall'app: se lo schema non è quello atteso si continua a usare l'ultima copia valida.
