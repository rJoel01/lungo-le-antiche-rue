# Lungo le Antiche Rue

## Descrizione  
L'applicazione, realizzata in collaborazione con la Pro Loco di Civitella Roveto (AQ), è un volantino digitale interattivo che fornisce ai visitatori tutte le informazioni necessarie sull'evento "Lungo le Antiche Rue". È progettata per essere fluida, intuitiva e facile da usare.  

## Linguaggi e Tecnologie Utilizzate  
- **Kotlin**  
- **Jetpack Compose**

## Funzionalità Principali  
✔️ **Mappa Interattiva** → Mostra la posizione delle cantine e dei punti di interesse, con integrazione di Google Maps.  
✔️ **Ricerca e Filtri** → Permette di trovare le cantine per nome, numero o prodotti offerti.  
✔️ **Informazioni Turistiche** → Sezione dedicata alla storia e ai dettagli sui luoghi dell’evento.  
✔️ **Navigazione Intuitiva** → Interfaccia fluida con transizioni animate.  
✔️ **Animazioni Personalizzate** → Grafica realizzata con Shape Shifter e componenti disegnati su Adobe XD.  

## Panoramica dell'App  

<p align="center">
Schermata Home Parte 1<br/>
<img src="https://i.imgur.com/lQ9VMwZ.jpeg" height="80%" width="30%" alt="Schermata App"/>
<br /><br />
Schermata Home Parte 2<br/>
<img src="https://i.imgur.com/shyuqZ6.jpeg" height="80%" width="30%" alt="Schermata App"/>
<br /><br />
Schermata Luoghi Storici<br/>
<img src="https://i.imgur.com/ipyEFaj.jpeg" height="80%" width="30%" alt="Schermata App"/>
<br />
</p>

## Architettura  
L'app è organizzata seguendo un'architettura modulare per garantire una buona separazione delle responsabilità:  

- **Presentation Layer** → Contiene la UI e la gestione dello stato, realizzata con Jetpack Compose e ViewModel.  
- **Semplice Gestione della Logica** → Non è presente un livello Domain separato, poiché la logica è minima e viene gestita direttamente nel ViewModel o nei Composable, a seconda della necessità.  
- **Gestione dei Dati** → I dati utilizzati dall'app sono principalmente statici o ottenuti da fonti esterne senza un livello di repository strutturato.    

## Commento  
L'applicazione è stata progettata dalle fondamenta per essere esteticamente piacevole e gratificante da usare. Le funzionalità principali sono semplici e intuitive, mentre l'integrazione con Google Maps garantisce un'esperienza fluida per trovare le location in tempo reale.  

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
