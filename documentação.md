# Documentação do Projeto "MindEase"

## Descrição Geral
O projeto **MindEase** é uma aplicação web que simula uma interface de login estilizada, desenvolvida usando HTML e CSS. Ele inclui um cabeçalho com navegação, uma interface de formulário de login, e estilos responsivos que ajustam a exibição do conteúdo conforme o tamanho da tela.

## Estrutura de Arquivos
O projeto é composto pelos seguintes arquivos:

- **index.html**: Contém o código HTML da página principal e define a estrutura básica da interface.
- **elements.css**: Inclui a estilização principal dos elementos HTML, incluindo estilos de tipografia, cores e espaçamento.
- **general.css**: Importa os arquivos `elements.css` e `responsive.css`, e serve como arquivo central de estilo.
- **responsive.css**: Contém media queries que tornam o layout responsivo, ajustando a interface para diferentes tamanhos de tela.

## Descrição dos Arquivos

### 1. index.html
Arquivo HTML principal que define a estrutura da interface:
- Contém um cabeçalho (`header`) com o logotipo do **MindEase** e uma barra de navegação.
- Um formulário de login com campos de e-mail e senha, além de links para "Esqueci minha senha" e "Inscreva-se"&#8203;:contentReference[oaicite:0]{index=0}.

### 2. elements.css
Define os estilos base para a aplicação:
- Configurações gerais, como zeramento de margens e preenchimentos, e uso de fontes específicas (Chivo e Cinzel) para estilizar os textos.
- Definição dos estilos para o cabeçalho, logo, menu de navegação, botão de login, campos de entrada e links&#8203;:contentReference[oaicite:1]{index=1}.

### 3. general.css
Arquivo que importa os estilos básicos e os estilos responsivos:
- Importa `elements.css` e `responsive.css` para centralizar e organizar a aplicação de estilos no projeto&#8203;:contentReference[oaicite:2]{index=2}.

### 4. responsive.css
Inclui media queries para tornar a página responsiva:
- Ajusta a exibição dos elementos para dispositivos com larguras menores, adaptando o layout para melhor usabilidade em telas menores, como tablets e smartphones.
- Por exemplo, reduz a largura do formulário de login em telas menores e reorganiza a exibição da barra de navegação para dispositivos móveis&#8203;:contentReference[oaicite:3]{index=3}.

## Funcionalidades

- **Interface de Login**: Uma caixa de login centralizada, com campos para entrada de e-mail e senha, e opções para redefinição de senha e criação de nova conta.
- **Estilo Responsivo**: Ajuste automático do layout em diferentes tamanhos de tela, proporcionando uma boa experiência tanto em desktop quanto em dispositivos móveis.

## Tecnologias Utilizadas
- **HTML**: Estrutura do conteúdo e organização da interface.
- **CSS**: Estilização da interface, incluindo responsividade e efeitos de hover nos elementos de navegação.

---

Este projeto oferece uma base sólida para desenvolvimento de interfaces de autenticação. Novas funcionalidades, como integração com back-end para autenticação real, podem ser adicionadas para transformar a interface em uma aplicação completa.
