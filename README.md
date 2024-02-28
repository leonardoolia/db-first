Esercizio di oggi: **DB First**  
nome repo: `db-first`

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.

Buon lavoro e a domani!

Esercizio:

COLONNA | TIPO | ATTRIBUTO
--- | --- | ---
ID | TINYINT | PRIMARY_KEY, UNIQUE, AUTO_INCREMENT
Marca | VARCHAR(50) | NOTNULL
Km percorsi |  UNSIGNED INT | NOTNULL
Colore | CHAR(2) | NULL
Stato carrozzeria | TINYINT(1) | NOTNULL
Motore | CHAR(1) | NOTNULL    
Cilindrata | UNSIGNED SMALLINT | NOTNULL
Servosterzo | TINYINT/BOOL(1) | NULL DEFAULT(0)
Porte | TINYINT(1) | NOTNULL 

<hr> 

### Legenda: 

Colore:
- RD = Rosso
- LB = Azzurro
- MG = Magenta
- BR = Marrone

Stato carrozzeria:
- 1 = Pessimo
- 2 = Decente
- 3 = Buono
- 4 = Ottimo
- 5 = Eccellente

Motore:

- D = Diesel
- B = Benzina
- E = Elettrico
- G = GPL
- I = Ibrido

