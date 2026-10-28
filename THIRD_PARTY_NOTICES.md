# Componenti di terze parti

SC Radar Signal include i seguenti componenti open source. Sono inclusi nel pacchetto
**senza modifiche**.

## Qt for Python (PySide6, Shiboken6) e Qt 6

- Copyright © The Qt Company Ltd. e altri collaboratori.
- Licenza: **GNU Lesser General Public License v3** ([LICENSES/LGPL-3.0.txt](LICENSES/LGPL-3.0.txt)),
  che integra la GNU General Public License v3 ([LICENSES/GPL-3.0.txt](LICENSES/GPL-3.0.txt)).
- Codice sorgente: <https://code.qt.io/cgit/pyside/pyside-setup.git/> e <https://download.qt.io/official_releases/QtForPython/>.

Le librerie Qt e PySide6 sono file separati nella cartella `_internal` del pacchetto: in base
alla LGPL puoi sostituirle con una versione modificata o diversa. Se ti serve aiuto per farlo,
apri una [Issue](https://github.com/rastlien78/SC-Radar-Signal/issues).

## pygame e SDL2 (tastiera e joystick)

- pygame: licenza **GNU LGPL v2.1** ([LICENSES/LGPL-2.1.txt](LICENSES/LGPL-2.1.txt)) —
  <https://github.com/pygame/pygame>
- SDL2: licenza zlib — <https://www.libsdl.org/license.php>

## OCR: RapidOCR, modelli PaddleOCR, ONNX Runtime

- RapidOCR — Copyright © RapidAI. Licenza **Apache 2.0** ([LICENSES/Apache-2.0.txt](LICENSES/Apache-2.0.txt)) —
  <https://github.com/RapidAI/RapidOCR>
- Modelli PP-OCR (PaddleOCR) — Copyright © PaddlePaddle Authors. Licenza **Apache 2.0** —
  <https://github.com/PaddlePaddle/PaddleOCR>
- ONNX Runtime — Copyright © Microsoft Corporation. Licenza MIT — <https://github.com/microsoft/onnxruntime>

## OpenCV

- Copyright © OpenCV team. Licenza **Apache 2.0** — <https://opencv.org/license/>
- Il pacchetto `opencv-python-headless` include FFmpeg (licenza **GNU LGPL v2.1 o successiva**,
  <https://ffmpeg.org/legal.html>) e OpenBLAS (BSD 3-Clause).

## Altre librerie Python

| Componente | Licenza | Sito |
|---|---|---|
| Python | Python Software Foundation License | <https://docs.python.org/3/license.html> |
| NumPy (con OpenBLAS) | BSD 3-Clause | <https://numpy.org> |
| Pillow | MIT-CMU (HPND) | <https://python-pillow.org> |
| Shapely (con GEOS, LGPL v2.1) | BSD 3-Clause | <https://github.com/shapely/shapely> |
| pyclipper | MIT | <https://github.com/fonttools/pyclipper> |
| OmegaConf | BSD 3-Clause | <https://github.com/omry/omegaconf> |
| PyYAML | MIT | <https://pyyaml.org> |
| protobuf | BSD 3-Clause | <https://github.com/protocolbuffers/protobuf> |
| FlatBuffers | Apache 2.0 | <https://github.com/google/flatbuffers> |
| requests, urllib3, idna, charset-normalizer | Apache 2.0 / MIT / BSD 3-Clause | <https://requests.readthedocs.io> |
| certifi | Mozilla Public License 2.0 | <https://github.com/certifi/python-certifi> |
| tqdm | MPL 2.0 e MIT | <https://github.com/tqdm/tqdm> |
| colorlog, six | MIT | <https://pypi.org/project/colorlog/> |
| mss (cattura schermo) | MIT | <https://github.com/BoboTiG/python-mss> |
| jeepney (solo Linux) | MIT | <https://gitlab.com/takluyver/jeepney> |
| pynput (solo Windows) | GNU LGPL v3 | <https://github.com/moses-palmer/pynput> |

## PyInstaller (bootloader)

- Licenza: GPL v2 con eccezione speciale che consente la distribuzione di programmi non
  liberi — <https://github.com/pyinstaller/pyinstaller/blob/develop/COPYING.txt>

## Dati di gioco

- Estratti da [StarCitizenWiki/scunpacked-data](https://github.com/StarCitizenWiki/scunpacked-data)
  e aggiornati dall'app a ogni avvio.
- Star Citizen® è un marchio registrato di Cloud Imperium Rights LLC.
