# EmptyVisual$

**Máquina de Glitch Visual em Tempo Real** — *Visual Glitch Machine*

> jah works

![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-V8-brightgreen)
![WebGL](https://img.shields.io/badge/powered%20by-WebGL-orange)

---

## 🎨 O que é / What is it?

**EmptyVisual$** é uma ferramenta gratuita e open source para gerar visuais psicodélicos e glitch art em tempo real, direto no navegador. Combine filtros, manipule cores, distorções e moduladores para criar arte visual única — tudo processado via WebGL, 100% client-side, sem servidor.

**EmptyVisual$** is a free, open-source tool for generating psychedelic visuals and glitch art in real time, directly in your browser. Combine filters, manipulate colors, distortions, and modulators to create unique visual art — all processed via WebGL, 100% client-side, no server required.

---

## ✨ Features

| Feature | Descrição / Description |
|---|---|
| 🔥 **30+ Efeitos WebGL** | Mirrors, warps, anomalias, filtros — todos combináveis em stack |
| 🎨 **22 Mapas Cromáticos** | De Phosphor Verde a Rainbow Prism, troque paletas ao vivo |
| 🎮 **Suporte Nativo a Gamepad** | Xbox, PlayStation, genéricos — controle efeitos com o joypad |
| 📹 **Webcam / Câmera Mobile** | Capture vídeo ao vivo da webcam ou câmera do celular |
| 📼 **Upload de Vídeo** | Suporte a MP4, WebM e OGG |
| 🖼️ **Frame Lens** | 9 overlays visuais: CRT, VHS, Fish, Neon, Amber... |
| ✍️ **Texto Sobreposto** | Injete texto com fontes, cores, glow e blink |
| 🔴 **Gravação WebM** | Grave a saída processada em vídeo |
| 📷 **Captura de Frame** | Salve qualquer frame como PNG |
| 🌐 **Bilíngue PT/EN** | Interface em português e inglês |
| 📱 **Mobile Friendly** | Layout responsivo com split-screen vertical |
| ⛶ **Fullscreen & Popout** | Tela cheia ou janela destacada para VJing |

---

## 🚀 Como usar / How to use

### Online (Vercel)
Acesse o deploy e comece a usar — sem instalação.

### Local
1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/emptyvisuals.git
   ```
2. Abra `index3.html` em um servidor local (necessário para evitar restrições `file://`):
   ```bash
   npx serve .
   ```
3. Acesse `http://localhost:3000`

> ⚠️ **Nota:** Abrir direto como `file://` pode causar erros de segurança do navegador (CORS). Use sempre um servidor local ou deploy.

---

## 🎮 Controles

### Teclado
| Tecla | Ação |
|---|---|
| `Q W E R T Y U` | Toggle efeitos (RGB, Scan, Slice, Edge, Noise, Pixel, Invert) |
| `I O` | Kaleidoscope 4x / 8x |
| `A S D F` | Mirrors (X, Y, Quad, Diag) |
| `P` | Acid Warp |
| `1-9, 0, -, =` | Mapa cromático direto |
| `Espaço` | Limpar todos os efeitos |
| `Enter` | Efeitos aleatórios |
| `Setas` | Pan X/Y |
| `[ / ]` | Zoom |
| `PgUp / PgDn` | Blur |

### Gamepad (Xbox / Padrão)
| Botão | Ação |
|---|---|
| `A` | Acid Warp |
| `B` | Kaleidoscope 4x |
| `X` | Datamosh |
| `Y` | Kaleidoscope 8x |
| `LB / RB` | Navegar mapas cromáticos |
| `LT / RT` | Escurecer / Clarear |
| `D-Pad` | Scan, Edge, RGB, Slice |
| `L-Stick` | Pan XY |
| `R-Stick` | Zoom / Hue |
| `Select` | Limpar efeitos |
| `L3 + R3` | Reset total |

---

## 🛠️ Stack Técnica

- **HTML5** — Estrutura semântica single-page
- **CSS3** — Design hacker terminal (Share Tech Mono + VT323)
- **JavaScript Vanilla** — Zero dependências externas
- **WebGL** — Renderização GPU em tempo real (60fps)
- **MediaRecorder API** — Gravação nativa do canvas
- **Gamepad API** — Suporte nativo a controles

---

## 📁 Estrutura

```
public/
├── index3.html    # Arquivo principal (dev)
├── V8.html        # Release backup
├── demo.mp4       # Vídeo de demonstração
└── README.md
```

---

## 🔒 Segurança

- **100% Client-side** — Nenhum dado é enviado a servidores
- **Sem upload real** — Arquivos são lidos localmente via `URL.createObjectURL()`
- **Sem cookies de tracking** — Apenas `localStorage` para preferências do usuário
- **Seguro para deploy estático** (Vercel, Netlify, GitHub Pages)

---

## 👤 Sobre o Criador

**emptymtz** — Artista independente da Zona Leste de São Paulo.
Apaixonado por glitch art, arte digital, projeções e por bugar a realidade.

📷 Instagram: [@empty.mtz](https://instagram.com/empty.mtz)

Inspirado pelo projeto *Acid Cam* e pelo artista *Jared*.

---

## 🤖 Criado com

- [Claude Sonnet](https://anthropic.com) — Assistente de IA
- [Gemini](https://deepmind.google) — Assistente de IA  
- [Antigravity](https://deepmind.google) — Agentic AI Coding

---

## 📄 Licença

MIT License — Use, modifique e distribua livremente.

---

*carar jah works* ✦
