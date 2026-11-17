# 🏍️ MX vs. ATV Unleashed para PS Vita — v1.00

🇪🇸 [Español](#-español) · 🇬🇧 [English](#-english) · 🇧🇷 [Português](#-português)

---

## 🇪🇸 Español

### 🎮 Qué es
Una **recompilación** de la versión de PC de *MX vs. ATV Unleashed* para que funcione en la **PS Vita**. 🔥
⚠️ No incluye ningún archivo del juego: **necesitas tu propia copia** de la versión de PC.

### 📦 Instalación
1. 💿 Instala el juego en un PC.
2. 📁 Copia todo el contenido de la carpeta de instalación (la que tiene `MXvsATV.exe` y las carpetas `data` y `media`) a la consola, en:
   ```
   ux0:data/mxvsatv/app/
   ```
   ✅ Tiene que quedar así: `ux0:data/mxvsatv/app/MXvsATV.exe`
3. 📲 Instala `MXVSATV.vpk` con VitaShell.
4. 🧩 Hace falta `libshacccg.suprx` en `ur0:data/` (el mismo que piden otros ports).

### 📝 Notas
- ⏳ La primera vez que juegues, los primeros menús y carreras pueden ir a tirones unos segundos mientras se preparan los gráficos. A partir de la segunda vez van normales.
- 🚫 Las opciones de vídeo y el multijugador están desactivados (aparecen en gris).
- 🌑 Las sombras dinámicas están desactivadas para mantener la velocidad.
- 💾 Las partidas se guardan en `ux0:data/mxvsatv/escritura/`.
- 🐞 Si algo falla, el registro está en `ux0:data/mxvsatv/registro/arranque.log`: adjúntalo al reportar el problema.

---

## 🇬🇧 English

### 🎮 What it is
A **recompilation** of the PC version of *MX vs. ATV Unleashed* so it runs on the **PS Vita**. 🔥
⚠️ No game files are included: **you need your own copy** of the PC version.

### 📦 Installation
1. 💿 Install the game on a PC.
2. 📁 Copy everything inside the install folder (the one with `MXvsATV.exe` and the `data` and `media` folders) to the console, into:
   ```
   ux0:data/mxvsatv/app/
   ```
   ✅ It should end up as: `ux0:data/mxvsatv/app/MXvsATV.exe`
3. 📲 Install `MXVSATV.vpk` with VitaShell.
4. 🧩 `libshacccg.suprx` is required in `ur0:data/` (the same one other ports ask for).

### 📝 Notes
- ⏳ The first time you play, the first menus and races may stutter for a few seconds while the graphics are prepared. From the second time on they run normally.
- 🚫 Video options and multiplayer are disabled (shown in grey).
- 🌑 Dynamic shadows are disabled to keep the game fast.
- 💾 Saves are stored in `ux0:data/mxvsatv/escritura/`.
- 🐞 If something goes wrong, the log is at `ux0:data/mxvsatv/registro/arranque.log`: attach it when reporting the problem.

---

## 🇧🇷 Português

### 🎮 O que é
Uma **recompilação** da versão de PC de *MX vs. ATV Unleashed* para rodar no **PS Vita**. 🔥
⚠️ Nenhum arquivo do jogo está incluído: **você precisa da sua própria cópia** da versão de PC.

### 📦 Instalação
1. 💿 Instale o jogo em um PC.
2. 📁 Copie todo o conteúdo da pasta de instalação (a que tem o `MXvsATV.exe` e as pastas `data` e `media`) para o console, em:
   ```
   ux0:data/mxvsatv/app/
   ```
   ✅ Deve ficar assim: `ux0:data/mxvsatv/app/MXvsATV.exe`
3. 📲 Instale o `MXVSATV.vpk` com o VitaShell.
4. 🧩 É necessário o `libshacccg.suprx` em `ur0:data/` (o mesmo que outros ports pedem).

### 📝 Notas
- ⏳ Na primeira vez que você jogar, os primeiros menus e corridas podem travar por alguns segundos enquanto os gráficos são preparados. A partir da segunda vez rodam normalmente.
- 🚫 As opções de vídeo e o multijogador estão desativados (aparecem em cinza).
- 🌑 As sombras dinâmicas estão desativadas para manter a velocidade.
- 💾 Os saves ficam em `ux0:data/mxvsatv/escritura/`.
- 🐞 Se algo der errado, o log está em `ux0:data/mxvsatv/registro/arranque.log`: anexe-o ao relatar o problema.

---

## 📜 Licencias / Licenses / Licenças

🇪🇸 Este port usa estas bibliotecas libres, enlazadas de forma estática en el eboot. Sus licencias están en la carpeta [`LICENSES`](LICENSES).
🇬🇧 This port uses these free libraries, statically linked into the eboot. Their licenses are in the [`LICENSES`](LICENSES) folder.
🇧🇷 Este port usa estas bibliotecas livres, ligadas estaticamente ao eboot. As licenças estão na pasta [`LICENSES`](LICENSES).

| Biblioteca / Library | Licencia / License | Código / Source |
|---|---|---|
| 🎨 **vitaGL** (Rinnegatamante) | LGPL-3.0 | https://github.com/Rinnegatamante/vitaGL — 📦 la versión exacta usada / the exact version used / a versão exata usada: [`vitaGL-source.tar.gz`](vitaGL-source.tar.gz) (commit `cd3791e` + `local_changes.diff`, `make NO_SPLASHSCREEN=1`) |
| 🧠 **vitaShaRK** (Rinnegatamante) | LGPL-3.0 | https://github.com/Rinnegatamante/vitaShaRK |
| 🧩 **SceShaccCgExt** (bythos14) | LGPL-2.1 | https://github.com/bythos14/SceShaccCgExt |
| ➗ **math-neon** (Lachlan Tychsen-Smith) | MIT | https://github.com/Rinnegatamante/math-neon |

🙏 Gracias / Thanks / Obrigado: Rinnegatamante, bythos14, Lachlan Tychsen-Smith, the VitaSDK team and the PS Vita homebrew community. 💙

🏷️ *MX vs. ATV Unleashed* es una marca de sus respectivos dueños. Este proyecto no está afiliado a ellos. / *MX vs. ATV Unleashed* is a trademark of its respective owners. This project is not affiliated with them. / *MX vs. ATV Unleashed* é uma marca de seus respectivos donos. Este projeto não é afiliado a eles.
