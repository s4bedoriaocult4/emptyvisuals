# EmptyVisual$

**Máquina de Glitch Visual em Tempo Real** — *Visual Glitch Machine*

> jah works ✦

![License](https://img.shields.io/badge/license-MIT-green)
![Version](https://img.shields.io/badge/version-V8-brightgreen)
![WebGL](https://img.shields.io/badge/powered%20by-WebGL-orange)

---

## o que é isso

## 🎨 O que é / What is it?

**EmptyVisual$** é uma ferramenta gratuita e open source para gerar visuais psicodélicos e glitch art em tempo real, direto no navegador. Combine filtros, manipule cores, distorções e moduladores para criar arte visual única — tudo processado via WebGL, 100% client-side, sem servidor.

**EmptyVisual$** is a free, open-source tool for generating psychedelic visuals and glitch art in real time, directly in your browser. Combine filters, manipulate colors, distortions, and modulators to create unique visual art — all processed via WebGL, 100% client-side, no server required.

---

## o que dá pra fazer

| | |
|---|---|
| 🔥 **30+ Efeitos WebGL** | Mirrors, warps, anomalias, filtros — todos empilháveis |
| 🎨 **22 Mapas Cromáticos** | De Phosphor Verde a Rainbow Prism, troca ao vivo |
| 🎮 **Suporte a Gamepad** | Xbox, PlayStation, genéricos — controla tudo pelo controle |
| 📹 **Webcam / Câmera Mobile** | Captura ao vivo direto do navegador |
| 📼 **Upload de Vídeo** | MP4, WebM e OGG |
| 🖼️ **Frame Lens** | 9 overlays: CRT, VHS, Fish, Neon, Amber... |
| ✍️ **Texto Sobreposto** | Injeta texto com fonte, cor, glow e blink |
| 🔴 **Gravação WebM** | Grava a saída processada em vídeo |
| 📷 **Captura de Frame** | Salva qualquer frame como PNG |
| 🌐 **PT / EN** | Interface em português e inglês |
| 📱 **Mobile** | Layout responsivo, funciona no celular |
| ⛶ **Fullscreen & Popout** | Tela cheia ou janela destacada pra VJing |

---

## como usar

### online
Acessa o deploy no Vercel e já vai. Sem instalar nada.

### local
```bash
git clone https://github.com/s4bedoriaocult4/emptyvisuals.git
cd emptyvisuals
npx serve .
# abre http://localhost:3000
```

> ⚠️ Abrir o `index.html` direto como `file://` pode travar por restrição de CORS do navegador. Usa um servidor local ou o deploy.

---

## controles

### teclado

| Tecla | Efeito |
|---|---|
| `Q W E R T Y U` | RGB, Scan, Slice, Edge, Noise, Pixel, Invert |
| `I O` | Kaleidoscope 4x / 8x |
| `A S D F` | Mirrors (X, Y, Quad, Diag) |
| `P` | Acid Warp |
| `1-9, 0, -, =` | Mapa cromático direto |
| `Espaço` | Limpa todos os efeitos |
| `Enter` | Efeitos aleatórios |
| `Setas` | Pan X/Y |
| `[ / ]` | Zoom |
| `PgUp / PgDn` | Blur |

### gamepad (Xbox / padrão)

| Botão | Ação |
|---|---|
| `A` | Acid Warp |
| `B` | Kaleidoscope 4x |
| `X` | Datamosh |
| `Y` | Kaleidoscope 8x |
| `LB / RB` | Navega mapas cromáticos |
| `LT / RT` | Escurece / Clareia |
| `D-Pad` | Scan, Edge, RGB, Slice |
| `L-Stick` | Pan XY |
| `R-Stick` | Zoom / Hue |
| `Select` | Limpa efeitos |
| `L3 + R3` | Reset total |

---

## stack

- **HTML5 + CSS3 + JS Vanilla** — zero dependências externas
- **WebGL** — renderização GPU em tempo real (60fps)
- **MediaRecorder API** — gravação nativa do canvas
- **Gamepad API** — suporte nativo a controles

---

## estrutura

```
emptyvisuals/
├── index.html     # aplicação completa (single file)
├── demo.mp4       # vídeo de demonstração
├── .gitignore
├── LICENSE
└── README.md
```

---

## segurança / privacidade

Tudo roda no seu navegador. Nenhum dado vai pra servidor, nenhum upload real acontece — os arquivos são lidos localmente via `URL.createObjectURL()`. Sem cookies de tracking, só `localStorage` pras preferências.

---

## apoio

Se o projeto te ajudou, qualquer contribuição é muito bem-vinda:

- **Ko-fi:** [ko-fi.com/emptymtz](https://ko-fi.com/emptymtz)

---

## créditos

Feito com Claude Sonnet, Gemini e Antigravity.

📷 Instagram: [@empty.mtz](https://instagram.com/empty.mtz)

---

## licença

MIT — usa, modifica, distribui à vontade.

---

*carar jah works* ✦
