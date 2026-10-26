# How Might We — domande e concetti

## Quadro d'insieme

Tutti i concetti in una tabella, ordinati per domanda. **[me]** = idee a mano · **[agent]** = concetti proposti dall'agente · **[risky]** = si appoggia su un'ipotesi che le storie non sostengono. I dettagli sono nelle sezioni sotto.

| Domanda | N. | Concetto | Famiglia | Autore | Note |
|---------|----|----------|----------|--------|------|
| **HMW1** · Ritrovare i prodotti già acquistati | 1 | Bundle di prodotti già acquistati in varie composizioni (per esempio "cena rapida") | Memoria della casa | [me] | |
| | 8 | **La mia dispensa** — in ogni ricerca mette in testa i prodotti già comprati dalla famiglia | Memoria della casa | [agent] | |
| | 9 | **La lista che si traduce** — la lista di famiglia diventa un carrello con i prodotti comprati l'ultima volta | Cambiare il punto di partenza | [agent] | |
| **HMW2** · Scegliere senza scorrere pagine | 2 | Sistema di filtri sulla ricerca, con suggerimenti | Restringere il campo | [me] | |
| | 10 | **Scegli per criterio** — la persona dice cosa conta e i risultati si riducono | Restringere il campo | [agent] | |
| | 11 | **Sceglie qualcuno per me** — chi prepara la spesa sceglie secondo un criterio dato | Una persona del servizio decide o risponde | [agent] | [risky] |
| **HMW3** · Capire se il prodotto manca o se la parola è sbagliata | 3 | Tag sui prodotti esauriti | Etichette sul catalogo | [me] | |
| | 4 | Ricerca intelligente con AI che si avvicina al risultato richiesto | Tradurre come si esprime la persona | [me] | |
| | 12 | **Si chiama così** — se la ricerca è vuota, dice come il servizio chiama quella cosa, o che non la vende | Il servizio risponde a ciò che fai | [agent] | |
| | 13 | **Chiedilo al negozio** — la persona chiede al negozio se il prodotto esiste | Una persona del servizio decide o risponde | [agent] | [risky] |
| **HMW4** · Capire quanta frutta e verdura sfusa si ordina | 5 | Possibilità di inserire la quantità | — | [me] | Non classificato |
| | 14 | **In pezzi, non in grammi** — si ordina in pezzi o per uso, il servizio converte in peso | Tradurre come si esprime la persona | [agent] | |
| | 15 | **Il peso tradotto** — ogni quantità torna in forma riconoscibile ("circa 5 mele") | Il servizio risponde a ciò che fai | [agent] | |
| **HMW5** · Sapere quali offerte danno la consegna gratuita | 6 | Elementi in evidenza con tag | Etichette sul catalogo | [me] | |
| | 16 | **Quanto manca** — mentre il carrello cresce, dice quanto manca alla consegna gratuita | Il servizio risponde a ciò che fai | [agent] | |
| | 17 | **Parti dall'offerta** — la spesa grande si costruisce attorno alle offerte con consegna gratuita | Cambiare il punto di partenza | [agent] | |
| **HMW6** · Ricevere la spesa senza dover essere a casa | 7 | Fermopoint con box refrigerati dove tenere la spesa fino a 24 ore | La spesa arriva altrove o a qualcun altro | [me] | |
| | 18 | **La fascia si decide il giorno stesso** — l'ora di consegna si conferma il giorno stesso | Spostare il tempo | [agent] | |
| | 19 | **Qualcuno ritira per me** — un vicino o un'altra persona riceve la spesa | La spesa arriva altrove o a qualcun altro | [agent] | [risky] |

## Domande e idee a mano

| ID | Come potremmo… | Idee a mano |
|----|----------------|-------------|
| HMW1 | …aiutare gli utenti a ritrovare facilmente i prodotti già acquistati, distinguendoli dai risultati che corrispondono soltanto al termine di ricerca? | Bundle di prodotti già acquistati in varie composizioni (per esempio "cena rapida"). |
| HMW2 | …aiutare gli utenti a scegliere un prodotto senza dover scorrere pagine di risultati? | Sistema di filtri sulla ricerca, con suggerimenti. |
| HMW3 | …aiutare gli utenti a capire se un prodotto che non trovano manca davvero o se l'hanno cercato con la parola sbagliata? | Tag sui prodotti esauriti. · Ricerca intelligente con AI che si avvicina al risultato richiesto. |
| HMW4 | …aiutare gli utenti a capire quanta frutta e verdura sfusa stanno ordinando? | Possibilità di inserire la quantità. |
| HMW5 | …aiutare gli utenti a sapere, mentre fanno una spesa grande, quali offerte danno loro la consegna gratuita? | Elementi in evidenza con tag. |
| HMW6 | …aiutare gli utenti a ricevere la spesa anche quando non possono garantire di essere a casa? | Fermopoint con box refrigerati dove tenere la spesa fino a 24 ore. |

