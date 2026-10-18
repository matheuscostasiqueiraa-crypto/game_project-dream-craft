<img width="534" height="192" alt="New 30sz" src="https://github.com/user-attachments/assets/4062d326-bc4b-4514-8a2e-7885d859a68a" />

# NULIRIS

> Um gato cego. Um experimento. Um mundo que só existe quando ele dorme.

---

## Sobre o Projeto

**Nuliris** é um jogo voxel em HTML5 + Three.js, desenvolvido por um único criador. O projeto combina construção de blocos, física de fluidos, ciclo dia/noite, sistema de clima dinâmico e uma camada narrativa sobre um gato cego usado em experimentos científicos para descobrir como o cérebro processa imagens.

Este repositório contém o código-fonte, os assets e a documentação do jogo.

---

## Como Jogar

### Requisitos
- Navegador moderno (Chrome, Firefox, Edge, Safari)
- JavaScript habilitado
- WebGL 2.0

### Executando o Jogo
1. Baixe o arquivo `Nulo_Dreams_Demo.html` (ou renomeie para `Nuliris.html`).
2. Abra o arquivo no navegador.
3. Aguarde o carregamento dos assets.
4. Divirta-se.

### Controles (Teclado)

| Ação | Tecla |
| :--- | :--- |
| Mover para frente | `W` |
| Mover para trás | `S` |
| Mover para esquerda | `A` |
| Mover para direita | `D` |
| Pular | `Espaço` |
| Agachar | `Shift` |
| Quebrar bloco | `Clique Esquerdo` |
| Colocar bloco | `Clique Direito` |
| Inventário | `E` |
| Chat | `T` ou `/` |
| Pausa | `ESC` |
| Configurações | `F1` |
| Print | `F2` |
| Debug | `F3` |
| Zoom | `Z` |
| Interagir | `F` |

### Controles (Mobile)
- **D-Pad virtual** no canto inferior esquerdo.
- **Botões de ação** no canto inferior direito (Pular, Quebrar, Colocar, Zoom, Interagir).
- **Área de câmera** no lado direito da tela para olhar ao redor.
- Toque na hotbar para trocar de item.

### Modos de Jogo
- **Sobrevivência:** você tem vida, precisa coletar recursos e sobreviver.
- **Criativo:** voe, coloque e quebre blocos infinitamente.

### Multiplayer
- Conexão P2P via PeerJS.
- Hospede uma sala ou entre em uma existente com um código.

---

## Sistemas Implementados

- **Motor voxel otimizado** com streaming de chunks.
- **Física de blocos** (gravidade, colisão, água).
- **Ciclo dia/noite** dinâmico.
- **Sistema de clima** (nublado, chuva, tempestades com raios).
- **Sistema de conquistas** por mundo.
- **Editor de skin** e suporte a skins no formato Minecraft (64×64).
- **Sistema de idiomas** (i18n).
- **Configurações de performance** (resolução, DOF, distância de render, filtros).
- **HUD personalizável** (FPS, debug, posição).
- **Save/Load** local via `localStorage`.

---

## Tecnologias

- **HTML5 Canvas** para renderização do menu.
- **Three.js** para o motor 3D.
- **PeerJS** para multiplayer P2P.
- **IndexedDB** para cache local de assets.
- **Web Audio API** para sons.

---

## Estrutura do Projeto

