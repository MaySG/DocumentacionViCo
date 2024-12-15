# Documentación de Archivos CSS

## Archivo: `styles.css`

### Clases encontradas:
- `.corporativAzul`:
```css
color: #42c7ff;
```

- `.corporativRosa`:
```css
color: #ff7762;
```

- `.fondoPrincipal`:
```css
background-attachment: fixed;
    background-image: url(../images/fondoPrincipal.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
```

- `.fondoForms`:
```css
background-attachment: fixed;
    background-image: url(../images/fondoForms.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
```

- `.fondoAbstracto`:
```css
background-attachment: fixed;
    background-image: url(../images/Abstracto.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
```

- `.fondoDni`:
```css
background-attachment: fixed;
    background-image: url(../images/cielo.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
```

- `.fondo`:
```css
background-color: transparent;
    height: 100vh;
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
```

- `.fondoSalud`:
```css
background-attachment: fixed;
    background-image: url(../images/saludFondo.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
```

- `.logo-text-container`:
```css
display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 50%;
    padding: 40px;
    border: 5px solid transparent;
    border-radius: 25px;
    box-shadow: 0 0 30px rgba(0, 0, 0, 0.2);
    animation: borderAnimate 5s linear infinite;
    background-color: transparent;
    text-align: center;
    opacity: 0;
    transform: scale(0.9);
    transition: opacity 2s ease-in-out, transform 2s ease-in-out;
```

- `.logo-text-container`:
```css
margin-top: 300px !important;
```

- `.logo`:
```css
width: 90%;
    height: auto;
    border-radius: 10px;
    transition: opacity 2s ease-in-out, transform 2s ease-in-out;
```

- `.slogan`:
```css
font-family: 'Caveat', sans-serif;
    margin-top: 20px;
    text-align: center;
    color: #012e4f;
    text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
    font-size: 4rem;
```

- `.bold`:
```css
font-weight: bold;
    font-family: 'Caveat', sans-serif;
    color: #ff7762;
```

- `.icono-card`:
```css
font-size: 200px;
    color: #42c7ff;
    -webkit-text-stroke: 2px #ff7762;
    text-shadow: 2px 2px 0px #ff7762;
    margin-bottom: 15px;
    transition: transform 0.3s ease, color 0.3s ease, -webkit-text-stroke 0.3s ease, text-shadow 0.3s ease;
```

- `.icono-card`:
```css
transform: scale(1.2);
    color: #ff7762;
    -webkit-text-stroke: 2px #42c7ff;
    text-shadow: 2px 2px 0px #42c7ff;
```

- `.card`:
```css
padding: 20px;
    background-color: rgba(248, 248, 255, 0.8);
    box-shadow: 0 4px 8px rgba(13, 110, 253, 0.5);
    border-radius: 8px;
```

- `.card-body`:
```css
display: flex;
    flex-direction: column;
```

- `.card-link`:
```css
text-decoration: none;
    color: inherit;
```

- `.card-text`:
```css
font-family: 'Caveat', sans-serif;
    font-size: 2.5rem;
    color: #2C2C2C;
```

- `.logo-text-container`:
```css
width: 70%;
```

- `.slogan`:
```css
font-size: 2rem;
```

- `.tooltip`:
```css
position: absolute;
    max-width: 350px;
    font-size: 1.5rem;
    padding: 20px;
    background-color: rgba(0, 0, 0, 0.85);
    color: white;
    border-radius: 10px;
    text-align: center;
    z-index: 9999;
    top: 100%; 
    left: 50%;
    transform: translateX(-50%);
```

- `.semitransparente`:
```css
background-color: rgba(255, 255, 255, 0.8);
    /* Fondo blanco semitransparente */
    color: #2C2C2C;
    border: 1px solid #ccc;
```

- `.form-label`:
```css
color: #2C2C2C;
    font-weight: bold;
    font-size: 1.5rem;
    font-family: 'Raleway', 'Roboto', serif;
```

- `.bordeInferior`:
```css
padding-bottom: 20px;
    border-bottom: 2px #ff7762 solid;
```