## Concetti — allargare il campo

Due concetti per domanda, in direzioni diverse da quelle delle idee a mano. Nessun ordine di preferenza. **[risky]** = si appoggia su un'ipotesi che le storie non sostengono.

| ID | HMW | Concetto | Cosa fa | Direzione | Rischio |
|----|-----|----------|---------|-----------|---------|
| C1 | HMW1 | La mia dispensa | Per ogni ricerca mette in testa, separati, i prodotti che la famiglia ha già comprato. | Memoria della casa | — |
| C2 | HMW1 | La lista che si traduce | Trasforma la lista della spesa di famiglia in un carrello con, per ogni voce, il prodotto comprato l'ultima volta. | Partire da altro che la ricerca | — |
| C3 | HMW2 | Scegli per criterio | La persona dice una volta cosa conta per lei (prezzo al chilo, marca, formato) e i risultati si riducono a quelli che lo rispettano. | Le parole della persona | — |
| C4 | HMW2 | Sceglie qualcuno per me | Chi prepara la spesa sceglie il prodotto secondo un criterio dato dalla persona, che non vede la lista. | Delegare al servizio | **[risky]** P1 non accetta che altri scelgano per lei i prodotti a cui tiene. |
| C5 | HMW3 | Si chiama così | Quando la ricerca non trova nulla, dice con quali nomi il servizio vende quella cosa, o che non la vende. | Trasparenza del servizio | — |
| C6 | HMW3 | Chiedilo al negozio | La persona chiede al negozio se un prodotto non trovato esiste, e riceve la risposta prima della consegna. | Delegare al servizio | **[risky]** Nessuna nota mostra che vorrebbero aspettare una risposta. |
| C7 | HMW4 | In pezzi, non in grammi | Frutta e verdura sfusa si ordinano in pezzi o per uso ("mele per quattro merende") e il servizio converte in peso. | Le parole della persona | — |
| C8 | HMW4 | Il peso tradotto | Ogni quantità inserita viene restituita in una forma riconoscibile ("circa 5 mele"). | Trasparenza del servizio | — |
| C9 | HMW5 | Quanto manca | Mentre il carrello cresce, dice quanto manca alla consegna gratuita e quali offerte la farebbero scattare. | Trasparenza del servizio | — |
| C10 | HMW5 | Parti dall'offerta | La spesa grande comincia dalle offerte che danno la consegna gratuita, e il carrello si costruisce attorno a loro. | Partire da altro che la ricerca | — |
| C11 | HMW6 | La fascia si decide il giorno stesso | La persona conferma l'ora di consegna il giorno stesso, quando sa dove sarà, invece che giorni prima. | Spostare il tempo | — |
| C12 | HMW6 | Qualcuno ritira per me | Un vicino, il portiere o un'altra persona scelta riceve la spesa al posto suo. | Rete di persone e luoghi | **[risky]** Le note non dicono nulla di vicini, portineria o persone di fiducia. |

## Direzioni

| Direzione | Cosa la definisce | Concetti |
|-----------|-------------------|----------|
| Memoria della casa | Il servizio usa quello che la famiglia ha già comprato. | C1 |
| Partire da altro che la ricerca | L'ordine comincia da una lista, da un'offerta, da qualcosa che la persona ha già. | C2, C10 |
| Le parole della persona | La persona chiede le cose come le pensa (criteri, pezzi, usi) e il servizio traduce. | C3, C7 |
| Delegare al servizio | Una persona del servizio sceglie o risponde al posto dell'utente. | C4, C6 |
| Trasparenza del servizio | Il servizio dice chiaramente cosa ha, come lo chiama, quanto manca. | C5, C8, C9 |
| Spostare il tempo | Una decisione si sposta più vicino al momento in cui la persona sa cosa le serve. | C11 |
| Rete di persone e luoghi | La spesa passa per altre persone o luoghi vicini alla persona. | C12 |

## Concetti scartati

| HMW | Concetto | Perché non risponde |
|-----|----------|---------------------|
| HMW1 | Spesa in abbonamento | Ripete i prodotti abituali ma non aiuta a distinguerli nei risultati di ricerca. |
| HMW2 | Recensioni degli altri clienti | Aggiunge informazioni a ogni risultato invece di ridurre quelli da scorrere. |
| HMW3 | Ricerca vocale | Cambia il modo di cercare, ma non dice se il prodotto manca o se la parola è sbagliata. |
| HMW5 | Consegna gratuita per abbonati | Toglie il costo di consegna ma non fa sapere quali offerte lo tolgono. |
| HMW6 | Locker refrigerato | Risponde alla domanda, ma è già tra le idee a mano (fermopoint con box refrigerati): non allarga il campo. |

