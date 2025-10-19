# 🎓 Crypto Course Complete - Programma e Guida alla Progressione

---



## 📋 Matrice di Dipendenza (Leggere così: devi completare TUTTE le righe per accedere al modulo)

| Modulo | Prerequisiti Obbligatori |
|--------|--------------------------|
| **M0: Exchange** | M1 |
| **M1: Bitcoin & Wallet** | ✅ ENTRY POINT |
| **M2: Ethereum & Smart Contract** | M0 + M1 |
| **M3: Scaling & L2** | M2 |
| **M4: Altcoin & Portfolio** | M1 |
| **M5: DAO & Governance** | M2 |
| **M6: Anti-Fraud** | M1 |
| **M7: Geopolitica** | *(consigliato M1 + M2)* |
| **M8: DeFi Avanzata** | M1 + M2 + M3 + M4 |
| **M9: Privacy Protocols** | M1 |
| **M10: Intelligence On-Chain** | M1 + M2 + M6 + M9 |
| **M11: Legal & Compliance** | M0 + M1 + M2 + M6 + (M10) |

---
````mermaid
graph TD
    START["START<br/>Inizia qui"]
    
    M1["M1: Bitcoin & Wallet<br/>✅ ENTRY POINT<br/>Prerequisiti: NESSUNO"]
    
    M0["M0: Exchange<br/>Prerequisiti: M1"]
    M4["M4: Altcoin & Portfolio<br/>Prerequisiti: M1"]
    M6["M6: Anti-Fraud<br/>Prerequisiti: M1"]
    M9["M9: Privacy Protocols<br/>Prerequisiti: M1"]
    
    M2["M2: Ethereum & Smart Contract<br/>Prerequisiti: M0 + M1"]
    
    M3["M3: Scaling & L2<br/>Prerequisiti: M2"]
    M5["M5: DAO & Governance<br/>Prerequisiti: M2"]
    
    M8["M8: DeFi Avanzata<br/>Prerequisiti: M1 + M2 + M3 + M4"]
    M10["M10: Intelligence On-Chain<br/>Prerequisiti: M1 + M2 + M6 + M9"]
    
    M11["M11: Legal & Compliance<br/>Prerequisiti: M0 + M1 + M2 + M6 + Consigliato M10"]
    
    M7["M7: Geopolitica<br/>Prerequisiti: nessuno obbligatorio<br/>Consigliato: M1 + M2"]
    
    START --> M1
    
    M1 --> M0
    M1 --> M4
    M1 --> M6
    M1 --> M9
    
    M0 --> M2
    M1 --> M2
    
    M2 --> M3
    M2 --> M5
    M2 --> M10
    
    M1 --> M8
    M2 --> M8
    M3 --> M8
    M4 --> M8
    
    M1 --> M10
    M6 --> M10
    M9 --> M10
    
    M0 --> M11
    M1 --> M11
    M2 --> M11
    M6 --> M11
    M10 --> M11
    
    M1 -.->|consigliato| M7
    M2 -.->|consigliato| M7
````
## 🎯 Percorsi Consigliati per Profilo

### 🔴 Hodler Conservatore (4 moduli - ~4-6 settimane)
**Obiettivo:** Comprare, custodire e proteggere i tuoi Bitcoin

```
M1 → M0 → M6 → M11
```

---

### 🟠 DeFi Expert (8 moduli - ~10-12 settimane)
**Obiettivo:** Padronanza totale della finanza decentralizzata

```
M1 → M0 → M2 → M6 → M3 → M4 → M8 → M11
```

---

### 🟡 Security Researcher (8 moduli - ~10-12 settimane)
**Obiettivo:** Analisi di sicurezza, tracciamento fondi, investigazione

```
M1 → M0 → M2 → M6 → M9 → M10 → M11
```

---

### 🟢 DAO Contributor (6 moduli - ~7-9 settimane)
**Obiettivo:** Partecipazione attiva in governance decentralizzata

