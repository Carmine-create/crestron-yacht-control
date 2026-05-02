cat > README.md << 'EOF'
# ⚓ Crestron Yacht Control

[![Crestron CH5](https://img.shields.io/badge/Crestron-CH5-blue)](https://developer.crestron.com)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

## 🚀 Yacht Control System - CRESTRON CH5

Pannello di controllo professionale per yacht e imbarcazioni di lusso.

### 🎮 **Controlli disponibili**

| Sezione | Comandi | Tipo segnale |
|---------|---------|--------------|
| **Tende motorizzate** | SU / GIÙ / STOP | IR / Relè |
| **TV motorizzata** | ON / OFF / SU / GIÙ | IR + Motor |
| **Luci scena** | ON / OFF / 50% | Serial DMX |

### 🛠️ **Tecnologie utilizzate**

- CRESTRON CH5 2.0 Framework
- HTML5 / CSS3 / JavaScript ES6
- Simulazione comandi IR
- Digital Joins architecture

### 📱 **Anteprima**

```bash
npx serve . -p 3000
# Apri http://localhost:3000