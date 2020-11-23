## Valutazione comparativa tecnica ed economica #

### Guida alla compilazione
***
Versione: 1.0


### Indice

1. Considerazioni generali
2. Prodotti selezionati
3. Requisiti funzionali e non
4. Criteri
> - Interoperabilità
> - Protezione dati personali
> - Sicurezza
> - Accessibilità
> - Manutentore
> - Supporto
> - Dipendenze
> - Competenze PA
> - Numero PA
> - Vitalità
5. TCO
6. Comparazione
7. TOPSISCalc


### 1. Considerazioni generali

Questo documento intende fornire una guida alla compilazione del foglio di calcolo “Valutazione comparativa tecnico-economica”, utile per svolgere una valutazione comparativa tecnica ed economica di software a riuso o open source.

Il foglio di calcolo è predisposto per la valutazione comparativa di tre software, genericamente indicati con “Software A”, “Software B” e “Software C” (è possibile comparare più di tre software aggiungendo opportunamente delle colonne). Ogni tab del foglio di calcolo è relativo a un criterio di valutazione. Ogni software riceverà un punteggio quantitativo per ogni criterio di valutazione, a seconda di come siano stati compilati i tab dei criteri. Una volta che saranno stati compilati i criteri di valutazione, nel tab “Comparazione” appariranno, per ogni software, i punteggi dei criteri di valutazione. In questo tab, una volta inseriti i pesi (#) per ognuno dei criteri di valutazione, apparirà la classifica dei software, risultato della valutazione comparativa tecnica ed economica.

Si noti che i criteri che presentano un asterisco “*” vanno compilati obbligatoriamente, in quanto corrispondono ai requisiti imposti dalla normativa vigente.

Nelle sezioni seguenti, verrà fornita una guida alla compilazione di ogni tab del foglio di calcolo. 

(#) I pesi dei criteri sono contenuti in apposito foglio di calcolo allegato “SPCL4-AgID-CCROS-Pesi criteri di valutazione 0.1”.

I Pesi sono assegnati in base a Macro-Categorie di software, individuate nel tab “Legenda”. Nel tab “Categorie e Pesi” le Categorie di Software sono elencate, partendo per omogeneità da quelle ad oggi presenti su Developers.italia.it, e indicandone la Macro-Categoria di appartenenza.

Al fine di raffinare l’adeguatezza delle Categorie e delle Macro-Categorie alla rappresentazione delle Soluzioni in Riuso Open Source per la Pubblica Amministrazione, si attiverà apposito Gruppo di Studio. Ovviamente qualsiasi suggerimento, nota, considerazione, critica è ben accetta, anzi, richiesta.

### 2. Prodotti selezionati

Tabella 1<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab01.png" alt="Tabella 01">

Per ognuno dei Prodotto selezionati, fornire le informazioni.

Il nome del Prodotto sarà riproposto in tutte le pagine successive.

### 3. Requisiti funzionali e non

Tabella 2<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab02.png" alt="Tabella 02">

Per ogni requisito funzionale e non funzionale, indicare il peso del requisito e la percentuale con cui ogni software copre il requisito. Per far ciò, in riferimento alla figura sopra riportata, compilare le righe 5, 6, 7,9, 10, 11 (colonna C per i pesi, colonne E, F e G per il grado di copertura).

I requisiti funzionali possono essere evidentemente raggruppati in modalità espositiva consona con la struttura funzionale della soluzione.

Note:
- È importante l’attribuzione corretta dei pesi, da ricondurre ad una rappresentazione percentuale
- Si suggerisce di effettuare la valutazione, suddividendo con precisione i requisiti tra “Obbligatori” e “Opzionali”. **È lasciato alla Pubblica Amministrazione valutante decidere la percentuale di copertura dei requisiti al di sotto della quale è inutile proseguire nella valutazione del Software**.
- Per i requisiti “Obbligatori” si suggerisce di verificare preliminarmente se è plausibile accettare che alcuni requisiti non siano completamente soddisfatti e lo diventino solo se il divario tra requisiti presenti e requisiti mancanti si può/vuole coprire con interventi di adeguamento ad hoc. In questo caso, si suggerisce di accertarsi che i Requisiti Obbligatori che abbiano maggior peso specifico siano coperti al 100%, accettando la non completa copertura per Requisiti a minor peso specifico.
- Nel caso la mancanza di un requisito “Obbligatorio” escluda la possibilità di scegliere la soluzione (e avendone ovviamente verificato il soddisfacimento), è ragionevole pensare di utilizzare questo foglio di calcolo anche per i requisiti “Opzionali”, al fine comunque di darne una completa valutazione.

### 4. Criteri

Questa pagina contiene i criteri di valutazione. Sono in sequenza e per ognuno di essi saranno a seguire indicate le modalità di composizione.

#### 4.1 Interoperabilità

Tabella 3<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab03.png" alt="Tabella 3">

Per ognuno dei criteri e per ognuno dei software , rispondere “si” (senza accento) oppure “no”.

I link rimandano ai documenti (e relative Sezioni) in cui è possibile verificare il soddisfacimento del criterio. Per esempio, i protocolli per l’interoperabilità cui si fa riferimento sono SOAP e REST (Sezioni 2.3 e 2.4 del Modello di Interoperabilità della Pubblica Amministrazione).

I criteri che presentano l’asterisco vanno obbligatoriamente compilati, a meno che la soluzione che si deve valutare non gestisce/produce il criterio.

#### 4.2 Protezione dati personali

Per ognuno dei criteri e per ognuno dei software, rispondere “si” (senza accento) oppure “no”.

Si noti che la compilazione di ogni criterio di questo tab è obbligatoria, a meno che la soluzione che si deve valutare non gestisca/produca il criterio.

Tabella 4<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab04.png" alt="Tabella 4">

#### 4.3 Sicurezza

Tabella 5<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab05.png" alt="Tabella 5">

Per ognuno dei criteri e per ognuno dei software, rispondere “si” (senza accento) oppure “no”.

Si noti che la compilazione di ogni criterio di questo tab è obbligatoria.

I link rimandano ai documenti (e Sezioni) in cui è possibile verificare il soddisfacimento del criterio.

#### 4.4 Accessibilità

Tabella 6<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab06.png" alt="Tabella 6">

Per ogni software, rispondere alla checklist selezionando una sola risposta per software. Si noti che la compilazione di questo tab è obbligatoria.

#### 4.5 Manutentore

Tabella 7<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab07.png" alt="Tabella 7">

Per ogni software, rispondere alla checklist selezionando una sola risposta per software.

#### 4.6 Supporto

Tabella 8<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab08.png" alt="Tabella 8">

Per ognuno dei criteri e per ognuno dei software , rispondere “si” (senza accento) oppure “no”.

In caso il software non necessiti di soggetti in grado di fornire supporto, si valorizza l’apposta riga con “nonec”. Si noti, che inconsiderazione dell’importanza di questa caratteristica, gli viene assegnato il peso “3”.

#### 4.7 Dipendenze

Tabella 9<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab09.png" alt="Tabella 9">

Per ciascun software, inserire il numero di dipendenze con altro software (proprietario o open source).

##### 4.8 Competenze PA

Tabella 10<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab10.png" alt="Tabella 10">

Per ogni software, rispondere alla checklist selezionando una sola risposta per software.

#### 4.9 Numero PA

Tabella 11<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab11.png" alt="Tabella 11">

Per ogni software, inserire il numero di PA che utilizzano il software e il numero di PA che sono interessate all’acquisizione del software.

##### 4.10 Vitalità

Tabella 12<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab12.png" alt="Tabella 12">

Per ogni software, inserire il valore di ognuno dei criteri della vitalità (tali valori sono reperibili per esempio nella pagina principale del software su Github). Non modificare i pesi indicati nella colonna B.

### 5 TCO

Tabella 13<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab13.png" alt="Tabella 13">

Per ogni software, fornire una stima delle voci di costo. Il TCO è da compilare obbligatoriamente per l’articolo 68 comma 1 bis del CAD. Non è tuttavia necessario fornire una stima di tutte le voci di costo.

Si noti inoltre che, per alcune voci di costo, vi sono delle sotto-voci la cui compilazione è anch’essa facoltativa. Tali sotto-voci appariranno cliccando sui simboli “+” presenti sulla sinistra. Se si decide di compilare le sotto-voci di una determinata voce di costo, tale voce di costo non va compilata: assumerà come valore la somma delle sue sotto-voci.

È possibile inoltre specificare una durata della soluzione e il numero di PA che dividono i costi del TCO, se tali valori sono diversi da quelli attualmente suggeriti nel foglio di calcolo.

### 6 Comparazione

Tabella 14<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab14.png" alt="Tabella 14">

Inserire i pesi per ogni criterio di valutazione in riga 2. Tali pesi vanno copiati dal foglio di calcolo “Pesi criteri di valutazione”. Utilizzare quelli corrispondenti alla categoria del software che si sta valutando.

Non inserire i punteggi dei criteri di valutazione: questi ultimi appariranno automaticamente non appena saranno stati compilati i tab precedenti.

Una volta inseriti i pesi, apparirà in basso la classifica dei software che si stanno comparando, risultato finale della valutazione comparativa tecnico-economica.

### 7 TOPSISCalc

In questo tab è implementato l’algoritmo di decisione multi-criteri TOPSIS, che produce la classifica dei software in base ai punteggi e ai pesi dei criteri di valutazione. Non è necessaria alcuna azione in questo tab.

Tabella 15<br><img src="https://github.com/AgID/ccros-valcomp/blob/lab/images/Tab15.png" alt="Tabella 15">
