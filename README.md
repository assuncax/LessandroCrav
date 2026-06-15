# CT Lessandro Carvalho — Landing Page

Landing page institucional do **Centro de Treinamento Lessandro Carvalho**, em Santa Bárbara d'Oeste/SP. Site estático (HTML, CSS e JavaScript puros), sem dependências de build — é só abrir no navegador.

---

## 📁 Estrutura de pastas

```
LessandroCarv/
├── index.html          # Página principal (estrutura/conteúdo)
├── css/
│   └── styles.css      # Todo o estilo visual
├── js/
│   └── main.js         # Interações (menu mobile, scroll, animações)
├── assets/
│   └── img/            # Imagens do site (logo, fotos do espaço)
└── README.md           # Este arquivo
```

---

## 🚀 Como visualizar

Basta abrir o arquivo `index.html` no navegador (duplo clique).

Para um ambiente local com servidor (recomendado durante o desenvolvimento):

```bash
# Com Python instalado
python -m http.server 8000
# Acesse http://localhost:8000

# Ou com Node.js
npx serve
```

---

## 🎨 Identidade visual

| Elemento        | Valor                              |
|-----------------|------------------------------------|
| Fundo           | Branco `#ffffff`                   |
| Texto           | Preto `#111315`                    |
| Cor de destaque | Verde água (teal) `#12b8a6`        |
| Fonte da marca  | **Oswald**                         |
| Fonte de títulos| **Anton**                          |
| Fonte de texto  | **Inter**                          |

As cores ficam centralizadas em variáveis CSS no topo de `css/styles.css` (`:root`) — altere ali para mudar o tema do site inteiro.

---

## 🧩 Seções da página

1. **Cabeçalho** fixo com navegação e botão de aula grátis
2. **Hero** — chamada principal e destaques
3. **Modalidades** — CrossFit, LPO, Ginástica Olímpica, HIIT, Power Lifting, Funcional
4. **Sobre** — diferenciais (equipe certificada, infraestrutura, acessibilidade)
5. **Parcerias** — Wellhub e TotalPass
6. **Horários** de funcionamento
7. **Localização / Contato** — endereço, telefone, e-mail, mapa
8. **CTA final** — aula experimental gratuita
9. **Rodapé** + botão flutuante de WhatsApp

---

## 📞 Informações de contato

- **Endereço:** Av. Alfredo Contato, 1175 — Dona Regina, Santa Bárbara d'Oeste — SP, 13455-726
- **WhatsApp / Telefone:** (19) 97169-0630
- **E-mail:** ctlessandrocarvalho@gmail.com
- **Instagram:** [@ctlessandrocarvalho](https://www.instagram.com/ctlessandrocarvalho/)

### Horários
- **Segunda a Sexta:** 06h00 — 20h00
- **Sábado:** 08h00 — 10h00
- **Domingo:** Fechado

---

## ✏️ Como editar

- **Textos e seções:** edite o `index.html`.
- **Cores, espaçamentos e layout:** edite o `css/styles.css`.
- **Comportamentos (menu, animações):** edite o `js/main.js`.
- **Imagens:** adicione os arquivos em `assets/img/` e referencie no HTML.

---

© 2026 CT Lessandro Carvalho. Todos os direitos reservados.
