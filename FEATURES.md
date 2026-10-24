# 🎮 Bem-vindo ao Servidor do ayuwooh — Guia do Jogador

Este é um servidor de sobrevivência com progressão personalizada, compêndio de lore e mecânicas adicionais na jogabilidade. Este guia lista tudo que está disponível.

---

## 🗡️ Os Três Grandes

### 1. Jornada de Níveis — suba até o nível 60

Todos os jogadores seguem a **mesma jornada**: nível **1 → 60**. Os primeiros níveis avançam rapidamente; os últimos exigem mais tempo.

**Como você ganha XP de nível:**
- **Jogar** (+XP a cada poucos minutos)
- **Caçando monstros** — quanto maior o monstro, maior a recompensa:
  - Mobs comuns ≈ 2–5 XP
  - Warden 60–80 · Wither 40–50 · Guardião Ancestral 20–30 · Invocador 12–18
  - **Dragão do Fim 80–100** — a maior recompensa 💰
- **Minerando** — minérios pagam XP extra:
  - Sucata Antiga 30–50 · Diamantes & Esmeraldas 15–25 · Obsidiana 15–25
  - Ferro, ouro, redstone, quartzo, carvão, cobre, lapis-lazúli — valores menores
  - Terra, cascalho e pedregulho não pagam XP

**Recompensas por nível** (além de uma recompensa em *todo* nível de subida):

| Nível | O que você recebe |
|---|---|
| 5 | 2× Maçã Dourada |
| 10 | 3× Maçã Dourada + 1× Diamante + primeiro **capítulo da Crônica** 📖 |
| 15 | 8× Esmeralda |
| 20 | 3× Diamante + 16× Salmão Assado + segunda **Crônica** 📖 |
| 25 | buffs: Regeneração I (90s) + Velocidade II (2 min) |
| 30 | 4× Diamante + 12× Garrafas de XP + terceira **Crônica** 📖 |
| 35 | 6× Maçã Dourada + Força II (2 min) |
| 40 | 6× Diamante + 24× Garrafas de XP + quarta **Crônica** 📖 |
| 45 | 8× Maçã Dourada + 16× Lapis-lazúli |
| 50 | 6× Diamante + **1× Totem da Imortalidade** + quinta **Crônica** 📖 — agora você é um *Veterano* |
| 55 | 8× Diamante + 2× Carapaça de Shulker |
| 60 | 10× Diamante + 8× Maçã Dourada + 4× Sucata de Netherite + última **Crônica** 📖 — nível máximo, com celebração global no servidor 🎉 |

Consulte seu nível, ranking e progresso com **`/clv`**.

### 2. Codex — o compêndio de descobertas 📖

Abra com **`/codex`** — seu livro de monstros e fauna, com a lore de cada coisa que você descobriu.

- **Derrote um mob** e o banner *"CODEX UPDATED"* aparece na tela; a página de lore correspondente fica desbloqueada permanentemente.
- 4 categorias:
  - 🟣 **Monstros** (21) — inimigos hostis
  - 🟢 **Vida Selvagem** (21) — animais passivos e criaturas dos biomas
  - 🔴 **Lendas & Monstruosidades** (7) — Dragão, Wither, Warden e criaturas lendárias
  - 📜 **Crônicas** (6) — a história do próprio servidor, um capítulo desbloqueado a cada marco de nível (10/20/30/40/50/60)
- Recompensas: **XP vanilla** por descoberta e **bônus grandes** ao completar uma categoria:
  - Monstros e Vida Selvagem: +100 XP por descoberta, +5000 XP por categoria completa
  - Lendas: +1000 XP por boss, +15000 XP por categoria completa **e um Totem**
  - Crônicas: +300 XP por capítulo, 64 garrafas de XP ao completar as 6
- Entradas bloqueadas aparecem como `??` até serem desbloqueadas.

> 💡 **Atenção:** neste servidor existem três contadores de XP — sua **barra verde de XP** (vanilla), os **níveis de habilidade do mcMMO** e o seu **nível 1–60 da jornada**. Eles não se misturam. As recompensas do Codex só enchem a barra verde.

### 3. mcMMO — sistema de habilidades ⚔️

Melhore habilidades jogando; cada uma desbloqueia sub-habilidades. Consulte qualquer uma com **`/mcmmo`**, ou uma página específica, como `/mining`, `/swords`, `/fishing`.

