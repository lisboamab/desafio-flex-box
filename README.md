# 🎯 Desafio Flexbox – Cards de Raquetes de Beach Tennis

## 📌 Objetivo
Este desafio tem como objetivo praticar **Flexbox na prática**, utilizando um layout de cards já existente.

Você recebeu um HTML pronto e um CSS inicial.  
Seu desafio é **organizar, alinhar e tornar o layout responsivo usando apenas Flexbox**.

---

## ❗ Regras do Desafio

- ❌ Não usar CSS Grid
- ❌ Não usar `position: absolute` ou `fixed`
- ❌ Não alterar o HTML
- ✅ Alterar apenas o arquivo `styles.css`
- ✅ Usar Flexbox sempre que possível

---

## 🟢 Nível 1 – Alinhamento Básico

1. Centralize os cards na tela (horizontal e verticalmente).
2. Garanta espaçamento consistente entre os cards.
3. O layout deve ficar centralizado mesmo em telas grandes.

💡 Propriedades esperadas:
- `display: flex`
- `justify-content`
- `align-items`
- `gap`

---

## 🟡 Nível 2 – Responsividade

1. Em telas grandes:
   - Cards lado a lado.
2. Em telas pequenas:
   - Cards um abaixo do outro.
3. O espaçamento deve permanecer consistente.

💡 Dicas:
- `flex-wrap`
- `width`, `max-width`
- `@media`

---

## 🟠 Nível 3 – Flexbox dentro do Card

1. Transforme o `.card` em um container flex.
2. Organize os elementos internos em coluna:
   - Imagem no topo
   - Título centralizado
   - Lista alinhada à esquerda

💡 Dicas:
- `flex-direction: column`
- `align-items`

---

## 🔵 Nível 4 – Mesma altura para os cards

1. Todos os cards devem ter a mesma altura.
2. A lista (`ul`) deve crescer para ocupar o espaço disponível.
3. O layout deve permitir adicionar um botão futuramente no rodapé.

💡 Dicas:
- `flex-grow`
- `min-height`

---

## 🔴 Nível 5 – Desafio Extra

1. Quando houver mais de um card:
   - Destaque visualmente o card do meio.
2. O destaque não pode quebrar o layout.
3. Deve funcionar em telas pequenas.

💡 Dicas:
- `nth-child`
- `transform`
- `align-self`

---

## 📦 Entrega

- Apenas o arquivo `styles.css` modificado
- Layout funcionando em:
  - Desktop
  - Tablet
  - Mobile

Boa sorte 🚀  
Flexbox é músculo: só cresce treinando 😄