```
M1 → M0 → M2 → M5 → M4 → M6 → M11
```

---

### 🔵 Privacy Advocate (7 moduli - ~9-11 settimane)
**Obiettivo:** Protezione della privacy, anonimità, elusione di sorveglianza

```
M1 → M0 → M2 → M6 → M9 → M10 → M11
```

---

### ⚫ Full Stack Expert (Completo - 12 moduli - ~14-18 settimane)
**Obiettivo:** Competenza totale nel crypto ecosystem

```
M1 → M0 → M2 → M3 → M4 → M5 → M6 → M7 → M8 → M9 → M10 → M11
```

---

# 📚 PROGRAMMA COMPLETO DEI MODULI

---

## Modulo 0 - Exchange

Questo modulo fornisce le basi operative per chi vuole iniziare a muoversi nel mondo delle criptovalute tramite exchange. Si esploreranno i concetti fondamentali come l'orderbook, le commissioni di trading e le differenze tra exchange centralizzati e decentralizzati. Verranno illustrate le modalità pratiche per acquistare criptovalute, sia passando dagli exchange tradizionali sia utilizzando metodi alternativi, e si discuteranno le strategie per gestire in sicurezza più conti contemporaneamente. L'obiettivo è dare agli studenti gli strumenti per entrare nel mercato in modo consapevole, riducendo rischi e costi operativi.

**Domande Chiave:**
- Cos'è un orderbook?
- Come compro cryptovalute?
- Come conosco le commissioni?
- Come mai è meglio averne più di uno?
- Come compro crypto senza passare da un Exchange?

---

## Modulo 1 – Bitcoin e Wallet

Questo modulo introduce i fondamenti di Bitcoin, la prima criptovaluta al mondo, e i concetti chiave legati alla gestione dei wallet. Si esploreranno la struttura della blockchain, la sicurezza offerta dalle chiavi crittografiche e i meccanismi che garantiscono l'immutabilità e la proprietà degli asset digitali. Sarà l'occasione per comprendere le differenze tra wallet custodial e non-custodial, la logica delle transazioni tramite UTXO, e gli strumenti avanzati come il Lightning Network per rendere le transazioni rapide e scalabili.

**Domande Chiave:**
- Come mai la blockchain di Bitcoin è immutabile?
- Cos'è la Proof of Work e cosa rende possibile?
- Come vengono distribuiti i nuovi Bitcoin? C'è un limite?
- Qual è la differenza tra un wallet custodial e uno non-custodial?
- Cos'è una chiave privata e perché rappresenta il vero possesso di un asset digitale?
- Quali sono i rischi di non custodire correttamente un seed?
- Possono altre persone vedere cosa faccio on-chain? In che modo?
- Cos'è un ordine stop loss / take profit e come può diventare un'arma a doppio taglio?
- Cos'è la leva, come funziona e in che modo si può ottenere?
- Come può la leva rovinare totalmente l'investimento?
- Cos'è un UTXO e che ruolo ha nella logica delle transazioni Bitcoin?
- Cos'è una Fork e come può avvenire?
- Cos'è il lighting network?

---

## Modulo 2 – Ethereum e Smart Contract

In questo modulo ci si concentra su Ethereum, la piattaforma leader per smart contract e applicazioni decentralizzate (dApp). Verranno spiegati i concetti di Proof of Stake, emissione di nuovi ETH, e la natura autonoma degli smart contract. Saranno approfonditi i token standard (ERC20, NFT), le stablecoin e il funzionamento degli strumenti della finanza decentralizzata, insieme ai rischi sistemici e alle metodologie per ispezionare e interagire con contratti intelligenti in sicurezza.

