-----

# 🤝 Linee Guida per i Contributi a SwiftCSS

Siamo entusiasti che tu sia interessato a contribuire a SwiftCSS\! Ogni contributo, grande o piccolo che sia, è prezioso e ci aiuta a migliorare questo framework per tutti.

Prima di iniziare, prenditi un momento per leggere queste linee guida. Seguirle ci aiuterà a gestire al meglio i contributi e a mantenere il progetto coeso e funzionale.

-----

##  Codice di Condotta

Ci aspettiamo che tutti i partecipanti alla community di SwiftCSS aderiscano al nostro codice di condotta. Questo significa creare un ambiente accogliente e rispettoso per tutti. Tratta gli altri con rispetto e sii amichevole.

-----

## Come Contribuire

Ci sono diversi modi per contribuire al progetto:

### 🐞 Segnalare Bug

Se trovi un bug, per favore, segnalacelo\!

1.  **Verifica**: Prima di aprire una nuova issue, controlla le [Issue esistenti su GitHub](https://www.google.com/search?q=https://github.com/SwiftCSS-library/SwiftCSS/issues) per assicurarti che il bug non sia già stato segnalato.
2.  **Crea un'Issue**: Se il bug non è stato segnalato, apri una nuova issue descrivendo il problema in modo chiaro e dettagliato.
      * **Titolo**: Breve e descrittivo (es. `BUG: Il padding 'px-4' non applica il valore corretto su mobile`).
      * **Descrizione**: Spiega cosa ti aspettavi che accadesse e cosa è successo.
      * **Passi per riprodurre**: Fornisci i passaggi esatti per riprodurre il bug. Se possibile, includi un esempio di codice o un link a un ambiente di riproduzione (es. CodePen, JSFiddle).
      * **Ambiente**: Specifica il browser, il sistema operativo e qualsiasi altra informazione rilevante.

### ✨ Proporre Funzionalità o Miglioramenti

Hai un'idea per una nuova utility, un componente o un miglioramento a quelli esistenti? Ci piacerebbe sentirla\!

1.  **Verifica**: Controlla le [Issue esistenti](https://github.com/SwiftCSS-library/SwiftCSS/issues) per vedere se la tua idea è già stata discussa.
2.  **Crea un'Issue**: Apri una nuova issue.
      * **Titolo**: Chiaro e conciso (es. `FEATURE: Aggiungi classi per opacità al hover`).
      * **Descrizione**: Spiega la tua proposta, i benefici che porterebbe e un possibile caso d'uso.

### 💻 Inviare Pull Request (Codice)

Questo è il modo migliore per contribuire direttamente al codice.

1.  **Fai un Fork** del repository `SwiftCSS-library/SwiftCSS` sul tuo account GitHub.
2.  **Clona** il tuo fork in locale: `git clone https://github.com/SwiftCSS-library/SwiftCSS/`
3.  **Crea un nuovo branch** per le tue modifiche. Usa un nome descrittivo (es. `feature/aggiungi-tooltip`, `fix/bug-padding-mobile`):
    `git checkout -b feature/nome-della-tua-feature`
4.  **Apporta le tue modifiche**. Assicurati che il codice sia ben commentato e segua lo stile esistente del progetto.
5.  **Esegui i test** (se presenti) per assicurarti che le tue modifiche non abbiano introdotto regressioni.
6.  **Fai il commit delle tue modifiche** con un messaggio chiaro e conciso. I messaggi di commit dovrebbero descrivere cosa è stato fatto e perché.
      * Esempio: `feat: aggiunge nuove classi per sfumature di testo`
      * Esempio: `fix: corregge il problema di overflow nelle card reattive`
7.  **Effettua il push** del tuo branch sul tuo fork GitHub:
    `git push origin feature/nome-della-tua-feature`
8.  **Apri una Pull Request** (PR) dal tuo branch al branch `main` del repository originale di SwiftCSS.
      * **Titolo della PR**: Deve essere chiaro e riassumere le modifiche.
      * **Descrizione della PR**: Spiega dettagliatamente le modifiche apportate, il problema che risolvono o la funzionalità che aggiungono. Fai riferimento all'issue correlata (es. `Closes #123`).
      * **Screenshot/GIF**: Se applicabile, includi screenshot o GIF per mostrare le modifiche visive.

-----

## Standard di Codifica

  * **CSS**: Utilizza le variabili CSS (`var(--...)`) per colori, spaziature, ecc., come definito in `:root`.
  * **Nomenclatura delle classi**: Mantieni la nomenclatura `s-` per le classi specifiche di SwiftCSS, seguendo il modello utility-first.
  * **Formattazione**: Mantieni la formattazione esistente (indentazione, spaziature).

-----

## Messaggi di Commit

Cerca di rendere i tuoi messaggi di commit il più chiari e leggibili possibile. Ti consigliamo di seguire una convenzione come [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) per i tipi di commit (es. `feat:`, `fix:`, `docs:`, `chore:`).

-----

## Licenza

Contribuendo a SwiftCSS, accetti che il tuo codice sia rilasciato sotto la stessa [licenza MIT](https://github.com/SwiftCSS-library/SwiftCSS/blob/main/LICENSE) del progetto.

-----

## Domande o Supporto

Se hai domande su come contribuire o hai bisogno di aiuto, unisciti alla nostra community su [Discord](https://discord.gg/RYntYyuay7) o apri una [Discussione su GitHub](https://www.google.com/search?q=https://github.com/SwiftCSS-library/SwiftCSS/discussions).

-----
