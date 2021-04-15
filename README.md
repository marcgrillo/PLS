# work

All'interno della cartella PLS troverete le cartelle CODE e DATA:



La cartella DATA ha i seguenti:

1) I file CISIA_AIO2_ingegneria.txt e CISIA_AIO4_scienze.txt che presentano i dati originali forniti dal CISIA

2) Il file dati.tsv estratto dal file Excel del dipartimento ed utilizzato in FILTER

3) I file dati di CISIA ordinati dagli script in CODE e quelli ordinati ridotti (privati dei singoli punteggi per sezione)

4) Il file dizionario.csv che raccoglie in un unico file ordinato tutte le informazioni disponibili per singolo studente

5) La cartella OLD contiene altre forme degli stessi dati utilizzate o estratte in alcuni script di prova





La cartella CODE ha i seguenti:

1) La cartella OLD contenente prime bozze di script per la lettura dei dati

2) 'ingegneria_cisia' contiene lo script che legge i files relativi ai test d'ingresso 'CISIA_AI02_Ingegneria.txt' e scrive i dati in maniera ordinata e leggibile sui files 'dati_ordinati_ridotti_CISIA_AI02_Ingegneria.txt' e 'dati_ordinati_CISIA_AI02_Ingegneria.txt'

3) 'scienze_cisia' contiene lo script che legge i files relativi ai test d'ingresso 'CISIA_AI02_Scienze.txt' e scrive i dati in maniera ordinata e leggibile sui files 'dati_ordinati_ridotti_CISIA_AI02_Scienze.txt' e 'dati_ordinati_CISIA_AI02_Scienze.txt'

4) 'scienze_cisia_read' è uno script dedicato alla lettura dei dati già ordinati e/o ridotti Cisia, funziona sia per ingegneria che per scienza.

5) FILTER contiene lo script motore che legge i dati del dipartimento 'dati.tsv' (estratti da un file excel), li pulisce, li ordina, li riduce e li scrive su un data_dict.
La seconda parte di Reader crea un data_dict finale che unisce i dati appena ridotti ad i dati precedentemente semplificati del CISIA.
Tutti sono scritti in un file "dizionario.csv" che si trova in data

6) Lettore contiene lo script per l'analisi dei dati ordinati letti da dizionario.csv.
Presenta diversi Quicklook e alcuni istogrammi per categoria.
Lo scrit andrebbe ultimato con l'analisi statistica dei dati. (Attendo risposte dal prof. Mannella)



La cartella RESULTS al momento vuota
