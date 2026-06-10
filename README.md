# 🧟 Vale Cinza: Horda

Um jogo de sobrevivência contra hordas no estilo *Vampire Survivors*, rodando inteiramente no navegador. Ambientado em **Jaraguá do Sul, SC — 2026**, onde uma pandemia transformou a cidade num vale cinzento cheio de monstros. Sobreviva ao maior número de hordas que conseguir.

---

## 🎮 Sobre o jogo

Você é um sobrevivente solitário num cenário pós-pandemia. A cada horda, inimigos surgem em ondas cada vez mais fortes e rápidas. Elimine todos para avançar, colete upgrades e enfrente o chefão golem com seu temido ataque de laser.

O jogo é um **único arquivo HTML autocontido** — todo o código, sprites (em base64) e lógica estão embutidos. Não há dependências, build, nem instalação: basta abrir no navegador.

---

## ✨ Funcionalidades

- **Combate manual** — mire com o mouse e clique para atacar na direção do cursor.
- **Sistema de hordas progressivas** — inimigos escalam em vida, velocidade e dano a cada rodada.
- **6 tipos de inimigos** com sprites animados: Zumbi, Cão, Infetado, Blindado e o Chefão, além do Suicida.
- **Chefão golem** com ataque de laser: ele para, fica invulnerável durante a animação de carga e dispara um feixe que atravessa quase todo o mapa.
- **6 armas** com sprites próprios: Faca (inicial), Bastão, Facão, Pistola, Espingarda e Rifle.
- **Sistema de upgrades** a cada 2 hordas — escolha entre melhorias de atributos ou novas armas, com raridades (comum, raro, épico).
- **Pontos de interesse no mapa** — Santuário (cura) e Caixa de Munição (recarga).
- **Tudo em português brasileiro.**

---

## 🕹️ Controles

| Tecla | Ação |
|-------|------|
| `WASD` ou `↑ ↓ ← →` | Mover o personagem |
| `Clique` do mouse | Atacar / atirar na direção do cursor |
| `1` – `8` | Trocar de arma |
| `E` | Usar ponto de interesse (Santuário / Caixa de Munição) |
| `R` | Recarregar arma |

---

## 🔫 Armas

| Arma | Tipo | Raridade |
|------|------|----------|
| **Faca** | Corpo a corpo (inicial) | — |
| **Bastão** | Corpo a corpo com knockback | Comum |
| **Pistola** | 12 tiros por carregador | Comum |
| **Espingarda** | 5 projéteis em leque | Raro |
| **Rifle** | Dano alto | Raro |
| **Facão** | Corpo a corpo de alto dano | Raro |

## 🎁 Upgrades

| Upgrade | Efeito | Raridade |
|---------|--------|----------|
| **Velocidade** | +20% de movimento | Comum |
| **Vida Extra** | +40 HP máximo | Comum |
| **Força** | +30% de dano | Raro |
| **Armadura** | -25% de dano recebido | Raro |
| **Regeneração** | +1 HP por segundo | Raro |
| **Roubo de Vida** | 2% do dano causado vira HP | Épico |

---

## 🚀 Como rodar localmente

Como o jogo é um único arquivo HTML, não há nada para instalar.

**Opção 1 — Abrir direto:**
Dê duplo clique em `vale_cinza_horda.html` e ele abrirá no seu navegador.

**Opção 2 — Com Live Server (VS Code):**
1. Instale a extensão **Live Server** no VS Code.
2. Abra a pasta do projeto.
3. Clique com o botão direito em `vale_cinza_horda.html` → **Open with Live Server**.
4. O jogo abre em `http://127.0.0.1:5500` e recarrega ao salvar.

---

## 🌐 Deploy

O projeto é um site estático, então pode ser publicado em qualquer hospedagem de arquivos estáticos (Vercel, Netlify, GitHub Pages). Para o **Vercel**, basta conectar o repositório do GitHub — nenhuma configuração de build é necessária.

---

## 🛠️ Tecnologias

- **HTML5 Canvas** para a renderização do jogo
- **JavaScript vanilla** (sem frameworks ou bibliotecas)
- **Sprites em pixel art** embutidos em base64
- Arquitetura de **arquivo único**, sem dependências

---

## 📋 Status do projeto

Em desenvolvimento ativo. Próximos passos possíveis: sprite do inimigo Suicida, novos chefões, sistema de pontuação persistente e mais armas.

---

## 📄 Licença

Distribuído sob a licença MIT. Sinta-se livre para usar, modificar e aprender com o código.

---

*Feito com 🩶.*
