# Homem-Aranha 8-bit 🕷️

[![Deploy PWA to GitHub Pages](https://github.com/renatowu/homemaranha/actions/workflows/deploy.yml/badge.svg)](https://github.com/renatowu/homemaranha/actions/workflows/deploy.yml)

Jogo de plataforma/ação em estilo 8-bit, feito em um único arquivo HTML com `<canvas>` puro — sem dependências. Balance nas teias, atire bolas de teia, pegue power-ups e enfrente o chefão **Duende Verde**.

Jogar: **https://renatowu.github.io/homemaranha/**

## Como jogar

| Ação | Teclado | Toque / Mouse |
|------|---------|---------------|
| Balançar na teia | Segure **Espaço** / **⬆** / **W** | Segure **TEIA** (ou clique esquerdo) |
| Atirar bola de teia | **F** / **X** / **J** | Botão **TIRO** (ou clique direito) |
| Mudo | **M** | Botão **♪** |

- **Power-ups:** 🛡️ escudo, ⚡ tiro rápido, ❤️ vida extra
- **Chefão:** o Duende Verde aparece a cada trecho, voando no planador e jogando bombas-abóbora
- Desvie de espinhos e drones, e vá o mais longe possível

## PWA (instalar como app)

O jogo é um Progressive Web App. Ao abrir a URL acima no celular, use **"Adicionar à tela de início"** (iOS) ou **"Instalar app"** (Android) para rodar em tela cheia e offline.

## Rodar localmente

```bash
python3 -m http.server 8123
# abra http://localhost:8123
```

## Notas

- Trilha sonora e efeitos são **chiptune originais** gerados em tempo real via Web Audio (nada de arquivos de áudio).
- Projeto de fã, sem fins comerciais, para estudo e diversão.
