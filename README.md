# Do Zero à Entrega — Guia de Projeto Completo

Um **guia interativo e responsivo** para transformar uma ideia em um projeto real. voltado a quem precisa estruturar e entregar um trabalho do início ao fim sem uma equipe pronta — TCC, projeto pessoal ou primeira startup.

O conteúdo está organizado como um roteiro prático de seis etapas, com exemplos aplicáveis, um plano de ação com progresso persistente e respostas para as dúvidas mais comuns de quem começa sozinho.

> **Idioma:** Português (pt-BR) · **Tipo:** site estático, sem dependências ou etapa de build.

---

## ✨ Funcionalidades

- **Jornada em 6 etapas** — Ideação, Estratégia, Requisitos, Modelagem, Planejamento e Entrega, navegáveis pela linha do tempo.
- **Conteúdo acionável** — cada etapa traz critérios, exemplos e um entregável claro ("o que sai daqui").
- **Plano de ação interativo** — checklist com 18 itens divididos por etapa, barra de progresso em tempo real e salvamento automático no navegador (`localStorage`).
- **Abas comparativas** — alternância entre cenários dentro das etapas, com navegação por teclado via `aria-selected`.
- **FAQ em acordeão** — perguntas frequentes com abertura exclusiva e estados `aria-expanded`.
- **Navegação inteligente** — menu mobile, *scroll spy* que destaca a seção atual, barra de progresso de leitura e botão "voltar ao topo".
- **Animações discretas** — revelação dos elementos ao rolar, com `IntersectionObserver` e respeito a `prefers-reduced-motion`.
- **Acessibilidade e responsividade** — marcação semântica, rótulos ARIA, foco visível e layout adaptado a celular, tablet e desktop.

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
| --- | --- |
| Estrutura | HTML5 semântico |
| Estilo | CSS3 (variáveis, Grid, Flexbox, animações) |
| Interatividade | JavaScript moderno (ES6+, sem frameworks) |
| Persistência | `localStorage` do navegador |
| Tipografia | Google Fonts (Inter + Plus Jakarta Sans) |

Sem pacotes, sem build, sem backend. O projeto funciona apenas com os arquivos estáticos.

---

## 📁 Estrutura

```
.
├── index.html   # Conteúdo, seções e toda a lógica de interatividade
├── style.css    # Design system, layout, responsividade e animações
└── README.md    # Esta documentação
```

---

## 🚀 Como executar

**Opção mais simples:** abra o arquivo `index.html` diretamente no navegador.

**Opção recomendada (serve local):**

```bash
# Python 3
python -m http.server 8000
```

Acesse `http://localhost:8000`.

Para publicar, basta enviar os três arquivos para qualquer hospedagem de sites estáticos (GitHub Pages, Netlify, Vercel etc.).

---

## 🧠 Sobre este repositório

Este é o **estado inicial** do projeto: a estrutura completa e funcional construída como experimento de desenvolvimento assistido por IA, registrada aqui para versionamento e evolução posterior. A proposta é servir tanto como material de consulta quanto como base para novas iterações.

---

## 📄 Uso

Conteúdo livre para uso pessoal e educacional. Sugestões e melhorias são bem-vindas via *issues* e *pull requests*.
