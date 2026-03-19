# 🏦 Banking Frontend Challenge BR

> Desafio front-end bancário em português para praticar interfaces reais de produto, inspirado em Nubank, Itaú, Inter, C6 Bank, PicPay e Mercado Pago.

---

## 📌 Sobre o desafio

O **Banking Frontend Challenge BR** é um desafio técnico de front-end criado para desenvolvedores brasileiros que querem construir um projeto de portfólio sólido e próximo de um produto real.

A proposta vai além de uma tela bonita: você vai simular fluxos completos de um app bancário/fintech, lidando com estados reais de interface, acessibilidade, responsividade e componentização.

---

## 🎯 Para quem é?

- Devs front-end **iniciantes** que querem um projeto forte no portfólio
- Pessoas **estudando para vagas** em bancos, fintechs e squads de produto
- Quem quer praticar interfaces inspiradas em **Nubank, Itaú, Inter e C6**
- Quem deseja evoluir em **UX, UI e estruturação de aplicações reais**

---

## 🖥️ Telas e fluxos esperados

| Tela | Descrição |
|---|---|
| **Login** | CPF/e-mail, senha, feedback de erro, loading |
| **Dashboard** | Saldo, atalhos, resumo do cartão, últimas transações |
| **Extrato** | Listagem, filtros por período, busca, agrupamento |
| **Comprovante** | Dados da transação, status, compartilhar/baixar |
| **Pix** | Fluxo completo: chave → valor → revisão → confirmação → sucesso/erro |

---

## ✅ Requisitos obrigatórios

- [ ] Tela de login com validação e estado de carregamento
- [ ] Dashboard com saldo (mostrar/ocultar), atalhos e últimas transações
- [ ] Extrato com filtro por período e busca por texto
- [ ] Comprovante com todos os dados da transação
- [ ] Fluxo Pix completo (mínimo 3 etapas)
- [ ] Estados de loading, erro e vazio em pelo menos 2 telas
- [ ] Responsividade: mobile, tablet e desktop
- [ ] Dados mockados em JSON

---

## ⭐ Requisitos bônus

- [ ] Animações e microinterações
- [ ] Tema escuro/claro
- [ ] Skeleton loading
- [ ] Open Finance (bancos conectados)
- [ ] Acessibilidade completa (WCAG AA)
- [ ] Teclado numérico fake no Pix
- [ ] PWA básico
- [ ] Internacionalização (pt-BR / en)

---

## 📊 O que será avaliado

### Interface
- Hierarquia visual
- Consistência entre componentes
- Qualidade visual geral
- Atenção aos detalhes

### Experiência do usuário
- Clareza de navegação
- Feedback visual
- Usabilidade
- Fluidez da interface

### Código
- Componentização
- Organização de pastas
- Legibilidade e reaproveitamento
- Boas práticas

### Responsividade
- Mobile-first
- Adaptação coerente para tablet e desktop (não apenas redimensionamento)

### Acessibilidade
- Navegação por teclado
- Foco visível
- Contraste adequado
- Semântica HTML
- Labels e atributos ARIA

### Maturidade de produto
- Loading states
- Empty states
- Error states
- Success states
- Validações de formulário

---

## 🗂️ Estrutura sugerida

```
src/
  components/      # componentes reutilizáveis
  pages/           # telas da aplicação
  layouts/         # estruturas de layout
  services/        # chamadas e lógica de dados
  mocks/           # dados fake em JSON
  assets/          # imagens, ícones, fontes
  styles/          # estilos globais e tokens
  utils/           # funções auxiliares
```

### Dados mockados sugeridos

```
mocks/
  user.json
  accounts.json
  transactions.json
  receipts.json
  pix-contacts.json
  connected-banks.json
```

---

## 🛠️ Stack

A escolha da stack é **livre**. Algumas sugestões:

**Frameworks:**
- React + Next.js
- Vue + Nuxt
- Angular
- Vite + React
- HTML, CSS e JavaScript puro

**Extras válidos:**
- TypeScript
- Tailwind CSS / Sass
- Zustand / Pinia / Context API
- shadcn/ui
- Framer Motion / VueUse

---

## 🎨 Layout de referência (Figma)

> 🔗 **[Acessar o Figma →](#)** *(link será adicionado em breve)*

O Figma funciona como **guia de estrutura e fluxo**, não como cópia obrigatória.

Soluções autorais são bem-vindas, desde que respeitem os fluxos principais e a proposta bancária do desafio.

**Tamanhos de frame utilizados:**
- Mobile: `390 × 844`
- Tablet: `768 × 1024`
- Desktop: `1440 × 1024`

---

## 📐 Responsividade

O projeto deve ser desenvolvido com abordagem **mobile-first**, mas precisa funcionar bem em todas as telas.

A versão desktop **não deve ser apenas uma ampliação do mobile** — deve ser uma adaptação coerente ao espaço disponível:

| Dispositivo | Adaptação esperada |
|---|---|
| Mobile | Navegação inferior, blocos empilhados |
| Tablet | Grid mais espaçado, filtros laterais ou em linha |
| Desktop | Sidebar fixa, áreas paralelas, melhor aproveitamento de espaço |

---

## 🏆 Como se destacar

Projetos que se destacam normalmente apresentam:

- ✅ Boa componentização e reaproveitamento de código
- ✅ Consistência visual entre todas as telas
- ✅ Estados completos (loading, erro, vazio, sucesso)
- ✅ Responsividade real, não apenas redimensionamento
- ✅ Atenção genuína à acessibilidade
- ✅ README bem feito com prints ou GIFs
- ✅ Deploy funcionando

---

## 📦 Como entregar

1. Suba o código no **GitHub** com README organizado
2. Adicione **prints ou GIFs** das principais telas
3. Faça o **deploy** em Vercel, Netlify ou similar
4. Adicione o link do repositório nos tópicos do GitHub

---

## 💼 Por que esse projeto ajuda no portfólio?

Esse desafio demonstra que você sabe:

- Construir interfaces complexas com múltiplos estados
- Pensar em produto, não só em visual
- Lidar com fluxos reais de uma aplicação financeira
- Trabalhar acessibilidade de forma prática
- Organizar código front-end de forma escalável
- Criar experiências próximas do que o mercado espera

---

## ⚠️ Aviso legal

Este projeto é um desafio **educacional e conceitual**.
Não possui vínculo oficial com Itaú, Nubank, Inter, C6 Bank, PicPay, Mercado Pago ou qualquer outra instituição financeira.
Não use logos oficiais nem copie interfaces de bancos de forma idêntica.

---

## 📄 Licença

Livre para uso **educacional e de portfólio**.

---

## ✍️ Autor

Criado por **Gustavo Bernardi - @guubernardi**

Se esse desafio te ajudou, deixa uma ⭐ no repositório — isso ajuda mais devs a encontrarem o projeto.

---

*Inspirado em boas práticas de produto financeiro digital do ecossistema brasileiro.*
