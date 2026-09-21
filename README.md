# TextoLocal
**OCR en español que funciona 100% sin internet. Tus documentos nunca salen de tu computador.**

Aplicación de escritorio para Windows que extrae texto de imágenes y PDFs escaneados y lo exporta a TXT, Word o PDF. Todo el procesamiento ocurre en tu equipo: no hay servidores, no hay subidas, no hay conexión. La única conexión posible es la descarga de un paquete de idioma (opcional) si se quiere usar el modulo de traducción, y solo cuando el usuario la acepta de forma expresa — la app nunca la inicia por su cuenta.

### [⬇ Descargar TextoLocal (Windows)](https://github.com/NicolasMunozSchmidt/TextoLocal/releases/download/v1.0/TextoLocal.zip)
![Ventana principal de TextoLocal](https://private-user-images.githubusercontent.com/330158011/655976453-b272d921-58bb-4606-a31f-ef08fabd6a77.PNG?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3OTAwMTc1NDcsIm5iZiI6MTc5MDAxNzI0NywicGF0aCI6Ii8zMzAxNTgwMTEvNjU1OTc2NDUzLWIyNzJkOTIxLTU4YmItNDYwNi1hMzFmLWVmMDhmYWJkNmE3Ny5QTkc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwOTIxJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDkyMVQxOTAwNDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT05OTM2Zjg5NTdiNDllOGUxMDRiMTg1YzdlY2E4ZjZhM2ZkOGZlZTBhNzM4YzlkZjUxOGRlOWM2NzIwYTJiMWQxJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZyZXNwb25zZS1jb250ZW50LXR5cGU9aW1hZ2UlMkZwbmcifQ.PoXKCvFmFvaoU81vG23giush4uSiA5jWRwHwIjV3k-c)
---

## Por qué existe

La mayoría de las herramientas para pasar un documento escaneado a texto funcionan subiendo el archivo a un servidor, casi siempre fuera de Chile. Para una foto cualquiera da lo mismo. Para una declaración jurada, un contrato o una ficha clínica, no.

Desde el 1 de diciembre de 2026 rige plenamente la **Ley 21.719 de protección de datos personales**, que endurece las obligaciones de quienes tratan datos de terceros y crea una agencia con facultades de fiscalización.

TextoLocal resuelve el mismo problema sin que el documento salga nunca del equipo.

## Qué hace

- Reconoce texto en español desde imágenes (`.png`, `.jpg`, `.jpeg`) y PDFs
- Detecta automáticamente los PDFs que ya traen texto y los procesa al instante
- Procesa varios archivos seguidos, en lote
- Permite editar el resultado antes de exportar
- Exporta a **TXT**, **Word (.docx)** y **PDF**
- Copia el texto al portapapeles con un clic
- Permite traducir texto reconocido al Inglés
- Permite exportar texto traducido

## Versión gratuita y licencia

La versión gratuita tiene **todas las funciones habilitadas**, con un límite de **10 páginas al día**. No hay marcas de agua, ni funciones bloqueadas, ni vencimiento.

| | Gratis | Personal | Estudio | Editorial 
|---|---|---|---|---|
| Páginas por día | 10 | Sin límite | Sin límite | Sin límite |
| Exportar a TXT, Word y PDF | Sí | Sí | Sí | Sí |
| Procesamiento por lotes | Sí | Sí | Sí | Sí |
| Equipos | 1 | 2 | 6 | 8 |
| Precio (CLP) | — | $29.000 ($32 USD) | $99.000 ($105 USD) | $190.000 ($199 USD) |
| Módulo de traducción | Sí | Sí | Sí | Sí | 
| Límite de traducción | 2000 palabras por día | 2000 palabras por día | 2000 palabras por día | Sin limites de palabras | 

Las licencias son de por vida: se pagan solo una vez y el programa es tuyo para siempre.

## Instalación

1. Descarga el archivo `.zip` desde el enlace de arriba
2. Descomprímelo en cualquier carpeta
3. Abre `TextoLocal.exe`

Windows va a mostrar el aviso **"Windows protegió tu PC"**. Es normal: la aplicación todavía no cuenta con certificado de firma digital, que es un trámite pagado que no hemos hecho. Presiona **"Más información"** y luego **"Ejecutar de todas formas"**.

No requiere instalador, ni permisos de administrador, ni Python.

## Requisitos

- Windows 10 o 11 (64 bits)
- 4 GB de RAM
- 700 MB de espacio libre

## Privacidad

TextoLocal no realiza ninguna conexión a internet, en ningún momento. Ni para procesar documentos, ni para activar la licencia, ni para buscar actualizaciones. Los modelos de reconocimiento vienen incluidos en el ejecutable y corren localmente.
La única conexión posible es la descarga de un paquete de idioma (opcional) si se quiere usar el modulo de traducción, y solo cuando el usuario la acepta de forma expresa — la app nunca la inicia por su cuenta.

La activación de licencia se verifica con una firma criptográfica en el propio equipo, sin consultar ningún servidor.

## Comprar una licencia

Escríbeme y coordinamos el pago mediante Transferencia bancaria, PayPal o cripto, La clave te llega el mismo día.

- Correo: ventastextolocal@gmail.com

## Donaciones

Si quieres donar y apoyar el desarrollo de este proyecto puedes enviar tu aporte a las siguientes direcciones: 

BTC: 1A5NVJHKbqZExBh1UYXjNNCwYAiNuZMowv

ETH: 0x2eb15c8cd0f75396e651333d8182d97a09c11f5f

LTC: LcopdX4EqL6fJa8yvNemYECrRzJwdroUXd


## Contacto

Desarrollado por Nicolás Muñoz. Si encuentras un error o necesitas algo puntual, escríbeme directamente: contesta la misma persona que hizo el programa.
