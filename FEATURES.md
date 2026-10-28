# 🎮 Guia do Jogador

Um servidor de sobrevivência com progressão própria: suba do **nível 1 ao 60**, descubra o mundo pelo **Codex** e evolua suas habilidades.

---

## 📈 Progressão

### Jornada de níveis — 1 → 60

Todos os jogadores seguem a mesma jornada. Os primeiros níveis sobem rápido; os últimos pedem mais tempo.

**Como ganhar XP:**
- **Jogando** — XP a cada 5 minutos.
- **Caçando** — quanto mais forte o mob, maior a recompensa.
- **Minerando** — minérios mais raros dão mais XP.
- **Avanços e descobertas do Codex** — cada um rende XP de jornada.

> 💡 **Três contadores de XP:** a barra verde vanilla, os níveis de habilidade e a jornada 1–60 são separados. Recompensas do Codex e dos avanços alimentam a **jornada**.

**Recompensas por nível:**

| Nível | O que você recebe |
|---|---|
| 5 | 2× Maçã Dourada |
| 10 | 3× Maçã Dourada + 1× Diamante + acesso ao **Nether** |
| 15 | 8× Esmeralda |
| 20 | 3× Diamante + 16× Salmão Assado |
| 25 | Regeneração I (90s) + Velocidade II (2 min) |
| 30 | 4× Diamante + 12× Garrafas de XP + acesso ao **End** |
| 35 | 6× Maçã Dourada + Força II (2 min) |
| 40 | 6× Diamante + 24× Garrafas de XP |
| 45 | 8× Maçã Dourada + 16× Lapis-lazúli |
| 50 | 6× Diamante + **Totem da Imortalidade** |
| 55 | 8× Diamante + 2× Carapaça de Shulker |
| 60 | 10× Diamante + 8× Maçã Dourada + 4× Sucata de Netherite — nível máximo, com celebração global 🎉 |

- **Todo nível** cura e enche sua fome por completo, além de mostrar o aviso de subida.

### Codex — o compêndio de descobertas 📖

Abra com **`/codex`**. Cada descoberta desbloqueia uma página de lore permanente e rende **XP**. Ao encontrar algo novo, aparece o banner **“CÓDICE ATUALIZADO”**.

| Categoria | O que reúne | Por descoberta | Ao completar |
|---|---|---|---|
| 🟣 Monstros | 33 inimigos hostis | +100 XP | +5000 XP |
| 🟢 Vida Selvagem | 37 animais e criaturas | +100 XP | +4000 XP |
| 🔴 Lendas & Monstruosidades | 9 bosses e criaturas lendárias | +1000 XP | +15000 XP + **Totem** |
| 🌿 Biomas | 48 paisagens do Overworld | +5 XP | +1000 XP |
| 🌌 Biomas Exóticos | 19 terras raras, Nether, End e Vazio | +10 XP | +800 XP |
| 💎 Relíquias | 24 itens difíceis de obter | +80 XP | +1500 XP |
| 🐺 Domesticação | 11 animais domáveis e montarias | +100 XP | +1000 XP |
| 🎵 Música | 19 discos | +50 XP | +1000 XP |
| 🏺 Arqueologia | 42 fragmentos e moldes | +30 XP | +1200 XP |
| 🧪 Alquimia | 20 efeitos e poções especiais | +40 XP | +1000 XP |
| ⚔️ Mestres mcMMO | 17 habilidades no nível 100 | +150 XP | +2000 XP |
| ⏳ Tempo de Casa | 6 marcos, de 1 a 100 horas | +80 XP | +800 XP |
| 🎣 Pescaria | 10 peixes e tesouros fisgados | +50 XP | +1000 XP |

- Descobertas ainda bloqueadas aparecem como `??`.
- Desbloqueie derrotando mobs, domesticando animais, visitando biomas, obtendo itens, preparando poções, subindo habilidades, acumulando tempo de jogo e pescando.

### Habilidades ⚔️

- **Nível 300 é o máximo** em todas as habilidades, alcançado apenas jogando.
- Cada habilidade tem seu próprio **nível**.
- Veja o progresso de cada uma com **`/fishing`**, **`/mining`**, **`/swords`**…