**Domande Chiave:**
- Cos'è la Proof of Stake e cosa rende possibile?
- Come vengono distribuiti i nuovi Ethereum? C'è un limite?
- Cos'è uno smart contract e cosa lo distingue da un normale programma?
- Cosa sono i "primitivi" della finanza decentralizzata (ERC20, DEX, Money Market) e cosa consentono di fare?
- Cos'è una stablecoin? Quali tipologie esistono e quali rischi comportano (collateralizzata, algoritmica, ibrida)?
- Cos'è una proof of reserve?
- Come capisci quando il tuo portafoglio presenta rischi sistemici?
- Gli smart contract possono essere controllati da amministratori o entità centrali? In che modo?
- Posso ispezionare uno smart contract? Come visualizzo le funzioni e le variabili pubbliche?
- Cos'è il liquid staking e come funziona un yield-bearing asset?
- Cos'è un NFT e quali sono i suoi utilizzi concreti (narrow LP, collezionabile, ticket, access key, asset unici)?
- Cos'è un Multi signature wallet, per cosa lo si usa?
- Come funziona tecnicamente un AMM (Automated Market Maker) e la formula $x \cdot y = k$?
- Cos'è l'Impermanent Loss e chi colpisce?
- Qual è la differenza tra gli standard token NFT ERC-721 e ERC-1155?
- Cosa sono i metadati di un NFT e perché è importante sapere dove sono salvati (es. on-chain vs IPFS vs server privato)?
- Cos'è una dApp (Applicazione Decentralizzata) e come si interagisce (connettere wallet, firmare, approvare)?
- Cosa sono gli On-Ramp e Off-Ramp?
- Qual è la differenza tra un CEX (Centralized Exchange) e un DEX (Decentralized Exchange) in termini di rischi e benefici per l'utente?
- Cos'è lo slippage?

---

## Modulo 3 - Scaling and Information retrival solutions

Il terzo modulo affronta le soluzioni di scalabilità e di gestione dei dati per blockchain ad alta intensità di transazioni. Si analizzeranno Layer 2, sidechain, rollup, oracoli e bridge, confrontando architetture monolitiche e modulari. L'obiettivo è comprendere come migliorare la velocità, ridurre i costi e mantenere sicurezza e decentralizzazione, oltre a capire l'importanza degli audit per valutare l'affidabilità di una dApp.

**Domande Chiave:**
- Cosa sono i Layer 2 (L2) e perché esistono?
- Qual è la differenza tra Optimistic Rollup e ZK-Rollup?
- Cosa sono le Sidechain (es. Polygon PoS)?
- Cosa sono gli Oracoli (es. Chainlink) e perché sono fondamentali per la DeFi?
- Cosa sono i Bridge (Ponti) e quali rischi di sicurezza comportano?
- Qual è la differenza tra un'architettura blockchain "Monolitica" (es. Solana) e una "Modulare" (es. Ethereum + L2)?
- Cos'è un audit di una dapp? è solo un audit del codice o c'è di più?

---

## Modulo 4 – Altcoin Integration e Portfolio Management

Questo modulo introduce la gestione di portafogli contenenti criptovalute alternative (altcoin). Si parlerà di analisi del rischio, performance relative rispetto a Bitcoin, differenze tra token e criptovalute, e principi di tokenomics. L'attenzione sarà posta sul modo di valutare l'apprezzamento storico delle altcoin e come costruire un portafoglio equilibrato e informato.

**Domande Chiave:**
- Quando capisco che il mio portafoglio ha un rischio troppo alto?
- Come misuro le performance delle monete alternative rispetto a Bitcoin?
- Qual è la differenza tra Token e Cryptocurrency?
- Cos'è la tokenomia e come si studia per un singolo token/cryptocurrency?
- Storicamente quanto è stato l'apprezzamento delle altcoin (facendo media) rispetto a bitcoin?

---

## Modulo 5 - DAO e governance

Qui si esplora il mondo delle Decentralized Autonomous Organization (DAO), organizzazioni governate tramite smart contract. Verrà spiegato come proporre e votare proposte, delegare potere di voto e monitorare l'impatto delle decisioni. Il modulo fornisce strumenti pratici per partecipare attivamente alla governance di ecosistemi decentralizzati.

