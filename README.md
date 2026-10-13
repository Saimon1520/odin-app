# Odín — app para Android

Odín es un asistente de voz personal. Esta app es solo la puerta de entrada: el asistente corre en una computadora privada, y la app no funciona sin un **código de emparejamiento** que da su dueño.

## Instalar

1. En el celular, abre la [última versión](https://github.com/Saimon1520/odin-app/releases/latest) y descarga **`odin.apk`**.
2. Ábrelo. Si Android lo pide, permite «Instalar apps de fuentes desconocidas» para el navegador o el gestor de archivos.
3. Abre Odín, toca **«Emparejar un dispositivo nuevo»** y escribe el código que te pasaron. El código sirve una sola vez y caduca.
4. Acepta el permiso del **micrófono** y entra con tu huella o tu rostro.

Requiere Android 7.0 o superior.

## Actualizar

Descarga el nuevo `odin.apk` de la misma página e instálalo encima: se conserva el emparejamiento.

## Privacidad

- El código de Odín y sus datos no están en este repositorio.
- Lo que dices viaja cifrado (HTTPS de punta a punta, por un túnel de Tailscale) hasta la computadora del dueño; la voz y las respuestas se procesan ahí, no en la nube. Solo las búsquedas web que le pidas salen a internet.
- Cada dispositivo se puede revocar en cualquier momento desde esa computadora.
