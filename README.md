# testrigor-tests

Questo repository documenta i test sperimentali eseguiti con TestRigor.

## Che cos'è TestRigor

TestRigor è uno strumento utilizzato per l'automazione dei test di siti web che permette di scrivere i casi d'uso necessari in linguaggio naturale.
TestRigor riesce a eseguire istruzioni semplici come:

> cerca video di gatti.

Ma anche instruzioni più complesse:

> vai su amazon.it e aggiungi al carrello i seguenti prodotti: Sapone per mani, una risma di carta A4 e 2 penne nere.

#### Precisazione

Per garantire il corretto funzionamento dello strumento è consigliato far partire il test dal sito desiderato e non da google per evitare i captcha.

## Obiettivo

L'obiettivo di questo esperimento è stato:
- Comprendere il funzionamento di TestRigor.
- Creare ed eseguire test automatici su un sito di prova.
- Valutare vantaggi, svantaggi ed eventuali limitazioni risetto ad altri strumenti disponibili(Cypress,TestZeus-Hercules,Autify).

## Risultati

- I test vengono eseguiti direttamente nel browser, su macchine di proprietà di TestRigor.
- È possibile esportare i log e i report sia dalla piattaforma che tramite API.
- La versione gratuita funziona bene e permette di eseguire test completi.
