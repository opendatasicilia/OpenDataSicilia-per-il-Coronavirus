# Repository GitHub

In questa sezione vengono segnalati alcuni repository [GitHub](https://github.com/) di enti pubblici e/o associazioni che condividono e rielaborano in opendata i dati #Covid19.

## Covid-19 Opendata Vaccini

Il repository contiene i dati in formato aperto relativi alla consegna e somministrazione nelle varie regioni Italiane dei vaccini anti COVID-19. Il dataset è suddiviso in 8 tabelle che riguardano principalmente i dati sui vaccini rispetto a:


*   consegne suddivise per data di consegna e regione;
*   somministrazioni suddivise per data, regione, fascia d'età, genere e categoria di appartenenza del soggetto vaccinato;
*   punti di somministrazione.
!!! info
    **Maggiori dettagli nel repository [Covid-19 Opendata Vaccini](https://github.com/italia/covid19-opendata-vaccini)**

---

## Presidenza del Consiglio dei Ministri - Dipartimento della Protezione Civile

Repository nato per informare i cittadini e mettere a disposizione i dati raccolti, utili ai soli fini comunicativi e di informazione, il Dipartimento della Protezione Civile ha elaborato un cruscotto geografico interattivo raggiungibile agli indirizzi  [http://arcg.is/C1unv](http://arcg.is/C1unv) (versione desktop) e [http://arcg.is/081a51](http://arcg.is/081a51) (versione mobile) e mette a disposizione, con licenza CC-BY-4.0, le seguenti informazioni aggiornate quotidianamente alle 18:30 (successivamente la conferenza stampa del Capo Dipartimento):

- Dati Andamento nazionale
- Dati json
- Dati regioni
- Dati province
- Schede riepilogative
- Aree
- Note
- Dati contratti DPC forniture
- Metriche
!!! info
     **Maggiori dettagli nel repository [Dati COVID-19 Italia](https://github.com/pcm-dpc/COVID-19)**

--- 

## Associazione onData

L'Associazione onData a condiviso in opendata diversi repository.

### Covid19Italia

Alla data del 4 marzo 2020 - dopo circa 15 giorni dal primo caso "italiano" - **non c'è** in **Italia** una **fonte** ufficiale che pubblichi i dati in modalità ***machine readable***.

Questo *repository* sarà aggiornato una volta al giorno - intorno alle 19:30 - per scaricare dal [sito della Protezione Civile](http://www.protezionecivile.gov.it/attivita-rischi/rischio-sanitario/emergenze/coronavirus/) i 2 file PDF denominati `Dati di riepilogo nazionale (pdf)` e `Dettaglio per provincia (pdf)` e trasformarli in formati leggibili da una "macchina".

I file sono aggiornati dalla Protezione Civile ogni giorno intorno alle 18:00.

Sul numero di deceduti la Protezione Civile riporta che "potrà essere confermato solo dopo che l’Istituto Superiore di Sanità avrà stabilito la causa effettiva del decesso".

!!! info
    **Maggiori dettagli nel repository [Covid19Italia](https://github.com/ondata/covid19italia)**

!!! warning
    **Dopo l'annuncio** del **[*repository ufficiale*](https://github.com/pcm-dpc/COVID-19)** della Protezione Civile con i dati sul COVID-19, abbiamo **bloccato** l'**aggiornamento** automatico dei dati a partire dai PDF pubblicati sul loro sito.**

---

### Vaccini per tutti

Dati aggiornati automaticamente per l'applicazione [ondata/vaccinipertutti](https://github.com/ondata/vaccinipertutti/).

!!! info
    **Maggiori dettagli nel repository ["Vaccini per tutti" by onData - Dati](https://github.com/ondata/vaccinipertutti-data)**
	
---

### Nuts

La **suddivisione territoriale statistica standard** in Europa (EUROSTAT) è la [**NUTS**](https://www.wikiwand.com/it/Nomenclatura_delle_unit%C3%A0_territoriali_statistiche). In Italia è di particolare interesse in alcuni contesti, come ad esempio quello della **sanità**, per il quale il paese è suddiviso funzionalmente non nelle 20 regioni "classiche", ma nelle 21 zone `NUTS2` (il Trentino-Alto Adige suddiviso nelle due province autonome).

Una fonte classica per i file geografici con i limiti amministrativi è [**ISTAT**](https://www.istat.it/it/archivio/222527), che però **non pubblica** ad esempio **file "tagliati" secondo `NUTS2`** (è appunto il livello gerarchico regionale).<br>
Questo *repository* per raccogliere alcuni file geografici suddivisi secondo NUTS (al momento soltanto 2).

Abbiamo chiesto ad ISTAT di pubblicare file geografici anche secondo `NUTS2`: al momento non li pubblicheranno ma ci hanno suggerito una modalità per farlo in autonomia e si sono detti interessati a farlo nel futuro.<br>
È fondamentale per due ragioni:

- le [API ISTAT SDMX](https://www.istat.it/it/metodi-e-strumenti/web-service-sdmx) espongono le informazioni geografiche, secondo NUTS (📚 qui [la nostra guida](https://ondata.github.io/guida-api-istat/)). Attenzione quelli qui esposti sono i codici nella codifica del 2006;
- come detto sopra, in alcuni contesti (sanità, scuola, protezione civile, ecc.) il taglio geografico non è quello regionale "classico", ma coincide proprio con il `NUTS2`.


!!! info
    **Maggiori dettagli nel repository [Nuts](https://github.com/ondata/nuts)**
	
---

### 30cappa

Il [decreto legge numero 172 del 18 dicembre 2020](https://www.gazzettaufficiale.it/eli/id/2020/12/18/20G00196/s)  -  detto in maniera un po' fastidiosa "di Natale"  -  definisce delle misure urgenti per le festività natalizie e di inizio anno nuovo.

In questo si legge:

> nei giorni **28, 29, 30 dicembre 2020** e **4 gennaio 2021** si applicano le misure di cui all'articolo 2 del [medesimo decreto](http://www.governo.it/sites/new.governo.it/files/dpcm_20201203_txt.pdf) del Presidente del Consiglio dei ministri 3 dicembre 2020, ma sono altresì **consentiti** gli **spostamenti** dai **comuni con popolazione non superiore a 5.000 abitanti** e** per una distanza non superiore a 30 chilometri dai relativi confini**, con **esclusione** in ogni caso degli **spostamenti verso i capoluoghi di provincia**.

[aborruso](https://twitter.com/aborruso), [napo](https://twitter.com/napo) e [pigreco](https://twitter.com/totofiandaca), hanno prodotto degli elaborati per avere un quadro del contesto geografico e numerico di questi spostamenti di **30 km** (i 30 "cappa" 😉).

Tutti i dettagli in questo post:
<https://medium.com/tantotanto/il-decreto-di-natale-in-chilometri-8af38744a7d5>

[![](https://raw.githubusercontent.com/ondata/30cappa/main/risorse/buffer05.png)](https://medium.com/tantotanto/il-decreto-di-natale-in-chilometri-8af38744a7d5)





!!! info
    **Maggiori dettagli nel repository [30cappa](https://github.com/ondata/30cappa)**

	