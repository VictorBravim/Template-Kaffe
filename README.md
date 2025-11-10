# Kaffe

![image 6](https://github.com/VictorBravim/Kaffe/assets/122113588/5bebf963-591f-49f9-b7c1-4bb30b91622b)


## <code>Introdução</code>

Kaffe é um projeto de site desenvolvido em React com Next.js, focado em apresentar uma cafeteria fictícia servindo de estudo e prática de estrutura front-end..

## <code>Pré-requisitos</code>

- Node.js
- npm ou yarn
- react-slick

## <code>Configuração</code>

1. Clone o Repositório:
   
```
git clone https://github.com/VictorBravim/Kaffe.git
cd kaffe
```

2. Instale dependências:
   
```
npm install
# ou
yarn install
```

3. Execute o projeto:
   
```
npm run dev
# ou
yarn dev
```

## <code>Estrutura</code>

- RootLayout.tsx: Define o layout base do site, incluindo importações de fontes (Montserrat), estilos globais (globals.css) e configurações de metadados.
- Page.tsx: Componente principal da página inicial, que compõe a estrutura completa da página, incluindo navegação, herói, produtos, seção “Sobre”, seção de contato e rodapé.
- Nav.tsx: A navegação no site permite alterar seções clicando em botões e destaca visualmente a seção atual.
- Hero.tsx: Controle deslizante de imagem na seção principal da página inicial, usando react-slick para funcionalidade de carrossel.
- Produtos.tsx: Renderiza uma lista de produtos com imagens e informações associadas, usando dados estáticos.
- About.tsx: Apresenta informações sobre diferentes tópicos em cartões de conteúdo.
- Contact.tsx: Formulário de contato que captura informações do usuário (nome, email, mensagem) e trata do envio.
- Footer.tsx: Rodapé do site com links para diferentes seções e funcionalidade de menu recolhível.

## <code>Licença</code>

- Este projeto está licenciado sob a [Licença MIT](LICENSE).
