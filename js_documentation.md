# Documentación de Archivos JavaScript

## Archivo: `chatBot.js`

### Funciones encontradas:
- `function appendMessage`
  - Parámetros: sender, text, className
  - Código:
  ```js
// Crea un nuevo elemento div para el mensaje
    const messageElement = document.createElement("div");
    messageElement.classList.add(className); // Añade una clase CSS para el estilo del mensaje
    messageElement.innerHTML = `<strong>${sender
  ```

## Archivo: `script.js`

_No se encontraron funciones en este archivo._

## Archivo: `scriptAuvasa.js`

### Funciones encontradas:
- `function initMap`
  - Parámetros: 
  - Código:
  ```js
const defaultLocation = { lat: 41.6572, lng: -4.73
  ```

- `function obtenerCoordenadas`
  - Parámetros: direccion
  - Código:
  ```js
const direccionCompleta = `${direccion
  ```

- `function buscarRuta`
  - Parámetros: origenCoords, destino
  - Código:
  ```js
const destinoCoords = await obtenerCoordenadas(destino);
  if (!destinoCoords) {
    document.getElementById("resultado").innerHTML = "Destino no encontrado.";
    return;
  ```

- `function mostrarRutaTexto`
  - Parámetros: result
  - Código:
  ```js
const steps = result.routes[0].legs[0].steps;
  let routeDescription = "";

  // Usamos for...of para esperar a que cada dirección se obtenga antes de continuar
  for (let step of steps) {
    if (step.travel_mode === "WALKING") {
      // Usamos geocodificación inversa para obtener la dirección
      const direccionDestino = await obtenerDireccion(step.end_location);
      // Eliminar el código postal y "España" si está presente
      const direccionSimplificada = direccionDestino
        .replace(/, \d{5
  ```

- `function obtenerDireccion`
  - Parámetros: coordinates
  - Código:
  ```js
const apiKey = "AIzaSyCD8yk8cj22G_KJfes6iC_G2U6zTmXQWjY"; // Tu API Key
  const lat = coordinates.lat();
  const lng = coordinates.lng();
  const url = `https://maps.googleapis.com/maps/api/geocode/json?latlng=${lat
  ```

- `function mostrarError`
  - Parámetros: error
  - Código:
  ```js
const errores = {
    1: "Permiso denegado",
    2: "Posición no disponible",
    3: "Tiempo de espera agotado",
  ```

## Archivo: `scriptForms.js`

### Funciones encontradas:
- `function togglePassword`
  - Parámetros: 
  - Código:
  ```js
const passwordField = document.getElementById('password');
    const toggleIcon = document.getElementById('toggleEye');
    
    // Alternar el tipo de input entre 'password' y 'text'
    if (passwordField.type === 'password') {
        passwordField.type = 'text';
        toggleIcon.classList.remove('bi-eye');
        toggleIcon.classList.add('bi-eye-slash');
  ```

## Archivo: `scriptRincon.js`

### Funciones encontradas:
- `function shuffle`
  - Parámetros: array
  - Código:
  ```js
for (let i = array.length - 1; i > 0; i--) {
      const j = Math.floor(Math.random() * (i + 1));
      [array[i], array[j]] = [array[j], array[i]]; // Intercambiar
  ```

- `function flipCard`
  - Parámetros: 
  - Código:
  ```js
if (lockBoard) return;
    const card = this;

    if (card === firstCard) return;
    card.classList.add("flip");

    if (!firstCard) {
      firstCard = card;
      return;
  ```

- `function checkForMatch`
  - Parámetros: 
  - Código:
  ```js
if (firstCard.dataset.content === secondCard.dataset.content) {
      disableCards();
      matchedCards++; // Incrementar contador de cartas emparejadas
      // Si todas las cartas han sido emparejadas
      if (matchedCards === totalCards / 2) {
        endGame(); // Finalizar el juego
  ```

- `function disableCards`
  - Parámetros: 
  - Código:
  ```js
firstCard.removeEventListener("click", flipCard);
    secondCard.removeEventListener("click", flipCard);
    resetBoard();
  ```

- `function unflipCards`
  - Parámetros: 
  - Código:
  ```js
setTimeout(() => {
      firstCard.classList.remove("flip");
      secondCard.classList.remove("flip");
      resetBoard();
  ```

- `function resetBoard`
  - Parámetros: 
  - Código:
  ```js
[firstCard, secondCard, lockBoard] = [null, null, false];
  ```

- `function endGame`
  - Parámetros: 
  - Código:
  ```js
restartButton.style.display = "block"; // Mostrar el botón de reinicio
  ```

- `function restartGame`
  - Parámetros: 
  - Código:
  ```js
// Resetear las cartas
    const allCards = document.querySelectorAll(".memory-card");
    allCards.forEach((card) => {
      card.classList.remove("flip"); // Voltear todas las cartas
      card.addEventListener("click", flipCard); // Volver a habilitar el clic
  ```

- `function mostrarFormulario`
  - Parámetros: 
  - Código:
  ```js
const formulario = document.getElementById("formulario-recordatorio");
  formulario.style.display =
    formulario.style.display === "none" ? "block" : "none";
  ```

## Archivo: `scriptSalud.js`

### Funciones encontradas:
- `function submitSymptoms`
  - Parámetros: 
  - Código:
  ```js
const selectedSymptom = $("#symptoms").val();
  if (!selectedSymptom) {
    $("#result").html('<p class="text-danger">Seleccione un síntoma.</p>');
    return;
  ```

## Archivo: `scriptSms.js`

_No se encontraron funciones en este archivo._

