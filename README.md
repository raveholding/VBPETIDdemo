# VincularB Pet ID · DEMO COMERCIAL

Demo de la **Ficha Inteligente de Mascota NFC + QR** de Vincular Business, para mostrar a potenciales clientes. **v1.0.0-demo**

Es la misma ficha que recibe el cliente final: **pública y de solo lectura**. No tiene panel, login, PIN ni ningún campo editable.

- La foto es la de Margoth. **El titular y los datos de salud son ficticios** (marcados EJEMPLO).
- Los datos de contacto de Vincular Business (WhatsApp y correo) son reales.

## Qué se puede probar
- WhatsApp con mensaje prearmado, llamada, Instagram, guardar contacto (vCard).
- Ubicación GPS **voluntaria** (pide permiso del navegador; funciona sobre HTTPS).
- Galería con ampliación, QR ampliable y descargable (necesita internet), instrucciones de lectura NFC/QR, aviso legal.

## Cómo se administra una ficha real
Los datos viven en el objeto `CONFIG` al inicio del script y solo los modifica el administrador de Vincular Business. En producción esos datos salen de una base de datos central con panel exclusivo del administrador y login validado en servidor.

## Límites de la demo
- El QR apunta a una URL de EJEMPLO (`fichas.ejemplo.com`): no imprimir ni grabar chips con ella.
- Es un archivo estático: cada cambio de datos requiere republicar.

## Uso
Abrir `index.html` en el navegador, o publicarlo en hosting con HTTPS para mostrarlo desde el celular del cliente.

## Contacto
Vincular Business · WhatsApp (387) 448-4132 · vincularbusiness@gmail.com