- `.card-text`:
```css
font-size: 1.5rem;
    font-weight: bold;
    color: #333;
    margin-bottom: 20px;
```

- `.centrar-card`:
```css
display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    /* Altura completa de la ventana */
    width: 100%;
    /* Ancho completo */
```

- `.card-centrada`:
```css
max-width: 500px;
    /* Ancho máximo deseado de la card */
    width: 100%;
    /* Asegurarse de que ocupe el ancho total permitido */
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    background-color: white;
    text-align: center;
```

- `.btn-custom`:
```css
background-color: #42c7ff;
    border-color: #ff7762;
    color: white;
    font-family: 'Caveat', cursive;
    font-size: 1.5rem;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease, border-color 0.3s ease;
```

- `.nav-link`:
```css
font-size: 1.25rem;
    padding: 12px 24px;
    color: #333;
    font-weight: bold;
    border: 2px solid #ddd;
    border-radius: 8px;
    margin-right: 5px;
    background-color: #f8f9fa;
    transition: background-color 0.3s ease;
```

- `.active`:
```css
color: #fff;
    background-color: #42c7ff;
    border-color: #ff7762;
```

## Archivo: `stylesAuvasa.css`

### Clases encontradas:
- `.container`:
```css
max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
```

- `.input-group`:
```css
margin-top: 5px;
    margin-bottom: 15px;
```

- `.resultado`:
```css
margin-top: 20px;
    padding: 10px;
    background-color: white;
    border: 1px solid #ccc;
    border-radius: 4px;
```

- `.map`:
```css
height: 400px;
    margin-top: 20px;
    border: 1px solid #ccc;
    border-radius: 4px;
```

- `.card_movilidad`:
```css
display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 100%; 
    height: 400px; 
    border: 1px solid #ccc;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    margin: 10px;
```

- `.card-img-top_movilidad`:
```css
width: 100%;
    height: 200px; 
    object-fit: cover;
```

- `.card-body_movilidad`:
```css
padding: 10px;
    text-align: center;
```

- `.card-title_movilidad`:
```css
font-size: 2rem;
    margin-bottom: 10px;
    color: #012e4f;
```

- `.card-text_movilidad`:
```css
font-size: 1.5rem;
    color: #555;
```

### IDs encontrados:
- `#resultado`:
```css
display: none;
```

## Archivo: `stylesChatBot.css`

### Clases encontradas:
- `.chat-header`:
```css
background-color: #007bff;
    color: white;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
```

- `.chat-body`:
```css
flex: 1;
    padding: 10px;
    overflow-y: auto;
    background-color: #f1f1f1;
```

- `.user-message`:
```css
background-color: #007bff;
    color: white;
    padding: 8px;
    border-radius: 10px;
    margin: 5px 0;
    align-self: flex-end;
    max-width: 80%;
```

- `.bot-message`:
```css
background-color: #e5e5e5;
    color: black;
    padding: 8px;
    border-radius: 10px;
    margin: 5px 0;
    align-self: flex-start;
    max-width: 80%;
```

- `.chat-input-container`:
```css
display: flex;
    padding: 10px;
    border-top: 1px solid #ddd;
    background-color: #ffffff;
```

### IDs encontrados:
- `#chat-bubble-icon`:
```css
width: 80px;
    height: 80px;
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-image: url('../images/sticker.png');
    background-size: cover;
    background-position: center;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
```

- `#chat-greeting`:
```css
position: fixed;
    bottom: 110px;
    right: 20px;
    width: 250px;
    background-color: #007bff;
    color: white;
    padding: 10px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: 2500;
```

- `#chat-bubble`:
```css
position: fixed;
    bottom: 110px;
    right: 20px;
    width: 300px;
    height: 400px;
    border-radius: 15px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    display: none;
    flex-direction: column;
    background-color: #ffffff;
    z-index: 2500;
```

- `#close-chat`:
```css
font-size: 18px;
    cursor: pointer;
    color: white;
    transition: color 0.2s;
```

- `#chat-input`:
```css
flex: 1;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 8px;
    margin-right: 10px;
    font-size: 14px;
```

