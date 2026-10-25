---
title: "Interview notes — P2 Luca Volpi"
date: 2026-10-25
activity: interview
source: "user interview"
author: "Simona Correale"
channel: video
method: semi-structured interview
tags: [interview, interview-note, grocery-delivery, p2, basket-building, search, ai-assistant, substitutions, order-receiving, delivery-windows, freshness, unattended-delivery]
confidence: high
grade: primary
status: complete
related: [index.md, plan.md, raw/raw-docs/desk/2026-10-10-desk-research-findings.md, raw/raw-docs/interview/2026-10-10-interview-script.md, raw/raw-docs/interview/luca-volpi/2026-10-25-interview-transcript-luca-volpi-p2.md]
---

# Interview notes — P2 Luca Volpi

## Profilo partecipante
- **Nome / ID**: P2 Luca Volpi
- **Nucleo familiare**: 4 persone (lui, la moglie e due figli piccoli).
- **Contesto**: Dipendente UniCredit a Milano, con sconto aziendale su Esselunga. Di solito la spesa online la fa la moglie; l'ultima l'ha fatta lui. Smart working non pianificabile in anticipo.

---

## Abitudini di acquisto e servizi utilizzati
- **Frequenza**: Circa una volta al mese, in modo irregolare; nessuna routine fissa (giorno o carrello ricorrente).
- **Copertura**: Spesa completa online, dalla lunga conservazione ai freschi (frutta e verdura incluse). Nessuna divisione tra cosa comprare online e cosa in negozio.
- **Piattaforme**:
  - **Esselunga online**: servizio usato quasi sempre negli ultimi anni.
  - **Carrefour, Coop** e un terzo servizio che non ricorda: provati in passato, con esperienze negative (freschi meno freschi).
- **Driver di scelta**:
  - Sconto per i dipendenti UniCredit: la sensazione di "perdere qualcosa" se cambiasse servizio.
  - Esselunga percepito come lo standard a Milano, quindi più veloce e più fresco.
  - Risparmio di tempo: con due bambini piccoli non è possibile girare più negozi.

---

