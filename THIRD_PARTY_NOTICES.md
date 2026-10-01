# Third-party notices

## libkeyfinder 2.2.8

Copyright © Ibrahim Sha'ath and libkeyfinder contributors. Source: [Mixxx libkeyfinder 2.2.8](https://github.com/mixxxdj/libkeyfinder/tree/2.2.8).
License: GNU General Public License version 3 or (at your option) any later version.
The complete upstream license is included at `vendor/bin/licenses/libkeyfinder-COPYING`.

## FFTW 3.3.11

Copyright © Matteo Frigo and Steven G. Johnson. Source: [FFTW 3.3.11](https://fftw.org/).
License: GNU General Public License version 2 or (at your option) any later version.
The complete upstream license is included at `vendor/bin/licenses/fftw-COPYING`.

## FFmpeg 9.0.2

Static macOS arm64 and amd64 FFmpeg/FFprobe builds from [Martin Riedl's build server](https://ffmpeg.martin-riedl.de/). Fixed release assets:
- arm64: [FFmpeg](https://ffmpeg.martin-riedl.de/download/macos/arm64/1789931890_9.0.2/ffmpeg.zip), [FFprobe](https://ffmpeg.martin-riedl.de/download/macos/arm64/1789931890_9.0.2/ffprobe.zip)
- amd64: [FFmpeg](https://ffmpeg.martin-riedl.de/download/macos/amd64/1789931006_9.0.2/ffmpeg.zip), [FFprobe](https://ffmpeg.martin-riedl.de/download/macos/amd64/1789931006_9.0.2/ffprobe.zip)

These builds enable GPL and version 3 components. The applicable license is GNU GPL version 3 or later; complete license text is included at `vendor/bin/licenses/FFmpeg-COPYING.GPLv3`. SHA-256 pins are in `scripts/fetch-binaries.sh`.

## Chromaprint 1.5.1

Official universal macOS `fpcalc` from [AcoustID's v1.5.1 release](https://github.com/acoustid/chromaprint/releases/tag/v1.5.1). The binary includes FFmpeg 4.4.1 components; Chromaprint's release license identifies the combined binary as LGPL-2.1, with MIT for Chromaprint's own source. License texts are included at `vendor/bin/licenses/Chromaprint-LICENSE.md` and `vendor/bin/licenses/COPYING.LGPLv2.1`.

## Other included or required software

- **SDL2 2.32.10** — zlib License. Copyright © Sam Lantinga and SDL contributors. The license is included at `vendor/python/darwin-*/python/licenses/SDL2-LICENSE.txt`.

- **Electron** — MIT License. Copyright © OpenJS Foundation and Electron contributors.
- **librosa** — ISC License. Copyright © librosa contributors.
- **Essentia** — AGPL-3.0-only. Copyright © Universitat Pompeu Fabra.
- **NumPy** — BSD 3-Clause License. Copyright © NumPy developers.
- **Demucs** — MIT License. Copyright © Alexandre Défossez and contributors.
- **CPython 3.11.16** — PSF License Version 2. Python source and runtime are distributed under the Python Software Foundation License; its license and notices are included with the standalone runtime.
- **Python core dependencies** — pinned in `requirements-core.txt`; their upstream license texts and notices are included in the standalone runtime's package metadata. This set includes audioread (MIT), certifi (MPL-2.0), cffi (MIT), charset-normalizer (MIT), cloudpickle (BSD-3-Clause), decorator (BSD-2-Clause), idna (BSD-3-Clause), joblib (BSD-3-Clause), lazy-loader (MIT), librosa (ISC), llvmlite (BSD-2-Clause), msgpack (Apache-2.0), mutagen (GPL-2.0-or-later), narwhals (MIT), numba (BSD-2-Clause), NumPy (BSD-3-Clause), packaging (Apache-2.0 or BSD-2-Clause), platformdirs (MIT), pooch (BSD-3-Clause), pycparser (BSD-3-Clause), PyYAML (MIT), requests (Apache-2.0), scikit-learn (BSD-3-Clause), SciPy (BSD-3-Clause), six (MIT), soundfile (BSD-3-Clause), soxr (LGPL-2.1-or-later), threadpoolctl (BSD-3-Clause), typing-extensions (PSF-2.0), and urllib3 (MIT).
- **FFmpeg** — GPL-3.0-or-later for the bundled macOS builds above.

Their respective upstream license texts apply to those components. MusicKind's source is licensed under GPL-3.0-or-later; see `LICENSE`.
