# Documentación de Archivos PHP

## Archivo: `chatBot.php`

```php
* ChatBot de ayuda
 *
```

## Archivo: `chatBotApi.php`

```php
* Lógica para implementar el ChatBot de ayuda
 *
 * Uso una apiKey de OpenAI: Configurado para que se le 
 * haga la pregunta a la IA y responda al usuario de la 
 * manera más correcta, amigable y sencilla para los usuarios
```

## Archivo: `conexion.php`

```php
* 
 * Archivo con la configuracion de la conexion
 * Los parametros los coge de parametros.php
 *
```

## Archivo: `diagnostico.php`

```php
* Página para obtener un diagnosticos de posibles enfermedades
 * valorando el sintoma seleccionado en el desplegable.
 * Los resultados se obtienen desde un Json
 *
```

## Archivo: `eliminar_recordatorio.php`

```php
* Página con la lógica para poder eliminar un recordatorio
 *
```

## Archivo: `entretenimiento.php`

```php
* Página relacionada con el entreteniemiento
 * - Viajes
 * - Cine y teatros
 * - Ocio
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

## Archivo: `erroresMamp.php`

```php
* Con esto habilito la opcion de ver los errores
 * Practico para encontrar posibles fallos
 *
```

## Archivo: `favicon.php`

```php
* Imagenes en todos los formatos posibles para mostrar el logo de la pagina
 * Lo creo en la página https://www.favicon-generator.org/ 
 *
```

## Archivo: `footer.php`

```php
* Footer de la web
 *
```

## Archivo: `footerLegal.php`

```php
* Pagina en la que muestro la politica de privacidad de la web, 
 * créditos y términos de uso
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

## Archivo: `formularioLogin.php`

```php
* Formulario para hacer logon en la web
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado
     * @see header.php
```

## Archivo: `formularioRegistro.php`

```php
* Formulario para registrarse en la web
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

## Archivo: `generate_php_doc.php`

```php
* Este archivo lo utilizo para generar la documentacion del codigo en php
```

## Archivo: `gestion.php`

```php
* Página de gestion
 * Contiene las secciones para gestionar DNI, papeleos y apoyo integral.
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo contiene el encabezado general del proyecto.
 * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

## Archivo: `gestionAgenTrib.php`

```php
* Página de gestiones relacionadas con la agencia tributaria
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

## Archivo: `gestionDNI.php`

```php
* Página de gestiones con el dni
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

## Archivo: `gestionVarios.php`

```php
* Página de gestiones varias
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

## Archivo: `guardar_recordatorio.php`

```php
* Lógica para guardar recordatorios en el area personal
 * Necesario que el usuario este loguado para entrar
 * Obtengo la variable nombre para personalizar el saludo
 *
```

## Archivo: `header.php`

```php
* Menu para navegar de una pagina a otra
 * Utilizo dos modelos, uno para dispositivos grandes y otro menu
 * tipo hamburguesa para dispositivos pequeños
 * Ademas aplico la propiedad sticky para fijarlo
 *
```

## Archivo: `headerPrincipal.php`

```php
* Menu de la página principal.
 * Con dos vistas:
 * - Con las opciones de registro o login.
 * - Con la opcion de salir
```

## Archivo: `index.php`

```php
* Página de inicio ViCo.
 * 
 *
 * @author Maria Teresa Sáez Gallardo
 * @version 1.0
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

## Archivo: `login.php`

```php
* Lógica para hacer login en la web
```

## Archivo: `logout.php`

```php
* Ciere de la sesión
```

## Archivo: `movilidad.php`

```php
* Página relacionada con la movilidad
 * - Herramienta para obtener informacion de rutas en bus
 * - Informacion de renfe, radioTaxi, Biki
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
 * @see header.php
```

## Archivo: `parametros.php`

```php
* 
 * Archivo con los parametros de la conexion
 * Tengo definidas dos conexiones, dependiendo
 * de si la conexion la hago el local, o si la conexion 
 * la subo a produccion
 *
```

## Archivo: `principal.php`

```php
* Página principal de opciones de ViCo.
 * Contiene las 5 secciones principales en las q se divide la aplicacion
 * Gestion, movilidad, salud, entretenimiento y seguridad
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

```php
* Este archivo incluye el footer
     * @see footer.php
```

## Archivo: `procesar_sms.php`

```php
* En este archivo esta toda la lógica para poder consultar si un sms es fraudulento
 * la herramienta esta implemntada con OpenAI, para lo q uso una ApiKey
```

```php
* Funcion que verifica un sms con IA
 * @return void
```

## Archivo: `registro.php`

```php
* Página en la que se realiza la validación de los valores que introducce el usuario
 * en el formulario de registro
 *
```

## Archivo: `rinconVico.php`

```php
* Pagina a la q he denominado Rincon Vico
 * solamente accesible si el usuaior ha hecho login
```

## Archivo: `salud.php`

```php
* Página relacionada con la salud de gestion de ViCo 
 * - Diagnostico de sintomas
 * - Cita médica
 * - Tutoriales
 * - Farmacias
 * - Consejos
 *
```

```php
* Esta sección incluye el favicon (logo)
   * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
   * @see header.php
```

```php
* Este archivo incluye el chatBot
   * @see chatBot.php
```

## Archivo: `smsFraudulento.php`

```php
* Página relacionada con la seguridad. Prevencion de fraudes
 * - Herramienta para obtener informacion sobre si un sms recibido es una posible estafa
 * - Noticias relacionadas con las estafas
 *
```

```php
* Este archivo incluye el favicon (logo)
     * @see favicon.php.php
```

```php
* Este archivo incluye el encabezado de la página.
     * @see header.php
```

```php
* Este archivo incluye el chatBot
     * @see chatBot.php
```

