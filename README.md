# mero-models

Model packages for the [MERØ](https://github.com/Msingi-AI/mero) on-device speech runtime. This repository holds releases only; the code is in `Msingi-AI/mero`.

The `models` release carries `catalog.json` plus the files of each package. The MERØ demo app reads the catalog, downloads a package and checks every file against its sha256 before using it.

| Package | Task | Source | Licence |
|---|---|---|---|
| `asr-eddiegulay-xlsr-sw-int8` | Swahili speech to text | eddiegulay/wav2vec2-large-xlsr-mvc-swahili (int8) | Apache-2.0 |
| `tts-piper-sw-lanfrica` | Swahili text to speech | speaches-ai/piper-sw_CD-lanfrica-medium | **Unresolved**: the training dataset permits non-profit, educational and public-benefit use only. Evaluation use only. |

These are development candidates, not accepted packages.
