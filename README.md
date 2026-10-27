# A fazenda

**Português** | [English](README.en.md)

Projeto **Unity 6** em **2D** com **Universal Render Pipeline (URP)**, criado a partir do modelo 2D da Unity.

> **Status: não iniciado.** O repositório contém apenas o projeto recém-criado: a cena de exemplo com câmera e luz 2D padrão. Ainda não há scripts C# nem conteúdo de jogo.

## Tecnologias

- **Unity** 6000.5.4f1 (linha Unity 6)
- **Universal Render Pipeline** 2D
- Pacotes do modelo 2D da Unity (Input System, 2D Animation, Tilemap Extras, entre outros), listados em `Packages/manifest.json`

## Estrutura

```
A-fazenda/
├── Assets/
│   ├── Scenes/SampleScene.unity   # cena de exemplo do modelo
│   └── Settings/                  # configurações do URP 2D
├── Packages/manifest.json         # pacotes do projeto
└── ProjectSettings/               # configurações do projeto (ProjectVersion.txt)
```

## Como abrir

1. Instale o **Unity Hub** e o editor **6000.5.4f1** (ou uma versão compatível do Unity 6).
2. No Unity Hub, clique em **Add** e selecione a pasta do repositório.
3. Abra a cena `Assets/Scenes/SampleScene.unity`.
