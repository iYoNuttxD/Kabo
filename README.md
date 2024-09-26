# Kabo

**Kabo** é uma plataforma voltada para a venda de produtos de tecnologia, com foco em hardware, periféricos e acessórios eletrônicos. O sistema oferece funcionalidades de e-commerce, como gestão de produtos, carrinho de compras, perfil de usuários, busca e um painel administrativo. 

## Visão Geral

Este projeto tem como objetivo proporcionar uma experiência interativa e eficiente para usuários que buscam produtos de tecnologia. A plataforma inclui:

- **Catálogo de Produtos** com detalhes sobre hardware, periféricos e acessórios.
- **Carrinho de Compras** para facilitar o processo de compra online.
- **Sistema de Cadastro e Login** para acesso personalizado.
- **Painel Administrativo** para gestão de produtos e usuários.
- **Perfis de Usuários** com histórico de compras.

## Funcionalidades Principais

### 1. Sistema de Cadastro e Login
Os usuários podem criar uma conta e fazer login através de um sistema de autenticação seguro. Uma vez autenticado, o usuário tem acesso a um perfil personalizado, onde pode gerenciar suas informações pessoais e histórico de compras.

### 2. Carrinho de Compras
O carrinho permite que os usuários adicionem produtos durante a navegação no site e revisem os itens antes de finalizar a compra. O sistema calcula o total da compra automaticamente e suporta atualizações de quantidades e remoção de itens.

### 3. Catálogo de Produtos
O site apresenta um catálogo detalhado, categorizado por tipo de hardware e periféricos. Entre os principais produtos, estão listados:

- **CPU**: Processadores.
- **GPU**: Placas de vídeo.
- **Placas Mãe**: Componentes de placas-mãe.
- **RAM**: Memórias RAM.
- **Periféricos**: Incluindo mouse, teclado, monitores, fones de ouvido (headsets).

Cada categoria de produtos possui páginas dedicadas com descrições detalhadas e imagens.

### 4. Busca de Produtos
Os usuários podem procurar produtos utilizando a barra de busca, que filtra os resultados com base em palavras-chave ou categorias, facilitando a navegação pelo inventário de hardware e periféricos.

### 5. Perfis de Usuários Personalizados
Cada usuário cadastrado possui um perfil único onde pode gerenciar:

- **Dados pessoais**: Nome, email, e informações de contato.
- **Histórico de Compras**: Histórico detalhado de compras passadas, permitindo reordens e revisões.

### 6. Painel Administrativo
O sistema oferece um painel administrativo, acessível apenas para administradores, onde é possível:

- **Gerenciar Produtos**: Adicionar, editar ou remover produtos do catálogo.
  
## Requisitos de Instalação

### 1. Clone o repositório:
```bash
git clone https://github.com/iYoNuttxD/Kabo
```

### 2. Configuração do Servidor Local:

- Instale o XAMPP ou qualquer outro servidor local que suporte PHP e MySQL.
- Coloque os arquivos do projeto na pasta de acesso do servidor (`htdocs` no caso do XAMPP).

### 3. Configuração do Banco de Dados:

- Crie um banco de dados MySQL.
- Importe o arquivo `database.sql` localizado na raiz do projeto para configurar as tabelas e dados iniciais.
- No arquivo `connection.php`, configure as credenciais de acesso ao banco de dados:
  ```php
  $servername = "localhost";
  $username = "root";
  $password = "";
  $dbname = "kabo";
  ```

### 4. Inicie o Servidor:
Acesse o projeto através do navegador usando:
```bash
http://localhost/kabo/index.php
```

## Tecnologias Utilizadas

- **PHP**: Usado para o backend e gerenciamento da lógica do servidor.
- **MySQL**: Banco de dados utilizado para armazenar informações dos produtos, usuários e pedidos.
- **HTML5/CSS3**: Utilizados para a estruturação e estilização das páginas do site.
- **JavaScript**: Responsável pelas interações dinâmicas, como validação de formulários e manipulação do DOM.
