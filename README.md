# SIGU — App móvil (descargas)

Este repositorio **no contiene código fuente**. Es solo un punto de descarga público para el
instalador Android (`.apk`) de **SIGU**, el sistema de asistencia y gestión académica de la
**UPT José Félix Ribas, Núcleo Socopó**.

El código fuente de la app vive en un repositorio privado aparte
(`SIGU-upt/SIGU-app-flutter`, Flutter/Dart); este repo existe únicamente para poder compartir
el `.apk` compilado sin exponer ese código.

## Descargar

La última versión está en **[Releases →](../../releases/latest)**.

| Dato | Valor |
|---|---|
| Versión | v1.0.0 |
| Plataforma | Android 8.0 (API 26) o superior |
| Tamaño | ~73.6 MB |
| SHA-256 | `94cd5e83c55e00b100f182c6c2273715907685bf272c30c39cca6a39cfad4909` |
| Análisis antivirus | [VirusTotal — 0/68 motores lo marcan como malicioso](https://www.virustotal.com/gui/file/94cd5e83c55e00b100f182c6c2273715907685bf272c30c39cca6a39cfad4909) |

**Siempre verifique el hash SHA-256** del archivo descargado antes de instalarlo, y compárelo
con el valor publicado arriba. Si no coinciden, no lo instale y repórtelo.

## Instalación (Android)

1. Descargue el `.apk` desde la página de [Releases](../../releases/latest).
2. Android bloqueará la instalación por defecto porque el archivo no viene de Google Play.
   Al abrirlo, el sistema pedirá permiso para "instalar apps desconocidas" — permítalo
   únicamente para esta descarga.
3. Siga el instalador. La app pedirá permisos de cámara (para escanear el código QR de
   asistencia) y, según el dispositivo, almacenamiento.
4. Inicie sesión con la cédula y contraseña entregadas por la institución.

## ¿Qué es SIGU?

SIGU centraliza el control de asistencia y la gestión académica de la institución: matrícula,
secciones, clases, reportes y asistencia por código QR que se renueva cada pocos segundos,
para dificultar el fraude de asistencia. Más información y el panel web en
[sigu-web.example](https://sigu-web.example) *(reemplazar por el dominio real)*.

## Seguridad y verificación

- El `.apk` se compila desde el repositorio fuente privado y se publica aquí sin modificaciones.
- El hash SHA-256 publicado en cada release permite verificar que el archivo descargado es
  exactamente el que se compiló y subió, sin alteraciones en el camino.
- Se recomienda revisar el reporte de VirusTotal enlazado en cada release antes de instalar.
- Si encuentra una discrepancia de hash, una versión no anunciada aquí, o cualquier
  comportamiento sospechoso del archivo, repórtelo a la coordinación del proyecto antes de
  instalar o distribuir el APK.

## Soporte

Dudas o problemas con la instalación: contacte a la coordinación de SIGU en su sede, o abra un
issue en este repositorio.

## Licencia

Ver [`LICENSE`](./LICENSE). El software distribuido aquí es de uso exclusivo de la comunidad de
la UPT José Félix Ribas, Núcleo Socopó; este repositorio de descargas no otorga licencia sobre
el código fuente, que permanece privado.
