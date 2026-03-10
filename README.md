# esp32_multitrack_looper
ESP32 Audio Kit based multitrack looper

- video presentation of the initial state of this project https://youtu.be/PKQmOsJ-g1I
- little quick start guide to get started with arduino synthesizer / music projects: https://youtu.be/ZNxGCB-d68g

Supported versions of board library
---
- ESP32 version 1.0.6 from https://github.com/espressif/arduino-esp32/releases/tag/1.0.6
- ESP32 version 2.0.2 from https://github.com/espressif/arduino-esp32/releases/tag/2.0.2
Please be aware that other versions might be not supported.

The project has been tested on the ESP32 Audio Kit V2.2

Useful documents:
ESP32 Audio Kit docu: http://myosuploads3.banggood.com/products/20210306/20210306011116instruction.pdf
 
---
The latest update has been tested on the ESP32 Audio Kit V2.2 with an ES8388 audio codec.
You can use it stand-alone when applied the analog button mod (https://youtu.be/r0af0DB1R68)
Default configuration:
- Key1: set length
- Key2: toggle click
- Key3 - Key6: toggle rec mode

I recommend using Tera Term or another VT100 compatible tool to see whats going on inside of the application























<!-- CHANTIER:AUDIT START -->
## Audit & Execution Plan (2026-03-10)

### Snapshot
- Priority: `P2`
- Tech profile: `other`
- Workflows: `yes`
- Tests: `yes`
- Debt markers: `0`
- Source files: `7`

### Corrections Prioritaires
- [ ] Optimisation ciblée perf/maintenabilité
- [ ] Ajouter/fiabiliser les commandes de vérification automatiques.
- [ ] Clore les points bloquants avant optimisation avancée.

### Optimisation
- [ ] Identifier le hotspot principal et mesurer avant/après.
- [ ] Réduire la complexité des modules les plus touchés.

### Mémoire chantier
- Control plane: `/Users/electron/.codex/memories/electron_rare_chantier`
- Repo card: `/Users/electron/.codex/memories/electron_rare_chantier/REPOS/esp32_multitrack_looper.md`

<!-- CHANTIER:AUDIT END -->