- `#send-btn`:
```css
background-color: #007bff;
    color: white;
    border: none;
    padding: 8px 15px;
    font-size: 14px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.2s;
```

- `#chat-greeting`:
```css
display: none;
```

- `#chat-bubble`:
```css
display: none;
```

- `#chat-bubble-icon`:
```css
display: block;
```

- `#chat-bubble`:
```css
z-index: 9999 !important;
```

## Archivo: `stylesEntretenimiento.css`

### Clases encontradas:
- `.fondoAbstracto`:
```css
background-attachment: fixed;
    background-image: url(../images/Abstracto.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100%;
```

- `.card-custom`:
```css
transition: transform 0.3s;
    overflow: hidden;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 250px;
```

- `.card-body`:
```css
background-color: #42c7ff;
    color: #fff;
```

- `.card-text`:
```css
font-family: 'Raleway', 'Roboto', serif;
    font-size: 2.5rem;
    color: #2C2C2C;
```

- `.container-slider`:
```css
display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    margin-top: 20px;
```

- `.caption`:
```css
font-size: 30px;
    color: #555;
    margin-top: 10px;
```

- `.container-slider`:
```css
display: none;
```


## Archivo: `stylesFooter.css`

### Clases encontradas:
- `.footer-logo`:
```css
display: flex;
    align-items: center;
```

- `.footer-text`:
```css
text-align: right;
    font-size: 14px;
```

- `.footer-links`:
```css
text-align: center;
    flex: 1;
```

- `.footer-links`:
```css
margin-top: 10px;
```

- `.footer-text`:
```css
margin-top: 10px;
        text-align: center;
```

## Archivo: `stylesGestion2.css`

### Clases encontradas:
- `.seccionCabecera`:
```css
font-family: 'Arial', sans-serif; /* Cambié la fuente a Arial */
    font-size: 2.5rem;
    color: #0d6efd;
    text-align: center;
    margin-bottom: 1.5rem;
```

- `.seccionParrafo`:
```css
font-family: 'Georgia', serif; /* Cambié la fuente a Georgia */
    font-size: 1.2rem;
```

- `.btn-custom`:
```css
background-color: #42c7ff;
    border-color: #ff7762;
    color: white;
    font-family: 'Caveat', cursive;
    font-size: 1.5rem;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease, border-color 0.3s ease;
```

- `.video-container`:
```css
position: relative;
    padding-bottom: 56.25%; /* Relación de aspecto 16:9 (315 / 560 = 0.5625) */
    height: 0;
    overflow: hidden;
    max-width: 100%;
    background: #000;
```

## Archivo: `stylesRincon.css`

### Clases encontradas:
- `.recordatorio-card`:
```css
background-color: #fffbcc;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0px 0px 5px rgba(0, 0, 0, 0.3);
    margin-top: 10px;
    width: 100%;
    max-width: 600px;
    margin-bottom: 20px;
```

- `.recordatorio-item`:
```css
padding: 10px 0;
    border-bottom: 1px dashed #ddd;
    display: flex;
    justify-content: space-between;
    align-items: center;
```

- `.fecha`:
```css
font-size: 12px;
    color: gray;
```

- `.btn-guardar`:
```css
background-color: #ff7762;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 16px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    width: 100%;
    text-align: center;
```

- `.btn-eliminar`:
```css
background: transparent;
    border: none;
    color: red;
    cursor: pointer;
    font-size: 20px;
    transition: color 0.3s ease;
```

- `.corporativRosa`:
```css
color: #ff7762;
```

- `.row`:
```css
margin-bottom: 20px;
```

- `.btn`:
```css
font-weight: bold;
```

- `.btn-primary`:
```css
background-color: #42c7ff;
    border-color: #42c7ff;
```

- `.container`:
```css
width: 95%;
    max-width: 1200px;
    margin: auto;
    background: #ffffff;
    padding: 20px;
```

- `.memory-card`:
```css
width: 100px;
    height: 100px;
    perspective: 1000px; /* Hacer posible el giro en 3D */
```

- `.flip-container`:
```css
width: 100%;
    height: 100%;
    position: relative;
    transform-style: preserve-3d;
    transition: transform 0.5s;
```