### Conquistas — XP por avançar 🏆

Cada conquista rende XP automaticamente, uma única vez por jogador:

| Tipo | XP |
|---|---|
| História | 25 |
| Aventura | 30 |
| Agricultura e animais | 30 |
| Nether | 40 |
| Fim | 60 |
| Desafios especiais | 80–300 |

- O chat mostra `[+N XP] Conquista desbloqueada: Nome da Conquista`.

---

## 🏡 Base e itens

### Proteção de bases 🏠

- Reivindique o chunk onde está com **`/c`**. Os chunks da base precisam se tocar.
- Limites: **20 chunks**, **2 regiões** e **10 membros** por base.
- A base começa com **24 horas** de energia para você construir a powercell. Sem ela, a energia cai e a base acaba dissolvida.
- **Powercell:** monte a receita no centro de um **baú único** (não duplo) dentro da base e feche o baú.

```text
┌───┬───┬───┐
│ F │ D │ F │     F = Ferro (5)
├───┼───┼───┤     D = Diamante (4)
│ D │ F │ D │
├───┼───┼───┤
│ F │ D │ F │
└───┴───┴───┘
```

| Combustível | Energia |
|---|---|
| Diamante | 48 h |
| Ouro | 8 h |
| Ferro | 6 h |
| Carvão | 3 h |
| Cobre | 2 h |

- O consumo cresce com o número de chunks da base.
- Ficar sem energia por muito tempo dissolve a base.
- Permissões separadas para **dono, membro e visitante**: quebrar, colocar, interagir, PVP, redstone, portas, trocas, mobs, fogo, TNT, voo e mais.
- Convide, aceite, expulse, bana e desbane jogadores; tranque a base, renomeie e veja as bordas com `/c show`.
- A base tem **auditoria** de ações (limpeza após 30 dias) e uma **bossbar** com nome e energia ao entrar.

### Mochilas 🎒

Uma mochila com **27 slots**. Segure e clique com o botão direito para abrir. A receita é aprendida automaticamente ao entrar no servidor.

```text
┌───┬───┬───┐
│ C │ P │ C │     C = Couro (5)
├───┼───┼───┤     P = Pau (1)
│ L │ B │ L │     L = Laço (2)
├───┼───┼───┤     B = Baú (1)
│ C │ C │ C │
└───┴───┴───┘
```

### Waystones 🪨

Pedras de teleporte craftáveis, com aparência de pedra de âncora.

```text
┌───┬───┬───┐
│ O │ P │ O │     O = Obsidiana (4)
├───┼───┼───┤     P = Pérola do Ender (4)
│ P │ C │ P │     C = Bússola (1)
├───┼───┼───┤
│ O │ P │ O │
└───┴───┴───┘
```

- Clique com o direito para abrir o menu de destinos e viajar.
- Nomeie com `/tw setname <nome>`.
- Cada waystone é sua por padrão; `/tw setpublic true` a libera para todos.
- Podem ser quebradas e levadas para outro lugar.

### Bússola de Explorador 🧭

Localiza estruturas do mundo. Botão direito vai para o **próximo** alvo; botão esquerdo, para o **anterior**. A agulha aponta para o alvo e as coordenadas aparecem no chat. Há **2,5s** entre os cliques.

```text
┌───┬───┬───┐
│ P │ P │ P │     P = Papel (6)
├───┼───┼───┤     L = Lingote de Ouro (2)
│ L │ S │ L │     S = Luneta (1)
├───┼───┼───┤     B = Bússola (1)
│ P │ B │ P │
└───┴───┴───┘
```

**Alvos (9):** Vila, Cidade Antiga, Câmaras de Prova, Pirâmide do Deserto, Mansão, Cabana da Bruxa, Posto de Saqueador, Fortaleza e Cavernas Grandes. A receita é aprendida automaticamente.

---

## ⚰️ Túmulos

Ao morrer, seus itens e **70% do XP** ficam num túmulo no local da morte, em vez de espalhados pelo chão.

