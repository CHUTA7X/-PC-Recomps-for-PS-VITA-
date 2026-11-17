# 🎮 PC Recomps for PS Vita

🇪🇸 [Español](#-español) · 🇬🇧 [English](#-english) · 🇧🇷 [Português](#-português)

---

## 🇪🇸 Español

### 🔁 Qué son estas recompilaciones
Este proyecto lleva **juegos de PC a la PS Vita** recompilándolos para que funcionen de forma nativa en la consola. No es un emulador: cada juego se convierte en un **eboot propio para Vita**, con los gráficos traducidos a la GPU de la consola mediante **vitaGL**.

⚠️ **No se distribuye ningún archivo de los juegos.** Cada recompilación solo incluye el programa (el `.vpk`); los datos los pones tú desde **tu propia copia de PC**.

### 🕹️ Juegos disponibles

| Juego | Versión | Carpeta `<juego>` |
|---|---|---|
| 🏍️ *MX vs. ATV Unleashed* | v1.00 | `mxvsatv` |

### 🧭 Cómo funciona (lo común a todos los juegos)
Todas las recompilaciones siguen el mismo esquema, así que si ya instalaste una, las demás se instalan igual:

1. 💿 **Instala el juego en un PC** con tu copia original.
2. 📁 **Copia la carpeta de instalación** a la Vita, dentro de:
   ```
   ux0:data/<juego>/app/
   ```
   (el nombre de `<juego>` está en la tabla de juegos disponibles).
3. 📲 **Instala el `.vpk`** del juego con VitaShell.
4. 🧩 Asegúrate de tener **`libshacccg.suprx`** en `ur0:data/` (el mismo que piden otros ports).

Cada juego usa siempre las mismas subcarpetas dentro de `ux0:data/<juego>/`:

| Carpeta | Para qué sirve |
|---|---|
| 📂 `app/` | Los archivos originales del juego (los copias tú). |
| 💾 `escritura/` | Partidas guardadas y configuración. |
| 🐞 `registro/` | Registros (`arranque.log`) para reportar fallos. |

### 📝 Qué esperar
- ⏳ **Primera partida con tirones:** los shaders se compilan en la consola la primera vez y se guardan; a partir de la segunda vez el juego va fluido.
- 🎛️ **Opciones adaptadas a la Vita:** algunas opciones de PC (vídeo, multijugador, efectos muy pesados como sombras dinámicas) pueden venir desactivadas para mantener el rendimiento. Cada juego indica cuáles.
- 🎮 **Controles nativos:** se juega con los controles de la Vita, sin teclado ni ratón.

### 🐞 Reportar problemas
Abre un *issue* indicando el juego, la versión del `.vpk` y adjunta el archivo `ux0:data/<juego>/registro/arranque.log`.

---

## 🇬🇧 English

### 🔁 What these recompilations are
This project brings **PC games to the PS Vita** by recompiling them so they run natively on the console. It is not an emulator: each game becomes its **own Vita eboot**, with its graphics translated to the console's GPU through **vitaGL**.

⚠️ **No game files are distributed.** Each recomp only includes the program (the `.vpk`); you provide the data from **your own PC copy**.

### 🕹️ Available games

| Game | Version | `<game>` folder |
|---|---|---|
| 🏍️ *MX vs. ATV Unleashed* | v1.00 | `mxvsatv` |

### 🧭 How it works (common to every game)
Every recomp follows the same layout, so once you have installed one, the rest install the same way:

1. 💿 **Install the game on a PC** with your original copy.
2. 📁 **Copy the install folder** to the Vita, into:
   ```
   ux0:data/<game>/app/
   ```
   (the `<game>` name is listed in the available games table).
3. 📲 **Install the game's `.vpk`** with VitaShell.
4. 🧩 Make sure **`libshacccg.suprx`** is in `ur0:data/` (the same one other ports ask for).

Each game always uses the same subfolders inside `ux0:data/<game>/`:

| Folder | Purpose |
|---|---|
| 📂 `app/` | The original game files (you copy them). |
| 💾 `escritura/` | Save games and settings. |
| 🐞 `registro/` | Logs (`arranque.log`) for bug reports. |

### 📝 What to expect
- ⏳ **Stutter on first play:** shaders are compiled on the console the first time and cached; from the second time on the game runs smoothly.
- 🎛️ **Options adapted to the Vita:** some PC options (video, multiplayer, very heavy effects such as dynamic shadows) may be disabled to keep performance up. Each game lists which ones.
- 🎮 **Native controls:** you play with the Vita's controls, no keyboard or mouse.

### 🐞 Reporting problems
Open an *issue* stating the game, the `.vpk` version, and attach `ux0:data/<game>/registro/arranque.log`.

---

## 🇧🇷 Português

### 🔁 O que são estas recompilações
Este projeto leva **jogos de PC para o PS Vita** recompilando-os para rodarem nativamente no console. Não é um emulador: cada jogo vira um **eboot próprio para o Vita**, com os gráficos traduzidos para a GPU do console através do **vitaGL**.

⚠️ **Nenhum arquivo dos jogos é distribuído.** Cada recompilação inclui apenas o programa (o `.vpk`); os dados vêm da **sua própria cópia de PC**.

### 🕹️ Jogos disponíveis

| Jogo | Versão | Pasta `<jogo>` |
|---|---|---|
| 🏍️ *MX vs. ATV Unleashed* | v1.00 | `mxvsatv` |

### 🧭 Como funciona (comum a todos os jogos)
Todas as recompilações seguem o mesmo esquema, então se você já instalou uma, as outras se instalam igual:

1. 💿 **Instale o jogo em um PC** com sua cópia original.
2. 📁 **Copie a pasta de instalação** para o Vita, em:
   ```
   ux0:data/<jogo>/app/
   ```
   (o nome de `<jogo>` está na tabela de jogos disponíveis).
3. 📲 **Instale o `.vpk`** do jogo com o VitaShell.
4. 🧩 Tenha o **`libshacccg.suprx`** em `ur0:data/` (o mesmo que outros ports pedem).

Cada jogo usa sempre as mesmas subpastas dentro de `ux0:data/<jogo>/`:

| Pasta | Para que serve |
|---|---|
| 📂 `app/` | Os arquivos originais do jogo (você copia). |
| 💾 `escritura/` | Saves e configurações. |
| 🐞 `registro/` | Logs (`arranque.log`) para reportar problemas. |

### 📝 O que esperar
- ⏳ **Travadas na primeira vez:** os shaders são compilados no console na primeira vez e ficam salvos; a partir da segunda vez o jogo roda liso.
- 🎛️ **Opções adaptadas ao Vita:** algumas opções de PC (vídeo, multijogador, efeitos muito pesados como sombras dinâmicas) podem vir desativadas para manter o desempenho. Cada jogo indica quais.
- 🎮 **Controles nativos:** joga-se com os controles do Vita, sem teclado nem mouse.

### 🐞 Reportar problemas
Abra uma *issue* informando o jogo, a versão do `.vpk` e anexe `ux0:data/<jogo>/registro/arranque.log`.

---

## 📜 Licencias / Licenses / Licenças

🇪🇸 Las recompilaciones usan bibliotecas libres enlazadas de forma estática; cada juego lista las suyas y dónde obtener el código.
🇬🇧 The recomps use free libraries, statically linked; each game lists its own and where to get the source.
🇧🇷 As recompilações usam bibliotecas livres ligadas estaticamente; cada jogo lista as suas e onde obter o código.

| Biblioteca / Library | Licencia / License | Código / Source |
|---|---|---|
| 🎨 **vitaGL** (Rinnegatamante) | LGPL-3.0 | https://github.com/Rinnegatamante/vitaGL |
| 🧠 **vitaShaRK** (Rinnegatamante) | LGPL-3.0 | https://github.com/Rinnegatamante/vitaShaRK |
| 🧩 **SceShaccCgExt** (bythos14) | LGPL-2.1 | https://github.com/bythos14/SceShaccCgExt |
| ➗ **math-neon** (Lachlan Tychsen-Smith) | MIT | https://github.com/Rinnegatamante/math-neon |

🙏 Gracias / Thanks / Obrigado: Rinnegatamante, bythos14, Lachlan Tychsen-Smith, the VitaSDK team and the PS Vita homebrew community. 💙

🏷️ Todos los juegos y marcas pertenecen a sus respectivos dueños; este proyecto no está afiliado a ellos. / All games and trademarks belong to their respective owners; this project is not affiliated with them. / Todos os jogos e marcas pertencem a seus respectivos donos; este projeto não é afiliado a eles.
