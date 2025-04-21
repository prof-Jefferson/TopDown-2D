# 🌟 Projeto Educacional Unity: Rotação de Poderes e Alvo por Distância

![Unity](https://img.shields.io/badge/Unity-6.0-blue.svg)
![License](https://img.shields.io/badge/educacional-livre-green.svg)

Este é um projeto **educacional** desenvolvido com **Unity 6.0**, que tem como objetivo aplicar os **princípios da Programação Orientada a Objetos (POO)** combinados com a **filosofia do padrão ECS (Entity Component System)**. O foco está em boas práticas de modularização, legibilidade e reutilização de código no desenvolvimento de jogos.

---

## 🎮 Descrição do Jogo

O jogo apresenta um personagem principal com poderes mágicos que **rotacionam ao seu redor** e têm como missão **detectar e atacar automaticamente o inimigo mais próximo**.

### 🧩 Principais Mecânicas:
- Jogador com habilidades giratórias automáticas;
- Identificação do inimigo mais próximo com base em distância;
- Ataques automáticos com instanciamento modular;
- Estrutura de código baseada em **POO com inspiração em ECS**.

---

## 🎓 Objetivo Educacional

- Ensinar conceitos fundamentais de **POO (classes, herança, encapsulamento, polimorfismo)**;
- Praticar organização e separação de responsabilidades no Unity;
- Apresentar conceitos básicos de ECS (sem uso direto do Unity DOTS);
- Trabalhar com sprites públicos para prototipação rápida e ética.

---

## 🧱 Tecnologias e Ferramentas Utilizadas

- **Unity 6.0**
- **C#**
- **Visual Studio 2022 / VS Code**
- **OpenGameArt.org (sprites livres)**
- **Sistema baseado em Prefabs, Scripts Modulares e Gerenciamento de Componentes**

---

## 🖼️ Sprites Utilizados

Assets públicos utilizados:

- 🌳 Árvores e Plantas: [Lots of Trees and Plants – OGA DB32](https://opengameart.org/content/lots-of-trees-and-plants-from-oga-db32-tilesets-pack-1)
- 👤 Personagens: [Pepper&Carrot Characters](https://opengameart.org/content/24x32-peppercarrot-characters)
- 🐙 Inimigo Tentacular: [Top-down Tentacle Creature](https://opengameart.org/content/top-down-tentacle-creature)
- 🌱 Planta Predadora: [Pixel Predator Plant Mob](https://opengameart.org/content/pixel-predator-plant-mob-character)
- ☠️ Esqueletos: [Skeletons Rework](https://opengameart.org/content/skeletons-rework)

---

## 📁 Organização do Projeto

```plaintext
Assets/
├── Art/
│   ├── Characters/
│   ├── Enemies/
│   └── Environment/
├── Prefabs/
├── Scripts/
│   ├── Core/
│   ├── Powers/
│   └── AI/
├── Scenes/
├── Audio/ (se aplicável)
└── README.md