- **Nível 300 é o máximo** em todas as habilidades, alcançado apenas jogando (sem atalhos).
- Ritmo planejado: **Fishing** e as **habilidades de combate** sobem um pouco mais rápido, **Acrobatics** é mais lenta, e Mining/Woodcutting/Herbalism/Excavation ficam no meio.
- **Repair e Salvage estão desativados**: o reparo de itens funciona normalmente pela bigorna; essas duas habilidades não existem neste servidor.
- Toda habilidade mostra a própria **barra de XP (bossbar)** conforme você evolui.

---

## 🪨 Waystones

Pedras de teleporte que você constrói, nomeia e usa para viajar instantaneamente. O bloco aparece como uma **pedra de âncora** (lodestone).

**Como craftar** (mesa de crafting 3×3):

```text
┌───┬───┬───┐
│ O │ P │ O │     O = Obsidian (4)
├───┼───┼───┤     P = Pérola do Ender (4)
│ P │ C │ P │     C = Bússola (1)
├───┼───┼───┤
│ O │ P │ O │
└───┴───┴───┘
```

Dá pra conseguir tudo cedo: obsidian com lava e água, pérolas de Endermen ou trocando com clérigos, e a bússola com ferro e sucata — sem precisar do Nether.

**Como usar:**
- **Nomeie** cada waystone com `/tw setname <nome>`.
- Abra o **menu de viagem** com `/tw openui` e escolha o destino; `/tw list` mostra suas waystones.
- Por padrão, cada waystone é **sua** — com `/tw setpublic true` ela fica visível e usável por todos os jogadores.
- Waystones podem ser **quebradas e levadas** para recolocar em outro lugar.

---

## 🌀 Desbloqueio de Dimensões

As dimensões do servidor abrem conforme sua **jornada de níveis** — o portal não te deixa passar antes da hora.

| Dimensão | Abre no nível |
|---|---|
| 🌋 **Nether** | nível **10** |
| 🔮 **End** | nível **30** — é lá que ficam as Cidades do End e as elytras |
| 🌀 **Sift** *(em breve)* | nível **60** |

- Ao tocar o portal sem o nível necessário, aparece uma mensagem mostrando o nível exigido.
- O exigido é o **nível da jornada 1–60** (`/clv`), não a barra de XP vanilla.
- A **Sift** é a nova dimensão do jogo: quando for lançada, ela será desbloqueada no **nível 60** — direto no máximo da jornada.

---

## 🖥️ Você, na Tela

- **Lista de players e nome sobre a cabeça:** seu nível entre colchetes — `[42] ayuwooh`.
- **Dimensão no tab:** depois do nível, a inicial da dimensão entre colchetes e colorida — `[12] [O] ayuwooh`: **O** verde (Overworld), **N** vermelha (Nether), **E** roxa (End).
- **Tab ordenado por nível** — do nível mais alto para o mais baixo; empates em ordem alfabética.
- **Scoreboard lateral** (aparece ao entrar) — **alterna a cada 15s** entre dois painéis para não poluir a tela:
  - **Painel de Progresso**: seu nickname, `Nível: 42`, uma **barra de progresso de XP** ao vivo com o **%** ao lado e seu **tempo total de jogo**
  - **Painel de Habilidades**: Power Level no topo e o nível de cada habilidade (mineração, madeira, ervas, escavação, pesca, espadas, machados, arqueia, acrobática e doma)
  - Ativa/desativa com **`/sb`** — sua escolha fica salva entre sessões.
- **Embaixo do seu nome no tab:** um coração vermelho com sua vida ❤️

---

## 🛋️ Comandos disponíveis

| Comando | O que faz |
|---|---|
| `/sit` | senta em qualquer lugar (clicar com o direito em degraus/escadas também serve) |
| `/lay` | deita no chão |
| `/legsup` | senta com as pernas para cima |
| `/bellyflop` | salto de barriga 🤸 |
| `/spin` | gira no lugar |
| `/crawl` | rasteja de barriga |
| `/playtime` (`/pt`) | suas horas totais de jogo (e `/pt top` para o placar) |
| `/skin` | `/skin set <nome>` ou `/skin url <link>` — troca de skin em servidor offline |
| `/ping`, `/tps` | seu ping e o estado do servidor |
| `/iv` | ativa/desativa os hologramas de itens nos blocos interativos |
| `/tw` | menu de waystones — viaje entre waystones construídas por você ou que são públicas |
| `/hug`, `/wave`, `/slap` | emotes — interações rápidas com outros jogadores |
| `/sprays upload <link>`, `/spray` | envia uma imagem e espareja-a na parede |

---

## ✨ Recursos do Mundo

