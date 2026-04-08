# 🏋️ MarombaCount 🏋️

> **Contador de séries e descanso.**  
> Sem frescura. Sem distração.

---

## Como funciona

O app foi pensado pra ser usado em modo **paisagem**, com o celular apoiado na academia. A tela é dividida em dois painéis:

| Lado | Gesto | Ação |
|------|-------|------|
| ◀ **Esquerdo** | Toque | +1 série concluída |
| ◀ Esquerdo | Botão ↺ | Reseta o contador de séries |
| ▶ **Direito** | Toque | Inicia / pausa / retoma o descanso |
| ▶ Direito | Segurar | Reseta o timer de descanso |
| ▶ Direito | ⚙ | Configura o tempo de descanso |

---

## Instalação

Acesse:

```
https://seu-usuario.github.io/Maromba-Conta
```

No Chrome → menu **⋮** → **Adicionar à tela inicial** → vira ícone nativo, sem Play Store.

## Funcionalidades

- **Wake Lock** — tela nunca apaga durante o treino
- **Vibração** — feedback tátil em cada ação e alerta ao fim do descanso
- **Offline** — funciona sem internet após a primeira abertura (Service Worker)
- **Fullscreen** — sem barra de navegação, modo imersivo total
- **Presets rápidos** — 30s / 45s / 1min / 1:30 / 2min / 3min
- **Sem cadastro, sem ads, sem frescura**

---

## Estrutura

```
maromba-count/
├── index.html      # App completo (HTML + CSS + JS em um único arquivo)
├── manifest.json   # Configuração PWA (ícone, orientação, fullscreen)
└── sw.js           # Service Worker para cache offline
```

---

## Design

Paleta dark com dois acentos:

- 🟡 `#E8FF00` — séries (lado esquerdo)
- 🟠 `#FF6B00` — descanso (lado direito)

Tipografia: **Bebas Neue** (números) + **Barlow Condensed** (textos)

---

## Licença

MIT — usa, modifica, distribui à vontade. Só não falta no treino.