**Domande Chiave:**
- Cos'è una dao e come funziona?
- Come ispeziono i voti di una proposta?
- Come propongo una proposta?
- Come voto per una proposta?
- Come posso delegare il mio potere di voto?
- Come controllo l'impatto dei voti?

---

## Modulo 6 - Proteggersi dai tipi di truffe

Il sesto modulo si concentra sulla sicurezza e la prevenzione delle frodi nel mondo crypto. Si analizzeranno i segnali di piattaforme fraudolente, le tecniche più comuni di truffa (romance scam, crypto drainer, malware wallet, phishing) e le precauzioni pratiche per proteggere fondi e dati. Sarà approfondito anche il fenomeno delle influencer-memecoins e dei rischi legati alla speculazione.

**Domande Chiave:**
- Come distinguo una piattaforma fraudolenta?
- Quali strumenti posso utilizzare per stare in un ambiente sicuro?
- Cos'è un PigButchering/romance scam?
- Cos'è un crypto drainer e come solitamente viene utilizzato?
- Cos'è un malware wallet? Come lo evito?
- Cos'è un seed phishing popup? Come lo evito?
- Cosa sono le influencer-memecoins?
- Cosa significa quando hai uno sweaper sul wallet? cosa si può fare?

---

## Modulo 7 - Geopolitica

Questo modulo esplora l'interazione tra criptovalute, la ricapitalizzazione dell'energia in eccesso, mercati predittivi e dinamiche geopolitiche. Si analizzerà come strumenti come Polymarket possano creare incentivi a far accadere eventi improbabili, influenzando le decisioni di politici o persone esposte pubblicamente. Verranno esaminati anche l'impatto di Bitcoin sull'economia globale in funzione della curva di adozione, il ruolo delle CBDC nella centralizzazione del controllo economico e le conseguenze macroeconomiche della tokenizzazione del debito sovrano.

**Domande Chiave:**
- In che modo si può ricapitalizzare energia in eccesso?
- In che modo Bitcoin impatta sul sistema economico mondiale a seconda della posizione nella curva di adozione?
- In che modo Polymarket altera il risultato della scommessa stessa? E che impatto può avere sui politici o persone visibilmente esposte.
- In che modo una CBDC può essere utilizzata per centralizzare il controllo economico a livello nazionale?
- Quali sono le conseguenze geopolitiche della tokenizzazione degli asset del debito sovrano?
- Qual è il legame tra inflazione globale, debito pubblico e la domanda di asset digitali scarsi come Bitcoin?
- Cosa accade agli equilibri macroeconomici se Bitcoin diventa un collaterale sistemico nel mercato dei derivati?
- Come cambia la natura del potere quando il "dato" è pubblico ma l'interpretazione è monopolizzata da chi possiede i migliori algoritmi di analisi?

---

## Modulo 8 - Defi avanzata

Qui si approfondiscono le strategie e i rischi della finanza decentralizzata (DeFi) avanzata. Si parlerà di MEV bot, flashloan, frontrun, sandwitch attack e arbitraggio on-chain, analizzando l'interazione tra smart contract, liquidità e nodi. L'obiettivo è capire come sfruttare opportunità complesse e prevenire perdite dovute a operazioni non schermate o attacchi sofisticati.

**Domande Chiave:**
- Cos'è un Mev bot e quali strumenti hai per leggere la logica delle loro transazioni?
- Cos'è un flashloan, quali sono i rischi?
- Cos'è un frontrun attack e come evito di caderne vittima?
- Cos'è un Flashloan attack?
- Cos'è un sandwitch attack?
- Cosa significa Just in time liquidity?
- Cos'è l'arbitraggio istantaneo onchain? qual è l'esempio più semplice?
- cos'è un bot di liquidazioni sui money market? Che tipo di programma ha bisogno offchain?
- Cos'è la node latency come può impattare strategie MEV complesse?

---

## Modulo 9 - Privacy Protocols