## Elenco unito

Tutti i concetti delle tabelle sopra, numerati. Autore: **[me]** = idee a mano, **[agent]** = concetti C1–C12. Nessun concetto attivo compare in entrambe le liste, quindi nessuno è **[both]**. I concetti scartati non sono nell'elenco.

| N. | HMW | Concetto | Autore |
|----|-----|----------|--------|
| 1 | HMW1 | Bundle di prodotti già acquistati in varie composizioni (per esempio "cena rapida") | [me] |
| 2 | HMW2 | Sistema di filtri sulla ricerca, con suggerimenti | [me] |
| 3 | HMW3 | Tag sui prodotti esauriti | [me] |
| 4 | HMW3 | Ricerca intelligente con AI che si avvicina al risultato richiesto | [me] |
| 5 | HMW4 | Possibilità di inserire la quantità | [me] |
| 6 | HMW5 | Elementi in evidenza con tag | [me] |
| 7 | HMW6 | Fermopoint con box refrigerati dove tenere la spesa fino a 24 ore | [me] |
| 8 | HMW1 | C1 La mia dispensa | [agent] |
| 9 | HMW1 | C2 La lista che si traduce | [agent] |
| 10 | HMW2 | C3 Scegli per criterio | [agent] |
| 11 | HMW2 | C4 Sceglie qualcuno per me [risky] | [agent] |
| 12 | HMW3 | C5 Si chiama così | [agent] |
| 13 | HMW3 | C6 Chiedilo al negozio [risky] | [agent] |
| 14 | HMW4 | C7 In pezzi, non in grammi | [agent] |
| 15 | HMW4 | C8 Il peso tradotto | [agent] |
| 16 | HMW5 | C9 Quanto manca | [agent] |
| 17 | HMW5 | C10 Parti dall'offerta | [agent] |
| 18 | HMW6 | C11 La fascia si decide il giorno stesso | [agent] |
| 19 | HMW6 | C12 Qualcuno ritira per me [risky] | [agent] |

## Famiglie

Raggruppate per il modo in cui rispondono alla domanda. Nessun ordine di preferenza.

| family | its direction, one line | concepts (by number) | authors |
|--------|-------------------------|----------------------|---------|
| Memoria della casa | Il servizio riparte da ciò che la famiglia ha già comprato. | 1, 8 | [me] 1 · [agent] 8 |
| Restringere il campo | I risultati si riducono a quelli che rispettano un criterio. | 2, 10 | [me] 2 · [agent] 10 |
| Tradurre come si esprime la persona | La persona dice le cose a modo suo e il servizio le interpreta. | 4, 14 | [me] 4 · [agent] 14 |
| Etichette sul catalogo | Il servizio segna sui prodotti uno stato o un'occasione (esaurito, in offerta). | 3, 6 | [me] 3, 6 |
| Il servizio risponde a ciò che fai | Il servizio spiega l'esito di un'azione appena fatta: una ricerca vuota, una quantità, il carrello che cresce. | 12, 15, 16 | [agent] 12, 15, 16 |
| Cambiare il punto di partenza | L'ordine non comincia dalla ricerca ma da una lista o da un'offerta. | 9, 17 | [agent] 9, 17 |
| Una persona del servizio decide o risponde | Un umano del servizio sceglie o risponde al posto dell'utente. | 11, 13 | [agent] 11, 13 |
| Spostare il tempo | Una decisione si prende più tardi, quando la persona sa cosa le serve. | 18 | [agent] 18 |
| La spesa arriva altrove o a qualcun altro | La consegna non dipende dalla presenza della persona a casa: va in un luogo o a un'altra persona. | 7, 19 | [me] 7 · [agent] 19 |

### Non classificati

| N. | Concetto | Perché |
|----|----------|--------|
| 5 | Possibilità di inserire la quantità [me] | Così com'è scritto descrive ciò che l'app fa già, ed è il momento di cui P1 si lamenta (Q21). Non dice in che modo cambierebbe l'inserimento, quindi non si capisce in quale direzione risponde. |

### Famiglie di una sola mano

- **Solo [me]:** Etichette sul catalogo (3, 6).
- **Solo [agent]:** Il servizio risponde a ciò che fai (12, 15, 16) · Cambiare il punto di partenza (9, 17) · Una persona del servizio decide o risponde (11, 13) · Spostare il tempo (18).
- **Entrambi:** Memoria della casa, Restringere il campo, Tradurre come si esprime la persona, La spesa arriva altrove o a qualcun altro.

### Conteggio

- **Concetti in:** 19 (7 [me], 12 [agent], 0 [both]).
- **Famiglie:** 9.
- **Non classificati:** 1.