- O túmulo é uma **cabeça de jogador** com holograma do dono, tempo restante, causa da morte e proteção.
- **Duração:** 3 horas. Depois, o conteúdo cai no chão.
- **Limite:** 18 túmulos por jogador.
- **Local seguro:** se morrer no ar, na lava, no void ou dentro de um bloco, o túmulo vai para o último lugar seguro.
- **Proteção:** nos primeiros **5 minutos**, só você e quem te matou podem abrir. Depois, qualquer um.
- **Não explode** com TNT ou creepers. Pode ser quebrado com a mão; quem quebrar leva o conteúdo.
- Ao renascer, você recebe uma **bússola** que aponta para o túmulo mais próximo por 5 minutos.
- **`/graves`** lista seus túmulos.
- O túmulo guarda um **livro** com nome, causa da morte, data, itens, XP e coordenadas. O layout do inventário e a armadura são preservados.
- Se o túmulo não puder ser criado, você mantém o inventário.

---

## ⚔️ Combate e PvP

- **Dragão do End escalado** 🐉 — vida, dano e resistência crescem com o número de jogadores. Ele usa raios, sopro e bolas de fogo, e as recompensas são divididas pelo dano causado. **Cristais do End explodem com mais força e causam fogo**.
- **PvP opt-in** — começa **desligado**. Use **`/pvp`** para ligar ou desligar. Sem PvP, você não dá nem recebe dano de jogadores (leva knockback), e animais domados, fogo/lava próximos e efeitos hostis também são protegidos. Após entrar em combate, são **30s** para poder alternar. Sair do jogo durante o combate não mata seu personagem.
- **Ovos de spawn** — 2% de chance ao derrotar um mob, inclusive os de spawners.
- **Recompensas por trim** — conjuntos completos com o mesmo padrão dão efeitos passivos (2, 3 e 4 peças; set completo vira “Ascended”). Misturar padrões pode gerar penalidades.
- **Cabeças de mobs** — chance de cair ao derrotar; Looting aumenta a chance. Também dá para fazer mini-blocos na pedra de corte ou comprar do vendedor ambulante.

---

## 🌍 O mundo

### Mundo Terraformado

O mundo principal usa geração personalizada de terreno, biomas, rios, montanhas, cavernas e estruturas próprias.

- **40+ biomas**, incluindo montanhas pintadas, savanas fragmentadas, florestas escarlates, cerejeiras, taigas, manguezais e vários oceanos.
- **Estruturas próprias:** vilas, postos de saqueador, pirâmides, monumentos oceânicos, mansões, fortes, cidades antigas, câmaras de prova, catacumbas, minas, ruínas, naufrágios, iglus, poços do deserto e acampamentos abandonados.
- **Cavernas especiais:** grandes, exuberantes (lush) e de cogumelos.

### Dimensões

| Dimensão | Abre no nível |
|---|---|
| 🌋 Nether | 10 |
| 🔮 End | 30 — Cidades do End e elytras |
| 🌀 Sift *(em breve)* | 60 |

O portal avisa o nível necessário.

### Mapa e conexão

- **Mapa 3D no navegador:** `http://<ip-do-servidor>:8100`.
- **Voxy:** clientes com o mod recebem terreno distante do servidor (até 512 chunks no Overworld e no End, 64 no Nether).

### Tesouros e recompensas do mundo

- **Baús de tesouro** surgem perto de jogadores ativos a cada **15–30 minutos**, entre 12 e 30 blocos. Cada jogador tem **1 por vez**, e o baú dura **5 minutos**.
- São **4 raridades** (Comum, Rara, Lendária e Mítica) e os primeiros **60 segundos** são só seus.
- **10% são mimics:** alguns entregam o loot, outros se disfarçam de raridade melhor. Vencer um mimic dobra o loot e dá **40 XP**; se ele fugir em 60s, você perde o restante. O loot sai aos poucos conforme você causa dano.
- **Recompensas de pesca:** ao pescar, há chance de um baú-recompensa com animação, do comum ao **Leviatã**, com itens, XP e surpresas.
- **Cofres das Cidades do End** garantem elytra para mais de um jogador.

---

## ✨ Qualidade de vida

### 🌱 Agricultura

