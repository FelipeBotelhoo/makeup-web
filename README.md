## Sistema de Gerenciamento de Salão de Maquiagem

### Descrição
Este é um projeto final desenvolvido para o curso de Técnico de Informática no SENAC.<br>
O sistema foi projetado para gerenciar um salão de maquiagem fictício, onde é possível administrar informações dos usuários, agendamentos, funcionários e serviços oferecidos.<br>
Este projeto simula um ambiente real de um salão de maquiagem, facilitando a organização e administração do negócio.
O sistema é intuitivo e fácil de usar, garantindo que todas as operações do salão possam ser gerenciadas a partir de uma interface única e centralizada.
<br>
### Funcionalidades
🔹 Gerenciamento de Usuários: Cadastro, edição e exclusão de clientes. <br>
🔹 Agendamentos: Sistema de marcação e gerenciamento de horários.<br>
🔹 Gerenciamento de Funcionários: Controle de cadastro e horários dos funcionários.<br>
🔹 Serviços: Administração dos serviços oferecidos pelo salão.<br>
🔹 Autenticação e Autorização: Controle de acesso com diferentes níveis de permissão (admin, funcionários, clientes).<br>
<br>
### Tecnologias Utilizadas
🔹 Linguagem: PHP<br>
🔹 Banco de Dados: MySQL<br>
🔹 Front-end: HTML, CSS, JavaScript<br>
🔹 Frameworks e Bibliotecas: Bootstrap, jQuery<br>
🔹 Servidor: Apache<br>


### Pré-requisitos
Para executar este projeto, você precisará das seguintes ferramentas instaladas em sua máquina:

XAMPP ou similar (Apache, MySQL, PHP)
Instalação
1. Clone o Repositório
Clone o repositório do projeto para sua máquina local:
  
     ```bash
   git clone [URL do repositório]
   ````

2. Mova o Projeto para o Diretório do Servidor <br>
🔹 Mova o projeto clonado para o diretório "htdocs" do XAMPP:
<br>
3. Inicie o Servidor Apache e MySQL<br>
🔹Abra o XAMPP e inicie os módulos "Apache" e "MySQL".
<br>
<br>

**É muito importante o START no APACHE e MySQL caso esteja utilizando o XAMPP </br>
e que o arquivo seja colocado dentro da pasta "htdocs"** </br></br>

<br>
4. Crie o Banco de Dados <br>
🔹 Abra o phpMyAdmin através do XAMPP e crie um novo banco de dados chamado <i>"maquiagem"</i>.
<br>

5. Importe o Banco de Dados <br>
🔹 No phpMyAdmin, selecione o banco de dados <i>"maquiagem"</i> e importe o arquivo database.sql localizado no diretório database do projeto.
<br>

### Execução do Projeto
6. Acesse o Projeto no Navegador <br>
🔹 Abra seu navegador e acesse o projeto através do endereço:

```bash
http://localhost/nome-do-repositorio
   ````

### Como Usar <br>
1. Faça login utilizando as credenciais fornecidas. <br>
2. Utilize o painel de controle para gerenciar usuários, agendamentos, funcionários e serviços.
