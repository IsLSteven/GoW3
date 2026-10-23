# God of War III Remastered para PC (Windows)

Versão para **Windows 10 / 11** do *God of War III Remastered* (PS4), já pronta para usar:
**não precisa instalar nada** (Python e bibliotecas já estão dentro da pasta).

> ⚠️ **Os arquivos do jogo NÃO estão incluídos aqui.** Você precisa ter a sua própria cópia do
> jogo, extraída do seu PS4 (veja o [Passo 2](#passo-2--ter-a-pasta-do-jogo)).
> Este projeto não tem ligação com a Sony Interactive Entertainment nem com a Santa Monica Studio.
> *God of War* é marca registrada da Sony Interactive Entertainment.

---

## 📋 Índice

1. [O que você precisa (requisitos)](#-o-que-você-precisa-requisitos)
2. [Passo a passo para instalar e jogar](#-passo-a-passo-para-instalar-e-jogar)
3. [Das próximas vezes](#-das-próximas-vezes)
4. [Controles](#-controles)
5. [Menu dentro do jogo](#-menu-dentro-do-jogo)
6. [Problemas comuns e soluções](#-problemas-comuns-e-soluções)
7. [Onde ficam meus saves?](#-onde-ficam-meus-saves)
8. [Créditos e licença](#-créditos-e-licença)

---

## ✅ O que você precisa (requisitos)

| Item | Detalhe |
|---|---|
| Sistema | **Windows 10 (versão 1903 ou mais nova) ou Windows 11**, 64 bits |
| Processador | 64 bits com **AVX** (Intel Core de 2011 em diante, AMD FX / Ryzen em diante) |
| Placa de vídeo | Qualquer uma com **Vulkan 1.3** e **driver atualizado** (NVIDIA, AMD ou Intel Arc) |
| Espaço em disco | ~**1 GB** para o programa + o espaço da pasta do jogo + **vários GB** para o *cache de shaders* (cresce com o tempo, pode passar de 20 GB). Veja [como limpar](#-problemas-comuns-e-soluções) |
| O jogo | A pasta do jogo (com `eboot.bin`, `sce_module` e `sce_sys`). Testado: **CUSA01623 (EUA)** e **CUSA01715 (Europa)**, versões 01.00 e **01.02 (recomendada)** |

> 💡 **Como saber se meu computador roda?** Se ele roda jogos 3D razoavelmente recentes, provavelmente roda.
> O mais importante é atualizar o **driver da placa de vídeo** (site da NVIDIA, AMD ou Intel).

---

## 🚀 Passo a passo para instalar e jogar

### Passo 1 — Baixar este programa

1. Nesta página do GitHub, clique no botão verde **`<> Code`**.
2. Clique em **`Download ZIP`**.
   (Ou use direto este link: <https://github.com/IsLSteven/GoW3/archive/refs/heads/main.zip>)
3. Aguarde o download terminar (o arquivo é grande, ~200 MB).

### Passo 2 — Ter a pasta do jogo

O programa **não contém o jogo**. Você precisa de uma pasta com o jogo, que dentro tenha estes itens:

```
📁 CUSA01623   (o nome da pasta pode variar)
 ├── eboot.bin
 ├── 📁 sce_module
 └── 📁 sce_sys
```

Anote **onde** essa pasta está (por exemplo `D:\Jogos\CUSA01623`). Você vai precisar dela no Passo 5.

### Passo 3 — Extrair o ZIP (muito importante!)

1. Clique com o botão direito no arquivo `GoW3-main.zip` baixado → **Extrair tudo…**
2. Escolha uma pasta **curta e simples**, por exemplo: **`C:\Games\GoW3`**
3. Clique em **Extrair**.

> ❌ **Não abra o programa de dentro do ZIP!** Sempre extraia primeiro.
> ❌ Evite pastas protegidas como `Arquivos de Programas` e evite nomes muito longos.

### Passo 4 — Abrir o programa

1. Entre na pasta extraída e dê dois cliques em **`God of War III.exe`**.
2. Se aparecer uma tela azul **"O Windows protegeu seu computador"**:
   1. Clique em **"Mais informações"**
   2. Clique em **"Executar assim mesmo"**

   Isso é normal: o programa não tem assinatura digital paga, por isso o Windows desconfia.
3. Se o antivírus reclamar, é um falso alarme comum nesse tipo de programa. Se precisar, adicione a
   pasta às exceções do antivírus.

### Passo 5 — Escolher a pasta do jogo

1. Na tela inicial (**Home**), clique em **"Choose the game folder"**.
   (Isso leva à página **Game**.)
2. Ao lado de **"Game folder"**, clique em **"Browse…"**.
3. Selecione a pasta onde está o `eboot.bin` (a do Passo 2) e confirme.
4. Volte para a página **Home**. Devem aparecer a capa do jogo e algo como
   *"CUSA01623 · version 01.02"*. Isso significa que deu certo ✔️

### Passo 6 — Jogar!

1. (Opcional) Ajuste as **Quick settings** na tela inicial:
   - **Display mode**: janela, tela cheia sem bordas ou tela cheia
   - **Frame rate limit**: limite de FPS
   - **Render resolution**: resolução (deixe **native** se estiver em dúvida)
   - **Engine frame rate**: 120 FPS (padrão) ou 240 FPS
2. Clique no botão **PLAY**.
3. ⏳ **A primeira vez demora mais** (o programa prepara a imagem do jogo). As próximas são bem
   mais rápidas. Pode ficar uma tela preta ou parada por um tempo: **tenha paciência e não feche**.

Os *patches* (correção de texturas, pular vídeos com o botão X e 120 FPS) já vêm ligados
automaticamente.

---

## 🔁 Das próximas vezes

- Abra **`Play God of War III.exe`**: ele inicia o jogo **direto**, com as configurações salvas.
- Para criar um **atalho na Área de Trabalho**: abra `God of War III.exe` →
  **Advanced → Desktop shortcut**.
- Para jogar pelo **Steam**: *Biblioteca → Adicionar um jogo → Adicionar um jogo que não é da Steam*
  e escolha `Play God of War III.exe`.
- Para **atualizar** o programa: **Advanced → Check for updates**. Seus saves e configurações são mantidos.

---

## 🎮 Controles

Funciona com **controle** (DualSense/PS5, DualShock, Xbox e outros) e **teclado** ao mesmo tempo.
Se você tem um controle, é só ligar no PC (USB ou Bluetooth) **antes** de abrir o jogo.

### Teclado (padrão — dá para mudar na página *Game → Controls* do programa)

| Tecla | Botão do PlayStation |
|---|---|
| **W A S D** | Analógico esquerdo (andar) |
| **Setas** | Analógico direito (câmera) |
| **Espaço** | ✕ (Cross) |
| **Shift esquerdo** | ○ (Circle) |
| **E** | □ (Square) |
| **Q** | △ (Triangle) |
| **1** / **3** | L1 / R1 |
| **R** / **F** | L2 / R2 |
| **Z** / **C** | L3 / R3 |
| **I K J L** | Direcional (setas do controle) |
| **Enter** | Options (pausa) |
| **Backspace** | Menu de pausa (touchpad direito) |
| **Tab** | Modo foto (touchpad esquerdo) |
| **Insert** | Menu do programa (veja abaixo) |

Num controle de Xbox: **View** abre o menu de pausa e **L1 + View** abre o modo foto.

---

## 🧰 Menu dentro do jogo

Durante o jogo, aperte **`Insert`** no teclado (ou **R3 + L2** no controle) para abrir o menu do
programa, com 4 abas (troque de aba com **Q / E** ou **L1 / R1**):

- **Game**: trapaças (vida infinita, magia infinita, Fúria de Esparta, orbes vermelhas máximas…)
  e multiplicadores de orbes e de dano.
- **Image**: modo de tela, VSync e nitidez.
- **Performance**: limite de FPS, resolução, FPS do motor do jogo.
- **Overlay**: contador de FPS e uso de GPU/CPU/RAM na tela.

---

## 🛠️ Problemas comuns e soluções

| Problema | O que fazer |
|---|---|
| **"O Windows protegeu seu computador"** | Clique em *Mais informações* → *Executar assim mesmo*. É normal. |
| **O Windows/antivírus apagou ou bloqueou arquivos** | Adicione a pasta do jogo às exceções do antivírus e extraia o ZIP de novo. |
| **Não acho o botão "Choose the game folder"** | Abra a página **Game** no menu lateral e use **Browse…** ao lado de *Game folder*. |
| **Tela preta ao iniciar** | No programa: **Advanced → Clear shader cache** e tente de novo. Na primeira vez a tela preta pode durar um pouco: espere. |
| **O jogo não abre / fecha sozinho** | Abra a página **Log** (ou *Advanced → Log*) do programa e veja a mensagem. O arquivo `user\last_run.log` guarda o registro completo. |
| **Mensagem `STOP: this CPU lacks`** no log | Seu processador é muito antigo (sem AVX). Não dá para rodar neste PC. |
| **Está travando / pouco FPS** | Atualize o driver da placa de vídeo. Diminua **Render resolution** ou o **Engine frame rate** (120 → 60 FPS) em *Performance*. |
| **Disco ficando cheio** | O *cache de shaders* (`user\cache`) cresce com o tempo. Use **Advanced → Clear shader cache** para liberar espaço (o jogo apenas demora um pouco mais para recompilar). |
| **Texturas estranhas em resoluções diferentes de 1080p** | É um problema conhecido do projeto. Use resolução **native** em 1080p. |
| **MSI Afterburner / RTSS / ReShade não aparecem** | Eles devem apontar para **`bin\gow3-probe.exe`** (e não para o launcher). No ReShade escolha **Vulkan**. |

Se nada funcionar, abra uma *Issue* aqui no GitHub e anexe o arquivo `user\last_run.log`.

---

## 💾 Onde ficam meus saves?

Tudo que é seu fica na pasta **`user`**, criada automaticamente ao lado do `God of War III.exe`:

- **Saves:** `user\savedata\1\CUSA01623\`
- **Cache de shaders e log:** `user\`
- **Configurações:** `gow3.ini` (ao lado do `.exe`) e `%APPDATA%\gow3-launcher`
- Arquivos gerados pelo programa: pasta `out\`

O programa **faz backup dos saves automaticamente** antes de cada início do jogo.

> ⚠️ Ao atualizar o programa, **mantenha a pasta `user`** para não perder o progresso.

**Saves do shadPS4** (emulador de PS4) são compatíveis; saves do RPCS3 (PS3) **não são**.
Copie as pastas dos slots para `user\savedata\1\CUSA01623\`. Detalhes completos (em inglês) em
<https://github.com/FelipePrado0/gow3_pc#importing-shadps4-saves>.

---

## 📁 O que tem nesta pasta?

| Item | Para que serve |
|---|---|
| `God of War III.exe` | **Programa principal** (launcher): configurações e botão PLAY |
| `Play God of War III.exe` | Inicia o jogo direto, com as configurações salvas |
| `bin/` | Motor do jogo (runtime, vídeo/áudio, bibliotecas) |
| `_internal/` | Python e bibliotecas do launcher (não mexa) |
| `launcher/` | Ícones e fonte do launcher |
| `patches/` | Patches aplicados em memória (não alteram os arquivos do jogo) |
| `scripts/`, `run.py` | Preparação do jogo na primeira execução |
| `README-Windows.txt` | Resumo original em inglês |
| `LICENSE` | Licença (GNU GPL v2 ou superior) |

---

## 🙏 Créditos e licença

Este é um pacote pronto do projeto **[gow3_pc](https://github.com/FelipePrado0/gow3_pc)** de
**Felipe Prado** (versão para Windows), que por sua vez é derivado de:

- **deadinside28** — [bloodborne_pc](https://github.com/deadinside28/bloodborne_pc), o port nativo original
- **Supermedo** — [bloodborne_pc para Windows](https://github.com/Supermedo/bloodborne_pc)
- **cuesta4** — [shadPS4 (branch `eltutz`)](https://github.com/cuesta4/shadPS4/tree/eltutz), correções de renderização para God of War III
- **Equipe do [shadPS4](https://github.com/shadps4-emu/shadPS4)** — núcleo de vídeo (tradução para Vulkan)
- **kvicken, cuesta4, illusion0001** — patches de resolução, textura, 120 FPS e pular vídeos
- Também usa: FFmpeg, SDL3, Dear ImGui, LibAtrac9, entre outros

Licença: **GNU GPL v2 ou posterior** (veja [`LICENSE`](LICENSE)). Componentes de terceiros mantêm suas
próprias licenças. O código-fonte completo está no projeto original:
<https://github.com/FelipePrado0/gow3_pc>

Para uso apenas com **cópia própria e legítima do jogo**.
