**Vue Slider**
===
Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.

**Bonus:**

1. al click su una thumb, visualizzare in grande l’immagine corrispondente

2. applicare l’autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente

3. quando il mouse va in hover sullo slider, bloccare l’autoplay e farlo riprendere quando esce

4. al doppio click sullo slider cambia la direzione dell’autoplay
## Svolgimento
1. inserisco le immagini in un array.
2. creo un counter.
3. mostro l'immagine attiva in base al contatore.
4. genero tante thumbnails quante sono le immagini.
5. aggiungo la classe active alla thumbnail relativa all'indice attivo.
6. al click di next/prev incremento e decremento il contatore con i relativi controlli (che non superi la lunghezza dell'array e che non sia sotto lo 0).
7. al click della thumb cambio il valore del contatore attivando la nuova immagine.
