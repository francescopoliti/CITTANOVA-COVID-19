
# Andamento dei contagi giornalieri<BR> nel comune di Cittanova, dal 2 novembre 2020 al 13 settembre 2021. # 

## Ubicazione ##

[Cittanova](https://www.cittanovaonline.it/) è un comune calabrese di 9.943 abitanti (dati provvisori Bilancio Demografico ISTAT, 31 luglio 2021), compreso nella Città Metropolitana di Reggio Calabria. 

## Dati ##

Fonte Dati: [Comune di Cittanova](https://www.comune.cittanova.rc.it/)

Elaborazione dati: [ing. Francesco Politi](https://www.cittanovaonline.it/francescopoliti/)

Inizio decorrenza dati: 2 novembre 2020
  
Fine decorrenza dati: 13 settembre 2021

Agente Patogeno: Covid-19

## Struttura dei dati ##

### File `REPORT_GIORNALIERI_COVID-19.csv` ###

Questo file riassume i dati contenuti nei report quotidiani, Emergenza Covid-19, diramati dal Comune di Cittanova, Città Metropolitana di Reggio Calabria.<BR>

Nome del campo | Descrizione | Formato 
-------------- | ----------- | ------- 
Data | Data del report | DD/MM/YYYY 
Positivi Tampone Molecolare | Numero totale dei soggetti che risultano, alla data del report, positivi al tampone molecolare | Numero intero 
Positivi Tampone Antigenico | Numero totale dei soggetti che risultano, alla data del report, positivi al tampone antigenico | Numero intero
Guariti | Numero totale dei soggetti guariti fino alla data del report | Numero intero
Deceduti | Numero totale dei soggetti deceduti fino alla data del report | Numero intero
Attualmente Positivi | Numero totale dei soggetti ancora positivi alla data del report | Numero intero
Totale | Numero totale dei soggetti contagiati dal Covid-19 fino alla data del report | Numero intero

______
Il campo `Attualmente positivi` comprende sia i soggetti che sono risultati positivi al tampone molecolare che quelli risultati positivi al tampone antigenico.
_______

- separatore di campo: `,`
- encoding: `UTF-8`
<BR><BR>

### File `NUOVI_CASI_E_INCIDENZA_SETTIMANALE.csv` ###

Questo file riassume l'indice di incidenza settimanale standardizzato per 100.000 abitanti = (N. totale di casi degli ultimi 7 giorni / Popolazione residente) x 100.000.<BR><BR>
Popolazione residente: 10.028 (popolazione residente al 1° Gennaio 2020, dato ufficiale ISTAT)<BR>

Nome del campo | Descrizione | Formato 
-------------- | ----------- | ------- 
Data | Data del report giornaliero | DD/MM/YYYY 
Nuovi positivi | Numero di nuovi casi registrati quotidianamente | Numero intero
Incidenza Settimanale per 100.000 abitanti | Indice di incidenza settimanale standardizzato | Numero decimale

- separatore di campo: `,`
- encoding: `UTF-8`
<BR><BR>

## Altri files ##

### File `Incidenza_settimanale_Cittanova_variazioni_covid-19.png` ###

Questo file è una immagine raster, con estensione png, che rappresenta l'andamento dell' incidenza settimanale dei nuovi casi Covid-19, standardizzata per 100.000 abitanti = (N. totale di casi degli ultimi 7 giorni / Popolazione residente) x 100.000.

### File `Last_phase_Cittanova_variazioni_covid-19.png` ###

Questo file è una immagine raster, con estensione png, che rappresenta l'andamento del contagio da Covid-19, mediante grafici provvisti di etichette, nell'ultimo periodo.

### File `Nuovi_casi_Cittanova_variazioni_covid-19.png` ###

Questo file è una immagine raster, con estensione png, che rappresenta graficamente l'incremento giornaliero del totale dei positivi, ai tamponi molecolari e antigenici, dal 2 novembre 2020.

### File `Cittanova_variazioni_covid-19-second_wave.png` ###

Questo file è una immagine raster, con estensione png, che rappresenta, mediante grafici provvisti di etichette, il riepilogo complessivo dei dati dal 2 novembre 2020 al 27 dicembre 2020.

### File `Cittanova_variazioni_covid-19-third_wave.png` ###

Questo file è una immagine raster, con estensione png, che rappresenta, mediante grafici provvisti di etichette, il riepilogo complessivo dei dati dal 27 dicembre 2020 al 23 febbraio 2021.

### File `Cittanova_variazioni_covid-19.png` ###

Questo file è una immagine raster, con estensione png, che rappresenta mediante grafici, il riepilogo complessivo dei dati divulgati, dal 2 novembre 2020 fino alla data dell'ultimo report quotidiano pubblicato.
<BR><BR>
_______
<BR>


![Image text](http://www.cittanovaonline.it/repository/logo_covid.png)

<BR><BR>
I dati sono stati elaborati con l'utilizzo di software `Open Source`. Favoriamo lo sviluppo, la diffusione e la tutela del software libero e la diffusione degli ***Open Data***.<BR>
Con il termine Open Data si fa riferimento ad alcuni tipi di dati (informazioni, dati numerici, ecc.) che possono essere liberamente utilizzati, riutilizzati e redistribuiti, secondo le indicazioni presenti nella licenza d’uso.<BR>
<BR>
Se stai visualizzando questo repository su un dispositivo mobile per espandere la lista dei files disponibili fai tap su "View code".
<BR><BR>

## Licenza ##

Il dataset è rilasciato con licenza [CC-BY-ND-4.0](https://creativecommons.org/licenses/by-nd/4.0/deed.it).


Licenza Creative Commons CC BY-ND

La licenza CC BY-ND permette di distribuire l'opera originale senza alcuna modifica, anche a scopi commerciali, a condizione che venga riconosciuta una menzione di paternità adeguata.

![Image text](http://www.cittanovaonline.it/repository/cc_by_nd.png)


### Se usi questi dati

Se usi questi dati, indicalo per favore in qesta modalità:

> <b>Comune di Cittanova, COVID-19</b> - Fonte: <a href='https://github.com/francescopoliti/CITTANOVA-COVID-19' target='_blank'>Contagi Giornalieri - Comune di Cittanova</a> con i dati pubblicati dal Comune di Cittanova

Qui il codice HTML che puoi incollare nel tuo sito/mappa/dashboard:

```html
<b>Comune di Cittanova, COVID-19</b> - Fonte: <a target="_blank" href='https://github.com/francescopoliti/CITTANOVA-COVID-19' target='_blank'>Contagi Giornalieri - Comune di Cittanova</a>
con i dati pubblicati dal Comune di Cittanova.
Licenza <a target="_blank" href="https://creativecommons.org/licenses/by-nd/4.0/deed.it">CC BY ND 4.0</a>
```