- Colher plantações maduras dá XP; plantações continuam crescendo **offline**.
- Pisotear terra arada **não destrói** mais a plantação.
- **Farinha de osso** acelera **cacto**, **nether wart** e **cana-de-açúcar**.
- **Enxadas replantam** a cultura na hora da colheita.
- No **composter**, agache e clique com o direito para processar **tudo de uma vez**.
- Receitas veganas permitem craftar couro, penas, slime, canas de blaze, pólvora e mais sem matar mobs passivos.

### 🛠️ Equipamentos e encantamentos

- **Bigornas sem “Muito Caro!”** — o limite de 40 níveis não existe; o custo real de XP é exibido e cobrado.
- **Cores em bigornas e placas** — use `&`, hex (`#55ffff`) e gradientes (`<gradient:red:gold>`) ao renomear ou escrever.
- **Pedra de amolar** remove a Maldição do Vínculo e a Maldição do Desaparecimento.
- **Recuperação de Encantamentos** — permite **guardar encantamentos de itens em livros** usando a pedra de amolar.
- **Arco Infinito** dispara mesmo sem flechas no inventário.
- **Totem da Imortalidade** funciona de qualquer slot do inventário.
- **Tesouras** têm 50% de chance de desarmar TNT acesa; correr com tesouras não machuca.
- **Spawners** podem ser minerados com Toque Suave usando picareta de ferro ou melhor.
- **Encantamento Escavador** — picaretas com ele abrem um túnel de minérios e pedra em uma ação.

### 🔥 Blocos e utilidades

- **Forno em cima de lava** funciona sem combustível — a fonte de lava embaixo é consumida.
- **Redstone desliga spawners.**
- **Pedra de corte** machuca quem pisa nela: **1 coração** por passo.
- **Mesa de encantamentos** mantém o lápis-lazúli entre usos e devolve o que sobrou se a mesa for quebrada.
- **Beacons** funcionam através de vidro tingido.
- **Baú do End (ender chest)** tem **6 fileiras**.
- É possível colocar **água no End** com baldes.
- **Lava e água infinitas** com apenas 2 fontes.
- **Mineração em cadeia** — agache e quebre com a ferramenta certa para derrubar a veia inteira (picareta→minério, machado→madeira, pá→terra, enxada→planta).
- **Pedreira expandida** — mais de 500 receitas: cortes de madeira, pedra, reciclagem e “un-crafting”.
- **Luz dinâmica** — tochas e lanternas na mão iluminam ao redor.
- **Fogueiras curam** lentamente num raio de 3 blocos.
- **Decaimento de folhas** — ao cortar uma árvore, as folhas somem em segundos, com drops.
- **Votação de sono** — deitar na cama inicia uma votação com bossbar; metade dos jogadores pula a noite. Tempestades também podem ser puladas.
- **Hologramas de itens** em baús, fornos e barris; ative ou desative com **`/iv`**.
- **Bússola na mão** mostra uma bossbar com a direção.
- **Bolas de neve** apagam fogo, velas e fogueiras.
- **Mobs que pegaram itens** voltam a despawnar normalmente.
- **Aldeões** seguem você quando segura um bloco de esmeralda; trocas podem ser **rerroladas** na tela de troca.
- **Cavalgar golfinhos** e **dirigir carrinhos** com W/A/S/D (o carrinho sobe degraus de 1 bloco). Entre os mobs montáveis, filhotes e animais ainda não domados também podem ser montados.
- **O dia dura mais** e as noites passam mais rápido; a barra de ar debaixo d'água é maior.
- **Vindicators Johnny** — 5% perseguem o jogador continuamente 🪓.
- **Mensagens de morte exclusivas**, como escorregar nas próprias tesouras ou se serrar ao meio.
- **Comer até encher** causa um arroto 🫧.
- **Poses e emotes** — sentar, deitar, rastejar, abraçar, acenar e mais. Skins personalizadas e sprays de imagens também estão disponíveis.

---

## 🧾 Comandos essenciais

| Comando | Para quê |
|---|---|
| `/codex` | compêndio de descobertas |
| `/fishing` | progresso da habilidade (ou `/mining`, `/swords`…) |
| `/c` | proteção de bases |
| `/graves` | seus túmulos e teleporte |
| `/pvp` | liga/desliga o PvP |
| `/sb` | scoreboard liga/desliga |
| `/help` | lista completa de comandos |

Bom jogo. 🎉
