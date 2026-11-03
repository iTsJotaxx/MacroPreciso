# MacroPreciso

Programa de Windows para grabar y reproducir macros (teclado y ratón) con precisión, pensado para Roblox. Un solo archivo `.exe`, sin instalador.

**[⬇ Descargar la última versión](https://github.com/iTsJotaxx/MacroPreciso/releases/latest)** (archivo `MacroPreciso.exe`)

## Qué hace

- **Grabar y reproducir macros** de teclado y ratón con sus tiempos exactos.
- **Macros de cámara para Roblox**: mide la cámara y la restaura antes de cada vuelta.
- **Macros guardadas** con tecla rápida propia para lanzarlas desde cualquier sitio.
- **Autoclicker** y **Detector**.
- Abre grabaciones `.mcp` y `.rec` de TinyTask, y puede crear un `.exe` con una macro dentro.
- Idiomas: español, inglés y francés.

## Cómo usarlo

1. Descarga `MacroPreciso.exe` desde la sección **Releases** de este repositorio.
2. Ejecútalo. No necesita instalación ni permisos de administrador.
3. Graba una macro, guárdala y asígnale una tecla.

## Sobre el aviso de Windows

Al abrirlo por primera vez puede salir **«Windows protegió su PC»** (SmartScreen) o un aviso del antivirus. Pasa con casi todos los programas pequeños sin firma digital, y más con los que simulan teclado y ratón, que es justo lo que hace una macro.

Para comprobar que tienes el archivo original:

- Compara su huella **SHA-256** con la que aparece en las notas de cada Release. En PowerShell: `Get-FileHash .\MacroPreciso.exe -Algorithm SHA256`
- Súbelo tú mismo a [virustotal.com](https://www.virustotal.com) y mira el resultado.
- Si te fías, pulsa **Más información → Ejecutar de todas formas**.

## Aviso

Úsalo bajo tu responsabilidad. Revisa las normas del juego en el que lo uses: algunos juegos no permiten automatizar acciones.
