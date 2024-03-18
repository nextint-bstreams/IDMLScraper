ESECUZIONE

1) Sotto "Sorgenti", creare una sottocartella con esattamente lo stesso nome del file .idml (per. es. se il file si chiama "A1_2024_PANORAMA.idml, la cartella dovrà chiamarsi "A1_2024_PANORAMA").

1) Mettere il file .idml (per es. "A1_2024_PANORAMA.idml") dentro la cartella appena creata.

2) da prompt di DOS, lanciare il comando "idmlscraper.exe NOMEPROGETTO" (per es. "idmlscraper.exe A1_2024_PANORAMA")

3) Al termine dell'esecuzione dello script, verranno generati due file nella cartella "Output":
   - NOMEPROGETTO.csv (per es. "A1_2024_PANORAMA.csv") popolato con i dati presenti nel file xml di indesign
   - NOMEPROGETTO_UrlPagina.csv (per es. "A1_2024_PANORAMA_UrlPagina.csv") con le url delle pagine html corrispondenti ad ogni pagina del volantino


settings.cfg
In questo file viene specificato il path dove sono state salvate le pagine HTML.
Il valore iniziale è "/volantino" che significa che le pagine html si trovano sotto le seguenti url relative:
/volantino/2024A25009/A2_2024_PANORAMA-1.html
/volantino/2024A25009/A2_2024_PANORAMA-2.html
.....
