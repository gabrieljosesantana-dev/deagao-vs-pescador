# 🏝️ Ilha dos Dragões 3D

Jogo de tiro em primeira pessoa (FPS) em uma ilha tropical infestada de **dragões voadores**. Sobreviva às ondas, derrote chefes, compre armas e upgrades, e use a cabana como área segura.

![Three.js](https://img.shields.io/badge/Three.js-0.160-black?logo=threedotjs)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/status-jogável-brightgreen)

---

## 🎮 Como jogar

1. Baixe ou clone o repositório
2. Abra o arquivo `index.html` no navegador (Chrome, Firefox ou Edge)
3. **Clique na tela** para começar (bloqueia o mouse)
4. Sobreviva às ondas de dragões!

> Não precisa instalar nada. É só abrir o HTML.

---

## ⌨️ Controles

| Tecla / Ação       | Função              |
|--------------------|---------------------|
| **WASD**           | Mover               |
| **Mouse**          | Mirar               |
| **Clique esquerdo**| Atirar              |
| **Espaço**         | Pular               |
| **R**              | Recarregar          |
| **Clique**         | Iniciar / continuar |

---

## ✨ Recursos

### 🐉 Combate
- Dragões voadores realistas (asas, cauda, chifres, garras)
- Sistema de **ondas** com dificuldade crescente
- **Chefes** a cada 3 ondas (dragões gigantes)
- Barra de vida do chefe
- Efeitos de tiro, partículas e flash do cano

### ⚔️ Armas (compre na loja)
| Arma          | Estilo                          |
|---------------|---------------------------------|
| 🔫 Pistola    | Padrão, equilibrada             |
| 💥 Espingarda | Spread (vários tiros de perto)  |
| 🎯 Fuzil      | Alto dano e boa cadência        |
| 🔴 Laser      | Muito rápido, muita munição     |

### 🛒 Loja entre ondas
- Comprar e equipar armas
- **Drone aliado** 🤖 — atira junto com você
- Upgrades: dano, cadência, munição, recarga, vida, velocidade, sorte de ouro
- Poção de cura

### 🏠 Área segura
- Cabana de madeira com zona verde
- Dragões **não entram** e não atacam dentro dela
- Regeneração lenta de vida

### 🌴 Mundo
- Ilha grande com relevo, areia caminhável e mar com ondas
- 75+ árvores (pinheiros, árvores comuns e **coqueiros**)
- Pedras e vegetação
- **Bichos passivos**: coelhos, pássaros, cervos, caranguejos e borboletas

### 🎨 Gráficos
- Céu com gradiente
- Luzes dinâmicas e sombras suaves
- Tom cinematográfico (ACES)
- Névoa e água animada

---

## 📁 Estrutura

```
ilha-shooter/
├── index.html    # Jogo completo (Three.js via CDN)
└── README.md     # Este arquivo
```

---

## 🛠️ Tecnologias

- **Three.js** (r160) — renderização 3D
- **PointerLockControls** — controles de FPS
- HTML5 + CSS3 + JavaScript (ES modules)
- Sem build, sem dependências locais

---

## 🚀 Publicar no GitHub Pages

1. Crie um repositório no GitHub
2. Envie os arquivos (`index.html` + `README.md`)
3. Em **Settings → Pages**, escolha a branch `main` e a pasta `/root`
4. Acesse: `https://seu-usuario.github.io/nome-do-repo/`

---

## 📌 Dicas

- Use a **cabana** para se curar quando estiver com pouca vida
- Guarde moedas para a **espingarda** ou o **drone** cedo
- Chefes dão muito mais moedas — foque neles
- A areia da praia é caminhável; só caia se entrar no mar fundo

---

## 📜 Licença

Projeto livre para uso pessoal e estudo. Divirta-se!

---

**Feito com Three.js · Ilha dos Dragões 3D** 🐉🏝️
