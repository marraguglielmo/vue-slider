# Vue Slider

Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.

## **Bonus:**

1. al click su una thumb, visualizzare in grande l’immagine corrispondente
2. applicare l’autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3. quando il mouse va in hover sullo slider, bloccare l’autoplay e farlo riprendere quando esce
4. al doppio click sullo slider cambia la direzione dell’autoplay

### Svolgimento

1. Inserisco l'array di oggetti contenenti le immagini, il titolo e la descrizione
2. inizializzo un contatore
3. rendo attiva l'immagine con indice contatore
4. creo tanti thumb quanto la lunghezza dell'array images
5. assegno la classe `active` alla thumb collegando l'indice al contatore
6. al click dei bottoni next e prev incremento o decremento il contatore