Il nono modulo esplora i protocolli per la privacy in blockchain. Si analizzeranno tecnologie come Zero-Knowledge Proof, nodi privati, privacy coins e mixer, spiegando come proteggere identità e fondi. Sarà mostrato come le transazioni possono rivelare informazioni a chi le osserva e quali strumenti sono disponibili per anonimizzare flussi di criptovalute.

**Domande Chiave:**
- Bitcoin è propriamente fungibile?
- Cos'è la Zero-knowledge proof? Mi dimostri con un esempio come funziona?
- A cosa servono i private nodes? Da cosa ti proteggono?
- Cosa sono le privacy coins?
- In che modo il nodo scelto per propagare la transazione sulla rete può raccogliere informazioni sulla tua transazione?
- Cos'è un Mixer? Quali sono le euristiche principali per determinare la destinazione e/o l'origine dei fondi?
- Cos'è una transazione di coinjoin?

---

## Modulo 10 - Intelligence onchain

Questo modulo introduce tecniche avanzate di tracciamento e analisi on-chain, comprese le strategie di demixing per separare flussi aggregati di fondi. Si parlerà di strumenti di tracing, correlazione tempo/quantità, identificazione di bridge e smart contract malevoli, attribuzione di indirizzi e verifica di blacklist. L'obiettivo è sviluppare capacità investigative per comprendere origini, destinazioni e rischi dei flussi di criptovalute, con particolare attenzione ai comportamenti complessi dei fondi on-chain.

**Domande Chiave:**
- Cos'è un tracing tool?
- Cosa significa e a cosa serve la time/amount correlation?
- Come seguo l'origine/destinazione di alcuni fondi?
- Come decifro la destinazione di un bridge
- Come decifro il comportamento di un malicious contract?
- Come determino quando un indirizzo è di un ervizio?
- In che modo posso provare a dare un attribuzione ai servizi?
- Come controllo se un indirizzo è stato blacklistato a un amministratore di un ERC20?
- Come determino la transazione outbound da una peelchain i bitcoin?
- Cosa vuol dire clustering? e a cosa serve?

---

## Modulo 11 - Legal obbligations e perquisizione

L'ultimo modulo affronta il quadro normativo legato alle criptovalute. Verranno analizzati obblighi legali per exchange e servizi, funzioni di blacklist in ERC20, collaborazione cross-giurisdizione, differenze di proprietà e fungibilità, nonché KYC/AML e Travel Rule. Si metterà in evidenza come la regolamentazione europea (MiCA) e statunitense (SEC) influiscono sulla privacy, sicurezza e operatività degli utenti.

**Domande Chiave:**
- Quali entità hanno legal obbligations nel caso ricevesse fondi rubati?
- Cosa significa quando un ERC20 ha una funzione di blacklist?
- In quali modi è possibile farli collaborare in cross giuristizioni?
- qual'è la differenza legale tra proprietà unica e fungible che c'è in alcune giurisdizioni?
- Cosa si intende per KYC (Know Your Customer) e AML (Anti-Money Laundering) e perché sono richiesti dagli exchange?
- Qual è la differenza di approccio alla regolamentazione tra l'Europa (MiCA) e gli Stati Uniti (SEC)?
- Cos'è il "Travel Rule" e come impatta la privacy delle transazioni tra exchange?
- Cosa succede alle crypto sequestrate?

---

## ⏱️ Timeline Consigliata per Profilo

| Profilo | Durata Totale | Ritmo | Moduli/Settimana |
|---------|--------------|-------|-----------------|
| Hodler Conservatore | 4-6 settimane | Rilassato | 1-2 |
| DAO Contributor | 7-9 settimane | Moderato | 1-2 |
| DeFi Expert | 8-10 settimane | Moderato | 1-2 |
| Privacy Advocate | 9-11 settimane | Moderato | 1 |
| Security Researcher | 10-12 settimane | Intenso | 1 |
| Full Stack Expert | 14-18 settimane | Intenso | 1 |