## Composizione del carrello (Pain Point Principale)
- **Ricerca**: La ricerca restituisce troppi risultati non pertinenti (cercando "arancia" escono succo e cioccolato all'arancia); bisogna raffinare a mano.
- **Assortimento troppo ampio**: Scorrere "quattro pagine di detersivi" per sceglierne uno è la parte più faticosa.
- **Prodotto non trovato**: Per articoli particolari (es. succo di limone) non capisce se ha sbagliato termine o se il prodotto non esiste.
- **Scelta guidata dalle promozioni**: Poco legato al marchio; sceglie in base all'offerta della settimana. Apprezza gli abbinamenti suggeriti (pasta + sugo pronto).
- **Ordinamento per prezzo al chilo**: All'inizio spiazzante, poi apprezzato come "il vero prezzo".
- **Tempo**: Oltre 20 minuti in un'unica sessione.
- **Carrello ricorrente**: Di fatto nessuno. Esiste un nucleo fisso (pane, latte, acqua, uova) ma non hanno mai salvato un carrello.

---

## Esperimento con assistente AI (Gemini)
- **Input**: Lista della spesa condivisa su Alexa (aggiornata da tutta la famiglia) + menu settimanale per i bambini + volantino promozioni Esselunga (richiesto da Gemini).
- **Output**: Carrello proposto incrociando lista, menu e promozioni; poi rifinitura manuale. Gemini ha anche suggerito come ottimizzare il carrello finale.
- **Valutazione**: Molto positiva; ha ridotto molto la fatica. Prima volta, il sabato precedente all'intervista.

---

## Sostituzioni e problemi di qualità
- **Sostituzioni**: Spesso non si accorge nemmeno di aver ricevuto un prodotto diverso.
- **Problemi reali**: Prodotti mancanti o di bassa qualità (es. banane spaccate).
- **Reclamo**: Molto semplice: foto in app e rimborso immediato. Lo fa per principio anche per importi di un euro.
- **Nessuna categoria esclusa dall'online**: Si definisce "disilluso" rispetto a chi vuole pannolini di marca o la verdura del fruttivendolo.

---

## Scelta dello slot e logistica di consegna
- **Fasce orarie**: Scelte in base agli impegni familiari; sorpreso di trovare libera la fascia 18–20 per il giorno dopo, di solito poco disponibile.
- **Giorno della consegna**: Nessuno in casa; ha risposto al citofono smart dal telefono e la moglie è arrivata in tempo. Consegna al piano, prodotti corretti.
- **Problemi storici**: Nessuno che ricordi.

---

## Prodotti freschi
- **Percezione**: I freschi di Esselunga a Casa sono più freschi di quelli del supermercato (non stanno in esposizione) e migliori di quelli degli altri servizi provati.

---

## Opportunità di miglioramento emerse (Feature & UX)
1. **Consegna senza presenza**: Locker refrigerato o accesso in casa, per non dover garantire giorni prima di essere a casa in una fascia.
2. **Carrelli salvati e pacchetti**: Carrelli standard salvabili o pacchetti tematici (es. colazione con 3–4 prodotti).
3. **Bundle promozionali**: Sconto (es. 30%) se si acquistano più prodotti insieme, in alternativa all'aggiunta di un prodotto alla volta.
4. **Ricerca più precisa**: Risultati pertinenti e chiarezza su quando un prodotto non è disponibile.

## Signals

- Shared pain point, building the basket: P2 names search and choice overload as the hardest part (Q5), where P1 named substitutions. Building the basket was P1's second friction point (app layout, Q21 in `notes/2026-10-10-interview-note-federica-franco-p1.md`).
- Divergence from P1, substitutions: P2 often does not notice a substitute at all and names no protected items. His friction after delivery is missing or damaged items, solved by the in-app claim.
- Shared pain point, delivery windows: both P1 and P2 must commit days ahead to a window. P1 solves it by ordering early; P2 cannot plan his presence at home and asks for unattended delivery.
- Shared observation, freshness: P1 and P2 are both satisfied with Esselunga fresh products. P2 attributes it to stock not being on display, which fits the desk competitor table's claim that Esselunga a Casa controls freshness from a central warehouse.
- New theme: P2 built his basket with a general-purpose AI assistant from a shared household list, a weekly menu and the promotions leaflet. Not covered by the guide or by hypotheses H1 to H4.
- Source: this note derives from the transcript `raw/raw-docs/interview/luca-volpi/2026-10-25-interview-transcript-luca-volpi-p2.md`.

## Interview record

### P2 Luca Volpi — 2026-10-25

**Profile:** P2 Luca Volpi. UniCredit employee in Milan. Shops for a family of four: himself, his wife and two young children. Orders online from Esselunga about once a month, irregularly; his wife usually places the order. Has tried Carrefour and Coop.

**Coverage:** one recording. Questions 12, 14, 15 and 18 were not asked; questions 11 and 13 were asked as one question. Where another answer touches them, this is noted below. Answers describe his last order, placed the Saturday before the interview, and his general habit.

**Last order in brief:** placed by him because his wife had no time. He gave Gemini the family's shared Alexa shopping list and the weekly menu; Gemini asked for the Esselunga promotions leaflet and proposed a basket from all three. He selected the products on the site, adjusted what was wrong, then asked Gemini to optimise the final basket. One session, over 20 minutes. Delivered the next day, 18:00 to 20:00.

**Building the basket**
- Observations:
  - He named search as the hardest part (Q5): results include anything containing the word, and the assortment is so wide that he has to scroll through pages to pick one product.
  - When a specific item does not appear (lemon juice), he cannot tell whether he used the wrong word or the product is not sold.
  - He chooses mostly by the week's promotions and is not attached to brands. Highlighted items and promotions work on him; he finds suggested pairings useful (pasta and ready-made sauce).
  - Esselunga's sort by price per kilo confused him at first; he now sees it as "the real price".
  - The last basket took over 20 minutes in one session.
  - He reviews the basket at the end to remove items added "out of enthusiasm".
  - A core of items is always bought (bread, milk, water, eggs), but he has never saved a basket: his wife is not into tech and he has never taken the time.
  - He buys everything online, fresh produce included, and has no category he keeps for the store.
  - Using Gemini with the shared list, the menu and the leaflet "greatly reduced the fatigue". It was his first try.
- Quotes:
  - "If you search for, say, orange, you get orange juice, orange chocolate, then you have to refine until you find the product you need."
  - "You don't feel like scrolling through four pages of detergents to choose the one you need."
  - "You never understand whether it's you who didn't write the right word or whether the product really isn't there."
  - "I found it particularly interesting as a method because it greatly reduced the fatigue of the thing."
  - "It takes a bit of time, it's not quick."

**Substitutions**
- Observations:
  - When he receives a different product from the one he chose, he often does not notice.
  - What he does notice are missing items and poor-quality items, for example bananas that arrived split open.
  - The claim process is easy: a photo and a complaint in the app, and the amount is credited immediately. He has used it several times, on principle, even for one euro.
  - He names no items he would refuse to have substituted. He contrasts himself with people who insist on branded nappies or greengrocer vegetables.
- Quotes:
  - "In general, if I receive a product different from the one I bought, I often don't even notice."
  - "You just put a photo with a complaint in the app and the amount is credited immediately."
  - "On principle, even if it's only a euro, I asked for the refund."

**Receiving the order**
- Observations:
  - He picks the window around family commitments. He was surprised to find 18:00 to 20:00 free for the next day, as evening windows are usually scarce.
  - On delivery day nobody was home. He answered the smart intercom from his phone, asked the courier to wait, and his wife arrived in time. Delivered to the door, all products correct. One of the first deliveries to their new address.
  - He remembers no delivery problems over the years.
  - He finds Esselunga's fresh products fresher than those on supermarket shelves, and fresher than the other services he tried.
  - His one change is delivery: he cannot be sure days ahead that he will be home in a given window, because his smart-working days change every week.
- Quotes:
  - "The hardest thing I find is being sure that in two days, from four to six, I can stay home waiting for the shopping."
  - "If I had a magic wand I'd want a system that lets them come into the house or leave the shopping even if you're not home. A sort of refrigerated locker."
  - "The products they send you are fresher than the ones you find at the supermarket. Probably because they don't have to sit on display."

**Most painful moment, in the participant's words:** building the basket, navigating search results. "The hardest part is navigating the mare magnum, the huge amount of results the search gives you, and choosing one."

**One thing they would change:** delivery, so the order can be left when nobody is home, for example in a refrigerated locker. In Q22 he added saved baskets, themed packs and multi-product promotional bundles.

**Hypotheses:**
- H1 — no evidence, leans against. Q15 was not asked; unprompted, he names no protected items and says he often does not notice substitutes.
- H2 — no evidence. Q14 was not asked.
- H3 — no evidence. He is not brand-loyal and chooses by promotion, which suggests brand matters little to him, but he was not asked what makes a substitute acceptable.
- H4 — no evidence. Q12 was not asked; he often does not notice substitutions at all.

**Interviewer notes:**
- His friction sits at the two ends: finding products when building the basket, and being home for the window. Substitutions barely register for him; P1 is the opposite.
- The Gemini experiment is the most distinctive finding: an outside assistant combined three sources the service does not connect (household list, meal plan, promotions). One try only.
- Saved baskets exist on the service but he has never used one; the barrier he gives is time and his wife's comfort with tech, not the feature.
- He refers to "Lucia" as if she had spoken before him; possibly a participant in an earlier session. Not clarified.
- "Compro solo Barilla" contradicts "not attached to brands" in the same sentence; probably a transcription error for "non compro solo Barilla". Read that way below.
- Interview date and channel are not stated in the recording. The date here is the day the transcript was filed. The closing "allora andiamo di là" suggests the interview may have been in person.
- Q12 (how and when he finds out) is still open across interviews.

#### P2 — Answers mapped to the guide

Answers are English translations of what the participant said in Italian. Speech-to-text errors in the source are corrected (for example "S Lunga", "Selunga" and "S.Lunga" to Esselunga, "essere lungo a casa" to Esselunga a Casa, "acqua e sapone" to Acqua & Sapone) and the interviewer's side comments are removed. Nothing is added. Passages that could not be understood are marked [unclear]. For the exact original wording, see [interview-transcript-p2.md](../raw/raw-docs/interview/luca-volpi/2026-10-25-interview-transcript-luca-volpi-p2.md).

**Opening.** The interviewer explained there would be about 20 questions on which services he uses, how and for whom. Consent to record is not audible in the recording.

**Q1. Who do you shop for?**
"I shop for myself, my wife and my two children, so for my family of four."

**Q2. How do you do your main grocery shop today? How much of it is online?**
"I'm not very regular in my habits, so I don't have a process like the one Lucia described, the same shop every week on the same day. I'm freer and messier about it, and I don't shop online all the time either; I'd say about once a month, but irregularly. I do quite a complete shop: everything I need, from long-life tins to things that expire very soon, I buy it all. So there's no strategy like buying only certain foods online and others in person. Fresh food too, vegetables, fruit: if I shop online, I buy everything online."

**Q3. Which service do you use, and why that one?**
"I've tried several: Carrefour, Coop, and another one I can't remember now, but I almost always use Esselunga. In recent years always Esselunga, partly because I had bad experiences with the others, partly because I think they positioned themselves very well with us UniCredit employees here in Milan by giving us a discount. In my head, the idea that I have the discount with Esselunga makes me prefer it, because I feel I'd lose something if I went with others. And to be honest, Esselunga in Milan is pretty much the standard: most online shopping is done on Esselunga, so that's probably also why their service is faster and maybe fresher."

**Q4. Tell me about the last time you ordered groceries online.**
"Usually my wife does the shopping, but last time I did it, because she had absolutely no time even to sit at the computer. I did it in a particularly curious way: I wanted to try doing it with Gemini, not Gemini Enterprise because it was outside work [unclear], but I have Gemini for personal use, and I asked it explicitly to do the shopping with me, so I let it guide me. We have a shared shopping list on Alexa, so whoever notices something is missing adds it to Alexa, and we also have a weekly menu, which we don't follow 100%, to give the children a varied distribution of foods. So I gave Gemini the Alexa list and the menu; it asked me for the Esselunga leaflet to see the promotions, crossed the leaflet with the menu and the partial list, and composed a basket. Then it told me to select the products. Of course there was some fine-tuning, because not everything was right, but I found it particularly interesting as a method because it greatly reduced the fatigue. That was the very first time, last Saturday I think.
Generally the process is more traditional: you go on the site, have a look round, search for what's on the list, but the search throws out everything. If you search for orange, you get orange juice, orange chocolate, then you have to refine until you find the product you need."
He added, unprompted: "If you sort by price, on eBay for example the first results are the smallest quantities; a hundred grams of ham costs less than a kilo. Esselunga sorts not by price but by price per kilo, so products that cost more because there's more, but cost less by weight, come first. At first it threw me, then I understood it's the real price, because the cost is relative to the quantity."

**Q5. What was the hardest part of that order?**
"Generally the hardest part is navigating the mare magnum, the huge amount of results the search gives you, and choosing one. Especially in the big supermarkets the assortment is very wide, and you don't feel like scrolling through four pages of detergents to choose the one you need."

**Q6. How did you decide what to put in the basket?**
"When I shop on Esselunga I'm guided a lot by the week's offers. If I know I need fish for the weekend, I look at which fish is on offer; pasta is the same. I'm not very attached to brands, I don't buy only Barilla [source: 'compro solo Barilla', read as 'non compro solo Barilla'], I'm guided by the promotion of the moment. I'm guided by what is highlighted, so promotions definitely work well, online especially. Sometimes the pairings: you're buying pasta and the ready-made tomato sauce comes up. If you can buy the sauce together with it, that can help."

**Q7. How long did it take? Did you do it in one go?**
"This last time I did it all in one session, but it took me more than 20 minutes. It depends on the number of products, of course. It was fun with Gemini, because I also challenged it: I gave it the final basket and asked how it would optimise it, and it gave me advice. Before, you'd usually look through the basket and try to spot the things that stood out, also because sometimes you add things out of enthusiasm and then realise you don't really need them. So yes, it takes time, it's not quick. That's why I understand Lucia, who keeps a saved basket she reuses every week. That would obviously speed things up a lot."

**Q8. How much of the basket is the same every week?**
"Effectively zero. We know there are products we always buy, bread, milk, water, eggs, but we've never saved a basket. You can surely do it on every e-commerce site by now, but we never have, partly because my wife isn't into tech, partly because I've never taken the time."

**Q9. Was there anything you wanted and could not find?**
"Maybe, but I struggle to remember now. Sometimes I look for things like lemon juice, slightly unusual things, and they just don't come up. And you never understand whether it's you who didn't write the right word or whether the product really isn't there."

**Q10. Is there anything you never buy online? Why?**
"No, actually, because we're quite disillusioned. I know many people say they'd never buy Esselunga nappies because their child must have branded ones or they get a rash, or that they'd never buy vegetables at the supermarket because the greengrocer's are something else. But as I said at the start, we try to speed things up, otherwise you'd have to go to lots of supermarkets and places, the market for one thing, Acqua & Sapone for detergents, and it becomes a waste of time. With two small children we can't."

**Q11. Has an item you ordered ever been unavailable? Tell me about the last time.**
Asked together with Q13, as "when you received a product that wasn't the one you selected, how did you handle it?"
"In general, if I receive a product different from the one I bought, I often don't even notice. What has happened, and is interesting, is that either I didn't receive products I had bought, or I received them in poor quality. The last time I bought bananas they were all split, already open."

**Q12. How and when did you find out?**
Not asked. See Q11: he often does not notice a substitute.

**Q13. What did you get instead? What did you do about it?**
"The customer care process was very simple, the customer claim, I don't know what it's called: you just put a photo with a complaint in the app and the amount is credited immediately. It has happened several times, even on things I could have turned a blind eye to, like the split bananas. But on principle, even if it's only a euro, I asked for the refund."

**Q14. Did you tell the service in advance what to do if something was missing? How?**
Not asked.

**Q15. Are there items where you would accept an alternative, and items where you never would? What is the difference?**
Not asked. See Q10: he names no category he keeps away from online.

**Q16. How did you choose the delivery window? Did you get the one you wanted?**
"Obviously I have to take family commitments into account, because the children have commitments and so do we. I was surprised to find six to eight in the evening, because it's usually hard to get. I managed to get it for the next day, from six to eight. So yes, another important factor is finding availability in the window you want."

**Q17. What happened on delivery day?**
"On delivery day I wasn't home and neither was my wife. They rang the intercom and I answered from my phone, because we have a smart intercom. I told them to wait because my wife was on her way, and in the end they crossed paths and managed to deliver. They delivered to the door, as expected. I think it was the first or second time they delivered to our new address. I don't think there were problems: they delivered everything to the door and the products were all correct."

**Q18. What did you check when the order arrived?**
Not asked.

**Q19. How were the fresh products? How does that compare with choosing them yourself?**
"My feeling with Esselunga a Casa is that the products they send you are fresher than the ones you find at the supermarket. Probably because they don't have to sit on display; they can stay in the fridge the whole time. Or maybe because Esselunga knows that if they send people old products, people stop buying online. I feel Esselunga has an interest in keeping fresh quality very good. That's one of the things I meant about the other supermarkets: the others I received shopping from didn't have this attention to fresh food. My feeling is the fresh food was less fresh."

**Q20. Has anything ever gone wrong at delivery? What did you do?**
Asked whether they always delivered to the door: "No, nothing comes to mind."

**Q21. If you could change one thing about ordering groceries online, what would it be?**
"I think it would be delivery. If I had a magic wand I'd want a system that lets them come into the house or leave the shopping even if you're not home, somewhere. A sort of refrigerated locker. The hardest thing I find is being sure that in two days, from four to six, I can stay home waiting for the shopping. Even though we work from home and in theory we could, I can never plan smart working, because every week my family has something different and I have to change my smart-working days. So it's complicated to plan ahead with certainty, because I have to be sure I'll be home. Maybe Wednesday afternoon I'll be home, but maybe not."

**Q22. Is there anything I did not ask that I should have?**
"Maybe the only thing is what we were saying about baskets or packs. You could design standard baskets that everyone can save, or packs: breakfast, with three or four products already inside. Not for your study in particular, but if you wanted to think about alternative ways of shopping online, solutions a bit different from the standard basket where you add one product at a time. Maybe tempting you with a promotion: OK, I'll give you 30% off if you take these three products together."
