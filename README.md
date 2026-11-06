# Urban Voice — descargas e instalación

Plugin de voz de **Urban Essentials**. Se necesita una licencia de compra para activar el procesamiento. Descargar el instalador no activa una suscripción ni realiza un cobro.

## Elegí tu computadora

- [Mac con chip Apple M1, M2, M3, M4 o posterior](https://github.com/dieguitus2001-commits/urban-voice-downloads/releases/download/v0.4.0/Urban-Voice-0.4.0-Mac-Apple-Silicon.pkg)
- [Mac con procesador Intel](https://github.com/dieguitus2001-commits/urban-voice-downloads/releases/download/v0.4.0/Urban-Voice-0.4.0-Mac-Intel.pkg)
- [Windows de 64 bits](https://github.com/dieguitus2001-commits/urban-voice-downloads/releases/download/v0.4.0/Urban-Voice-0.4.0-Windows-x64-Setup.exe)

En Mac, abrí el menú Apple → Acerca de este Mac: si dice **Chip Apple**, elegí Apple Silicon; si dice **Procesador Intel**, elegí Intel. Requiere macOS 11 o posterior. Windows requiere Windows 10 versión 1809 o posterior, de 64 bits. La compatibilidad con cada programa de música debe comprobarse en ese programa.

## Instalar en Mac

1. Guardá tu proyecto y cerrá Logic Pro y los demás programas de audio.
2. Descargá el `.pkg` correspondiente a tu equipo desde los enlaces de esta página.
3. Abrí el instalador y completá los pasos. Se incluyen AU para Logic, VST3 para otros programas y la aplicación Urban Voice.
4. Esta versión **no tiene firma Developer ID ni certificación notarial de Apple**. Si macOS indica que no puede verificar el desarrollador, comprobá que descargaste el archivo desde esta página. Si decidís continuar, después de intentar abrirlo entrá en **Ajustes del Sistema → Privacidad y seguridad → Abrir igualmente** y confirmá ese instalador. Es el [procedimiento explicado por Apple](https://support.apple.com/es-es/102445). No hace falta desactivar globalmente la seguridad del equipo.
5. Volvé a abrir tu programa de audio. En Logic, insertá **Audio Units → Sonido Fresh → Urban Voice** en un canal de voz. El fabricante conserva ese nombre para mantener la compatibilidad con proyectos anteriores.
6. Si no aparece, reiniciá el Mac y revisá el gestor de módulos de Logic. Seleccioná Urban Voice y ejecutá la opción de restablecer y volver a explorar la selección.

Si el aviso afirma que el archivo contiene malware o está dañado, detené la instalación y contactanos con el texto exacto del aviso.

## Instalar en Windows

1. Guardá tu proyecto y cerrá los programas de audio.
2. Abrí `Urban-Voice-0.4.0-Windows-x64-Setup.exe` y seguí el asistente. Permití la instalación de Microsoft WebView2 incluida si todavía no está instalado.
3. Este instalador todavía no tiene certificado de firma comercial. Si Windows muestra un aviso de aplicación no reconocida, verificá el origen y el nombre del archivo antes de decidir continuar. No desactives el antivirus ni sus protecciones globales.
4. Abrí tu programa y buscá **Urban Voice** como efecto VST3. El instalador usa la carpeta estándar `C:\Program Files\Common Files\VST3`.
5. En FL Studio: **Options → Manage plugins → Find installed plugins**; luego cargalo en un slot de efectos del Mixer. [Guía oficial de FL Studio](https://www.image-line.com/fl-studio-learning/fl-studio-online-manual/html/basics_externalplugins.htm).

Que el instalador se cierre al terminar es normal. El plugin se abre desde tu programa de música.

## Activar y usar tu licencia

Abrí Urban Voice, pulsá **Activar licencia**, pegá la clave del correo de Urban Essentials y confirmá. Necesitás internet para activarlo y verificarlo periódicamente. Se permiten hasta **2 equipos**. Para cambiar de computadora, usá **Liberar este equipo** antes de activar la otra.

- **USD 20 mensuales:** acceso hasta el final del período pagado, más **72 horas de gracia**. Si no se renueva, el procesamiento pasa suavemente a bypass; tus presets, ajustes y automatizaciones se conservan. Tras regularizar el pago, pulsá **Verificar** con internet.
- **USD 79 definitivo:** un pago, sin vencimiento mensual.
- Después de una verificación válida podés trabajar hasta **7 días sin conexión**, sin superar el vencimiento de tu plan. La licencia definitiva también necesita verificaciones periódicas.

Para actualizar tu tarjeta, consultar facturas o cancelar la renovación, entrá en [Gestionar mi suscripción](https://billing.stripe.com/p/login/7sYfZi1ag3HB9K3e0E2kw00) con el correo de tu compra. La cancelación detiene las próximas renovaciones; conservás el período ya pagado y sus 72 horas de gracia.

Los precios base son en dólares estadounidenses y no incluyen los impuestos que correspondan. Stripe muestra el total antes de pagar y puede ofrecer una moneda local.

La actualización conserva los presets del usuario. Si el instalador detecta dos copias del plugin, no las borres al azar: contactanos para identificar la que usa tu proyecto.

## Ayuda

Escribí a **urbanessentials@urbanvoice.online** indicando tu sistema, programa de audio y el mensaje de error. No publiques tu clave de licencia.

Versión 0.4.0. Los archivos SHA-256 de la publicación permiten comprobar que la descarga corresponde a esta entrega. Este repositorio distribuye instaladores; no publica el código fuente del producto.