- **Minera spawners com Toque Suave** ⛏️ — picareta de ferro ou melhor. O spawner é coletado como item em vez de ser destruído.
- **Mineração em cadeia** — quebre mantendo-se agachado com a ferramenta correta e a veia inteira quebra junto (picareta→minério, machado→madeira, pá→terra, enxada→planta).
- **Cavalgar golfinhos** 🐬 — clique com o direito em um golfinho para montá-lo e conduzi-lo; ele precisa voltar à água.
- **Compass bossbar** — segurando uma bússola aparece uma barra com a direção ao vivo.
- **Totem da Imortalidade** — salva você com o item em *qualquer parte* do inventário, não apenas na mão.
- **Beacons com vidro tingido** — vidro tingido não bloqueia os efeitos do beacon.
- **Anvils sem "Muito Caro!"** 🛠️ — o limite de 40 níveis não existe mais: reparos e encantamentos caros continuam disponíveis, com o custo real de XP exibido e cobrado. Ao renomear, códigos de cor `&`, hex (`#55ffff`) e gradientes (`<gradient:red:gold>`) funcionam.
- **Arroto ao encher a fome** 🫧 — comer até o máximo da fome causa um arroto.
- **Bolas de neve apagam fogo** — apagam fogueiras, velas e chamas ao acertar.
- **O dia demora mais** — as fases de dia se prolongam um pouco, e as noites passam mais rápido.
- **Vindicators Johnny** — uma pequena % dos vindicators é chamada de Johnny e persegue o jogador continuamente 🪓.
- **Mais tempo debaixo d'água** — a barra de ar é maior antes de o dano começar.
- **Cofres nas Cidades do End** — os cofres dos navios garantem elytra para mais de um jogador.
- **Baú do End com 6 fileiras** 🧰 — o dobro de espaço no baú do End (6 fileiras em vez de 3).
- **Votação de sono** 🛏️ — deitar na cama à noite inicia uma votação para pular a noite (bossbar com progresso e sons); sair da cama cancela o voto. Com metade dos jogadores votando, a madrugada é pulada com uma animação de amanhecer ✨. Tempestades também podem ser puladas por voto.
- **Decaimento de folhas** 🍃 — ao cortar uma árvore, as folhas decaem sozinhas em segundos, mantendo a paisagem limpa (drops incluídos).
- **Encantamento Escavador** ⛏️ — picaretas com esse encantamento quebram um túnel de minérios e pedra em uma única ação. Disponível na mesa de encantamentos.
- **Luz dinâmica** ✨ — segurar tochas e lanternas ilumina o ambiente ao redor; ao guardar o item, a luz apaga.
- **Fogueiras curam** 🔥 — ficar perto de uma fogueira acesa regenera vida lentamente (meia vida a cada 2 s, raio de 3 blocos).
- **Proteção de baús e contêineres** 🔒 — agachado (shift), clique com o direito no baú para abrir o menu de proteção: tranque para os outros e escolha quem pode abrir.
- **Recompensas de pesca** 🎣 — ao pescar, há chance de cair um baú-recompensa com animação: cinco tipos do comum ao Leviatã, com itens, XP e algumas surpresas.
- **XP ao colher** 🌱 — colher plantações maduras gera XP (configurável para valer apenas em plantações naturais e completamente maduras).
- **Cabeças de mobs** 💀 — chance de a cabeça do mob cair ao derrotá-lo (Looting aumenta a chance); use a cabeça como decoração.
- **Plantações crescem offline** 🌾 — as plantações continuam crescendo mesmo com o chunk descarregado e sem ninguém por perto.
- **Pedreira expandida** 🪚 — a pedreira ganhou 500+ receitas: corte de qualquer peça da família da madeira (toras, tábuas, cercas, portas, placas…), receitas extras de pedra, reciclagem e "un-crafting".
- **Receitas veganas** 🌿 — couro, penas, blocos de slime, canas de blaze, pólvora e mais são craftados com ingredientes veganos, sem sacrificar mobs passivos.
- **Plantações a prova de pisão** 🌱 — pisotear a terra arada não a destrói mais; correr ou cair sobre a plantação é seguro.
- **Placas com cor** 🪧 — placas aceitam códigos de cor `&` ao escrever nelas.
- **Carrinhos guiáveis** 🛤️ — sentado em um carrinho de minério, dirija-o com W/A/S/D; ele sobe degraus de 1 bloco.
- **Arco Infinito sem flechas** 🏹 — com o encantamento Infinito, dispare mesmo sem nenhuma flecha no inventário.
- **Tesouras desarmam TNT** ✂️ — um golpe de tesoura na TNT acesa tem 50% de chance de desarmá-la.
- **Mensagens de morte exclusivas** 💀 — certas mortes aparecem com frases próprias, como escorregar e cair nas próprias tesouras.

---

Bom jogo.
