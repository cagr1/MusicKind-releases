# MusicKind

Herramienta de escritorio para DJs en macOS: clasifica tu música por género, prepara sets por BPM y tonalidad Camelot, limpia duplicados y arregla metadatos. Gratis y software libre (GPL-3.0-or-later).

Página: https://carlosgallardo.dev/musickind/

## Descargar

En [Releases](../../releases/latest), elige el instalador de tu Mac (menú Apple → Acerca de este Mac):

| Tu Mac | Archivo |
|---|---|
| Apple Silicon (M1 o posterior) | `MusicKind-<versión>-arm64.dmg` |
| Intel | `MusicKind-<versión>.dmg` |

Requiere macOS 13 Ventura o posterior. Windows y Linux: no disponibles por ahora.

## Instalar

1. Abre el `.dmg` y arrastra **MusicKind** a **Aplicaciones**.
2. La app no está notarizada por Apple, así que la primera vez macOS mostrará «No se abrió “MusicKind”». **No pulses «Trasladar a la Papelera»: pulsa «Aceptar» (Done).**
3. Ve a **Ajustes del Sistema → Privacidad y seguridad**, baja hasta «Se bloqueó “MusicKind”…» y pulsa **Abrir igualmente**. Confirma con tu contraseña. Solo hace falta una vez.

En macOS 13–14 también sirve clic derecho → Abrir → Abrir; en macOS 15 Sequoia y posteriores ya no.

El manual de usuario (PDF) viene dentro del `.dmg`.

## Código fuente

Cada versión incluye en sus assets el código fuente correspondiente (`MusicKind-<versión>-source.zip`), conforme a la GPL-3.0-or-later. Ver [LICENSE](./LICENSE) y [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md) (libkeyfinder, FFTW, FFmpeg, Chromaprint y demás).

## Reportar un problema

Abre un [issue](../../issues) con tu versión de macOS, tipo de Mac (Apple Silicon o Intel), qué hacías y qué viste.

---

**English.** MusicKind is a free, GPL-3.0-or-later desktop app for DJs on macOS 13+: genre classification, set preparation by BPM and Camelot key, duplicate cleanup and metadata fixing. Download the `.dmg` for your Mac from [Releases](../../releases/latest). The app is not notarized by Apple: on first launch, click “Done” (not “Move to Trash”) on the “Not Opened” warning, then go to System Settings → Privacy & Security → Open Anyway and confirm with your password (right-click → Open only works on macOS 13–14). Source code for each version is attached to its release.