- `.flip-container`:
```css
transform: rotateY(180deg); /* Voltear la carta */
```

- `.back`:
```css
position: absolute;
    width: 100%;
    height: 100%;
    backface-visibility: hidden; /* Esconde el lado opuesto */
```

- `.front`:
```css
background-color: #f1f1f1;
    /* Aquí puedes poner un color o una imagen de fondo si lo deseas */
```

- `.back`:
```css
background-color: #ccc;
    /* Aquí es donde iría la imagen de la carta */
    transform: rotateY(180deg); /* La parte trasera debe estar girada inicialmente */
```

- `.recordatorio-card`:
```css
padding: 15px;
```

- `.memory-card`:
```css
width: 100%; /* Se ajusta automáticamente al tamaño del grid */
        height: auto; /* Mantiene proporciones dentro del grid */
```

### IDs encontrados:
- `#formulario-recordatorio`:
```css
display: none;
    margin-top: 20px;
    background-color: #ffffff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 600px;
    font-family: Arial, sans-serif;
```

- `#memory-game`:
```css
display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 10px;
```

- `#restart-button`:
```css
display: none;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
```

- `#formulario-recordatorio`:
```css
width: 100%;
        padding: 15px;
```

- `#memory-game`:
```css
display: grid; /* Cambia a un grid layout */
        grid-template-columns: repeat(4, 1fr); /* 4 columnas */
        grid-auto-rows: 100px; /* Cada fila tendrá 100px de alto */
        gap: 10px; /* Espaciado entre las cartas */
        justify-content: center; /* Centrar el contenido horizontalmente */
```

## Archivo: `stylesSms.css`

### Clases encontradas:
- `.form-title`:
```css
background-color: #012e4f; /* Azul oscuro */
    color: white; /* Letras blancas */
    padding: 15px 20px; /* Espaciado interno */
    border-radius: 8px; /* Esquinas redondeadas */
    text-align: center; /* Centrar el texto */
    margin-bottom: 30px;
```

- `.form-label`:
```css
font-weight: bold;
    color: #012e4f; /* Azul oscuro */
```

- `.form-control-lg`:
```css
border: 2px solid #012e4f; /* Borde azul oscuro */
    border-radius: 8px; /* Esquinas redondeadas */
    transition: border-color 0.3s ease-in-out; /* Transición suave */
```

- `.btn-corporate`:
```css
background-color: #42c7ff; /* Azul corporativo */
    color: white; /* Letras blancas */
    border: none;
    border-radius: 8px;
    padding: 10px 20px;
    transition: background-color 0.3s ease, transform 0.3s ease; /* Transición suave */
```

- `.titulo-noticias`:
```css
text-align: center;
    font-size: 2.5rem;
    font-weight: bold;
    color: #012e4f;
    margin-bottom: 40px;
```

- `.card_fraude`:
```css
display: flex;
    flex-direction: row;
    max-width: 800px;
    margin: auto;
    background-color: rgba(248, 248, 255, 0.8); /* Fondo semitransparente */
    box-shadow: 0 4px 8px rgba(13, 110, 253, 0.5); /* Sombra */
    border-radius: 8px;
    overflow: hidden; /* Oculta elementos que sobresalgan */
    min-height: 220px; /* Altura mínima para evitar desajustes */
```

- `.card_fraude-body`:
```css
flex: 1; /* Toma el espacio restante */
    padding: 15px;
    display: flex;
    flex-direction: column; /* Alinea título, texto y enlace */
    justify-content: space-between; /* Distribuye espacio entre los elementos */
```

- `.card_fraude-title`:
```css
font-size: 1.5rem; /* Tamaño grande pero no exagerado */
    font-weight: bold;
    color: #333;
    margin-bottom: 10px;
```

- `.card_fraude-text`:
```css
font-size: 1.4rem; /* Accesible */
    color: #555;
    flex-grow: 1; /* Ocupa el espacio sobrante si es necesario */
    overflow: hidden;
    text-overflow: ellipsis; /* Muestra puntos suspensivos si el texto es demasiado largo */
    max-height: 8.5rem; /* Limita la altura del texto */
```


