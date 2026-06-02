![susurro cabula](susurro-cabula/img/header.png)

# ☥ susurro cabula

`freq : quiet · signal : alive`

A small, portable cheat-sheet for a Roland AIRA Compact rig — **T-8 + S-1 + P-6 + J-6 + E-4** into a Xone:92 mixer. Built for fast reading at the desk, not for show. Plain-text and NomadNet `.mu` (micron) versions included.

Uma cábula pequena e portátil para um setup Roland AIRA Compact — **T-8 + S-1 + P-6 + J-6 + E-4** ligado a um Xone:92. Feita para ler depressa na mesa, não para mostrar. Inclui versões em texto e em `.mu` (micron) para NomadNet.

---

## the five / as cinco

- **T-8 = pulse / pulso** — time master · drums · bass
- **S-1 = air / ar** — synth · filter · breath
- **P-6 = memory / memória** — short samples
- **J-6 = chord / acorde** — harmony · JUNO-60 · the soul of '82
- **E-4 = voice / voz** — singing · auto-pitch · harmony · vocoder

> t-8 walks · p-6 remembers · s-1 breathes
> j-6 harmonises · e-4 sings
> t-8 caminha · p-6 lembra · s-1 respira
> j-6 harmoniza · e-4 canta

---

## three things, not two / três coisas, não duas

- **audio / áudio** — the sound · black TRS cables
- **sync** — the time · colored TS cables
- **control / controlo** — each machine's own knobs (they move only it)

Never route sync through audio, or audio through sync.
Nunca passar sync por áudio, nem áudio por sync.

---

## single-output chain / cadeia única

```
P-6 › T-8 › S-1 › J-6 › E-4 › Xone:92 (LINE) › amp › colunas
```

E-4 goes last — voice joins the instrument mix in one cable out.
A E-4 fica em último — a voz junta-se ao mix num só cabo.

---

## contents / conteúdos

```
cheatsheet/
  cabula.txt      — 1-page, instant read (PT)
  completa.txt    — full reference (PT)
node/
  susurro-cabula-en.mu   — NomadNet page (EN)
  susurro-cabula-pt.mu   — NomadNet page (PT)
```

The `.mu` files use micron markup (`>>>` headers, `F222` color tags, back-link to `/page/index.mu`). Drop them into a NomadNet node's `pages/` directory.

Os ficheiros `.mu` usam micron (cabeçalhos `>>>`, tags de cor `F222`, back-link para `/page/index.mu`). Coloca-os na pasta `pages/` de um node NomadNet.

---

## trademarks / marcas

Unofficial. This project is not affiliated with, endorsed by, or sponsored by
Roland Corporation. "Roland", "AIRA", "T-8", "S-1", "P-6", "J-6" and "E-4" are
trademarks of their respective owners and are used here only to describe the
equipment.

Projeto não-oficial. Sem qualquer afiliação, endosso ou patrocínio da Roland
Corporation. "Roland", "AIRA", "T-8", "S-1", "P-6", "J-6" e "E-4" são marcas dos
respetivos detentores e são usadas aqui apenas para descrever o equipamento.

---

## license / licença

[CC BY-SA 4.0](LICENSE) — share and adapt with attribution, keep the same license.
Partilha e adapta com atribuição, mantendo a mesma licença.

---

`walk quietly, ₿ut keep the signal alive`
`₿uilt with love in cooperation with nature`
