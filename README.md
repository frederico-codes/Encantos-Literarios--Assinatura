# Encantos Literários — LP de Clube de Assinatura

Landing page responsiva e focada em **animações CSS** inspirada no design da Rocketseat. O projeto evidencia microinterações, transições fluidas em elementos visuais do kit mensal.

![Cover](assets/Cover.svg)

> **Figma (Community)**  
> https://www.figma.com/design/Gen5r0BO4RXfdTM3dTs7VJ/LP-de-Clube-de-Assinatura--Community-?node-id=3244-3425&m=dev

---

## ✨ Destaques

- **CSS Animations** — animações suaves em cartões de preço e *props* (livro, cartões e shapes).
- **CSS Transitions** — transições de opacidade/transform com *easing* customizado.
- **CSS Functions** — uso de `var()`, `calc()`, `min()`, `max()` e `@media`.
- **Responsividade** — *layout* mobile-first com *breakpoint* em `1440px`.
- **Design Tokens** — paleta em `:root` com variáveis para **brand**, **accent**, **text** e **shape**.
- **Acessibilidade básica** — `alt` em imagens, semântica em `header`, `main`, `section`, `footer`, `aria-label` em navegação.

---


---

## 🛠️ Tecnologias

- **HTML5** semântico  
- **CSS3** (custom properties, grid, flexbox, `transform`, `transition`, `@keyframes`)  
- **Google Fonts** (Raleway)

---

## 🚀 Como rodar

Não requer *build* nem servidor — é um site estático.

```bash
# opção 1: abrir direto no navegador
duplo clique em index.html

# opção 2: servir localmente (VS Code)
# Instale a extensão "Live Server" e clique em "Go Live"

```
## 📱 Responsividade

- **Mobile-first** (largura base ~**335px**).
- *Breakpoint* principal: `@media (min-width: 1440px)`:
  - Substitui *background* por versão **Large**.
  - Ativa cartões **2** e **3** da área de **Pricing**.
  - Habilita efeitos 3D nos *props* e reorganiza grid para 3 colunas.

---

## 🧪 Qualidade & Performance

- **Imagens SVG** predominantemente (nitidez + peso reduzido).
- **Sem JS** — toda interação é CSS (baixo custo de CPU).
- **Tokens em `:root`** — facilita *theme* e manutenção.

---

## 🔧 Customização rápida

- **Cores**: edite as variáveis em `:root`.
- **Breakpoints**: ajuste o `@media (min-width: 1440px)`.
- **Easing**: troque o `cubic-bezier` nas `transition-*`.
- **Cards**: adicione/remova planos duplicando `.pricing__card`.


## 📄 Licença & Créditos

- **Design**: Rocketseat (Community — link acima).
- **Implementação**: você ✨
- Uso educacional/demonstrativo. Verifique a licença do design original no Figma.


### Licença

Este projeto está licenciado sob a **Licença MIT** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.
