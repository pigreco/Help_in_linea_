## Interfaccia calcolatore di campi ![calc](https://docs.qgis.org/testing/en/_images/mActionCalculateField.png)

![interfaccia](/img/calcolatore_campi.png)

1. se attivato aggiorna solo le geometrie selezionate;
2. se attivato crea un campo virtuale;
3. se attivato aggiorna il campo esistente selezionato al punto 7;
4. digitare nome del campo (per shapefile NON più di 10 caratteri);
5. selezionare il tipo di campo di uscita;
6. digitare lunghezza campo di uscita (es: per integer digitare 9);
7. se attivato (il punto 3 è attivo), compararirà un menu a tendina con i campi della tabella attributi più la <*geometry*>;
8. operatori più usati( uguale, somma, differenza,divisione, moltiplicazione, potenza, unione stringhe, parentesi, nuova riga);
9. area dove digitare e comporre le espressioni (con la possibilità di inserire commenti es: `$area -- area` oppure `/* testo */`);
10. casella di ricerca funzioni;
11. elenco ad albero con tutte le funzioni suddivise per argomento;
12. Help in linea;
13. anteprima valore espressione digitata in 9 oppure segnalazione errore;
14. visualizza i valori univoci del campo selezionato.

## Commenti per documentare espressione

<p align="center">
  <img width="600" src="../img/finestra_field_calc/commenti.png">
</p>

## Interfaccia calcolatore di campi e finestre nascoste

Nel caso risulti nascosta la sezione Gruppi funzioni:

<p align="center">
  <img width="600" src="../img/finestra_field_calc/hfcqgis_gruppi.gif">
</p>

Nel caso risulti nascosta la sezione help in linea:

<p align="center">
  <img width="600" src="../img/finestra_field_calc/hfcqgis_Help.gif">
</p>