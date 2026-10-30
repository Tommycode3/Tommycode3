# Tommaso Maggiolo

Founder of [Aretē](https://arete.info) — EEG wearables. I build across neurotech, ML, embedded systems and hardware.

<!-- TODO(Tommaso): one sentence, in your own words -->

### Neurotech & brain–computer interfaces
| Repo | What it is | Verified result |
|---|---|---|
| [eeg-alpha-bench](https://github.com/Tommycode3/eeg-alpha-bench) | Does your EEG see alpha? Eyes-open/closed Berger-effect benchmark for any headset | 109 PhysioNet subjects: 82.6% pass, median EC/EO alpha reactivity 3.39×, IAF 10.15 ± 0.86 Hz |
| [flicker2grasp](https://github.com/Tommycode3/flicker2grasp) | SSVEP BCI (CCA, FBCCA, TRCA) on real EEG driving a MuJoCo robot arm | eTRCA 94.8% (12 classes, 0.5 s), 189.6 bit/min; 97–100% pick-and-place success |

### Physiology & sport
| Repo | What it is | Verified result |
|---|---|---|
| [fractal-threshold](https://github.com/Tommycode3/fractal-threshold) | DFA-α1 aerobic/anaerobic thresholds from RR intervals | Matches `nolds` to 1e-14; α1 1.25 → 0.59 across exercise tests; 2 ms beat jitter fakes a threshold |
| [bodyledger](https://github.com/Tommycode3/bodyledger) | Local-first wearable data store (COROS, Google Health) + read-only MCP server | Robust baselines (median/MAD), lag-checked correlations with FDR control |
| [fitbit-air-lab](https://github.com/Tommycode3/fitbit-air-lab) | BLE reverse-engineering lab for the Fitbit Air | GATT dump + HR stream recorder with gap-aware quality report |

### Aerospace & simulation
| Repo | What it is | Verified result |
|---|---|---|
| [tumble-to-point](https://github.com/Tommycode3/tumble-to-point) | CubeSat ADCS simulator: B-dot, MEKF with gyro bias, reaction-wheel pointing | RK4 error ratio 15.98 (theory 16); NEES 5.90 (expected 6); 50/50 Monte Carlo runs converge |

### Hardware & embedded
| Repo | What it is |
|---|---|
| [scriba-pendant](https://github.com/Tommycode3/scriba-pendant) | Open-hardware transcription pendant, nRF54L15 + nPM1300 (pre-schematic: architecture + power budget) |
| [lossless-dac](https://github.com/Tommycode3/lossless-dac) | Balanced headphone amp, LT3045/LT3094 ±5 V rails + OPA1622, captured in Zener |
| [jlcfind](https://github.com/Tommycode3/jlcfind) | Zero-dependency CLI: BOM → JLCPCB/LCSC parts, cost, fab zip |
| [bambu2resin](https://github.com/Tommycode3/bambu2resin) | Bambu Studio 3MF → Anycubic resin printers: orient, hollow, support, slice |
| [ir-parrot](https://github.com/Tommycode3/ir-parrot) | Learn/replay IR remotes on an nRF52840 (Zephyr) |
| [cyd-lab](https://github.com/Tommycode3/cyd-lab) | Three ESP32 display firmwares: clock/weather/Pomodoro, BT FFT spectrum, Spotify now-playing |

### Software & tools
| Repo | What it is |
|---|---|
| [crosscheck-a2a](https://github.com/Tommycode3/crosscheck-a2a) | Conformance & security auditor for A2A agent cards |
| [volante-ios](https://github.com/Tommycode3/volante-ios) | Podcasts + voice notes from steering-wheel buttons, for cars without CarPlay |
| [quiete](https://github.com/Tommycode3/quiete) | Typographic Android launcher in Jetpack Compose |
| [igforge](https://github.com/Tommycode3/igforge) | git log → Instagram posts, written by Claude Code, rendered headless |
| [wifi-doctor](https://github.com/Tommycode3/wifi-doctor) | Offline Wi-Fi diagnostics for macOS with an automatic verdict |
