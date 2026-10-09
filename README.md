# 🥐 Padaria Aurora — Website Responsivo

Landing page demonstrativa para uma **padaria artesanal fictícia**, criada como projeto de portfólio frontend. O site utiliza uma identidade visual acolhedora, navegação por seções e catálogo de produtos com filtros interativos.

> **Projeto fictício:** nome, telefone, endereço, horários e produtos são demonstrativos. Não representam uma empresa real. Antes de adaptar para um cliente, substitua essas informações.

## ✨ Funcionalidades

- Layout responsivo para desktop, tablet e celular.
- Menu de navegação mobile com botão hambúrguer, indicação de estado e fechamento pela tecla `Escape`.
- Navegação entre seções da página.
- Catálogo de produtos com filtros **Todos**, **Pães e salgados**, **Doces** e **Bebidas**.
- Links demonstrativos para pedidos e contato via WhatsApp, com mensagens pré-preenchidas.
- Seções institucionais, apresentação de produtos, diferenciais e contato.
- Link de pesquisa no Google Maps (exemplo, não localização de empresa real).
- Ano do rodapé atualizado automaticamente via JavaScript.
- Link **Voltar ao topo** com rolagem suave.
- Recursos básicos de acessibilidade, como textos alternativos, atributos ARIA e suporte a redução de movimento.

## 🛠️ Tecnologias

| Tecnologia | Aplicação |
| --- | --- |
| HTML5 | Estrutura semântica e conteúdo |
| CSS3 | Estilização, layout e responsividade |
| JavaScript puro | Menu mobile, filtros, ano do rodapé e rolagem ao topo |
| Google Fonts | Fontes DM Sans e Playfair Display |

O projeto é **estático**: não utiliza frameworks, banco de dados, backend ou ferramentas de build.

## 📁 Estrutura

```text
padaria-aurora/
├── assets/
│   ├── favicon.svg
│   ├── hero-paes.webp
│   ├── historia-croissants.webp
│   ├── pao-artesanal.webp
│   ├── croissant.webp
│   ├── doce-da-casa.webp
│   ├── cafe.webp
│   ├── bolos-tortas.webp
│   ├── cafe-com-leite.webp
│   └── ambiente-cafe.webp
├── index.html
├── styles.css
├── script.js
└── README.md
```

As imagens usadas no site estão na pasta `assets/`, em formato **WebP**. Não há dependência de URLs externas para exibir essas imagens.

## 🚀 Como executar localmente

1. Baixe ou clone o repositório.
2. Abra a pasta `padaria-aurora` no Visual Studio Code.
3. Abra o arquivo `index.html` no navegador ou use a extensão **Live Server**.

Não é necessário instalar dependências.

## 📱 Responsividade

O CSS inclui ajustes para diferentes larguras, incluindo pontos de quebra em aproximadamente **1020 px, 800 px e 520 px**. Em telas pequenas, a navegação se torna recolhível e os cards se reorganizam para facilitar a leitura.

## ⚙️ Personalização

Antes de usar o projeto para um negócio real:

1. Substitua nome, identidade visual e textos da Padaria Aurora.
2. Troque o número demonstrativo `5554999999999` nos links `wa.me` pelo WhatsApp comercial correto (`55` + DDD + número).
3. Atualize endereço, horários e link do Google Maps.
4. Revise produtos, preços e disponibilidade.
5. Substitua imagens ilustrativas por fotos autorizadas dos produtos reais.
6. Confira `<title>`, meta description, favicon e informações de contato.
7. Teste os links, filtros, menu e responsividade antes de publicar.

## 🖼️ Imagens e fontes

- As imagens de produtos e ambiente incluídas em `assets/` são **ilustrações geradas por IA**, usadas exclusivamente para demonstrar o layout. Não retratam produtos de uma empresa real.
- O favicon é um SVG do próprio projeto.
- As fontes **DM Sans** e **Playfair Display** são carregadas do **Google Fonts**. Se a conexão estiver indisponível, o navegador utilizará fontes alternativas definidas no CSS.

## 🌐 Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html`, `styles.css`, `script.js`, `README.md` e a pasta `assets/`, mantendo `index.html` na raiz.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)` e salve.
6. Aguarde a publicação e teste o endereço gerado pelo GitHub.

Como é um site estático, também pode ser hospedado em serviços como Netlify e Vercel.

## ♿ Acessibilidade

O projeto inclui estrutura HTML semântica, link para pular ao conteúdo, atributos ARIA no menu e filtros, textos alternativos nas imagens, foco visível e suporte a `prefers-reduced-motion`. Essas medidas **não equivalem a uma auditoria completa de acessibilidade**.

## 🔒 Privacidade

O site não possui login, formulários próprios de coleta, banco de dados ou cookies próprios implementados. Links para WhatsApp e Google Maps e o carregamento de fontes do Google Fonts podem envolver serviços externos e suas respectivas políticas de privacidade.

## 📌 Status

**Versão demonstrativa de portfólio.** Imagens armazenadas localmente, botão de retorno ao topo corrigido e funcionalidades frontend implementadas. Contatos e dados comerciais permanecem fictícios.

## 👨‍💻 Autor

Projeto demonstrativo de desenvolvimento frontend para portfólio profissional.
