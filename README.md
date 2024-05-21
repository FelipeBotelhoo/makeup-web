## Sistema de Gerenciamento de Salão de Maquiagem

### Descrição
Este é um projeto final desenvolvido para o curso de Técnico de Informática no SENAC.<br>
O sistema foi projetado para gerenciar um salão de maquiagem fictício, onde é possível administrar informações dos usuários, agendamentos, funcionários e serviços oferecidos.<br>
Este projeto simula um ambiente real de um salão de maquiagem, facilitando a organização e administração do negócio.
O sistema é intuitivo e fácil de usar, garantindo que todas as operações do salão possam ser gerenciadas a partir de uma interface única e centralizada.

### Funcionalidades
- Gerenciamento de Usuários: Cadastro, edição e exclusão de clientes.
- Agendamentos: Sistema de marcação e gerenciamento de horários.
- Gerenciamento de Funcionários: Controle de cadastro e horários dos funcionários.
- Serviços: Administração dos serviços oferecidos pelo salão.
- Autenticação e Autorização: Controle de acesso com diferentes níveis de permissão (admin, funcionários, clientes).

### Tecnologias Utilizadas
- Linguagem: PHP
- Banco de Dados: MySQL
- Front-end: HTML, CSS, JavaScript
- Frameworks e Bibliotecas: Bootstrap, jQuery
- Servidor: Apache



### Pré-requisitos
Para executar este projeto, você precisará das seguintes ferramentas instaladas em sua máquina:

XAMPP ou similar (Apache, MySQL, PHP)
Instalação
1. Clone o Repositório
- Clone o repositório do projeto para sua máquina local:
     ```bash
   git clone [URL do repositório]
   ````

2. Mova o Projeto para o Diretório do Servidor
- Mova o projeto clonado para o diretório "htdocs" do XAMPP:

3. Inicie o Servidor Apache e MySQL
- Abra o XAMPP e inicie os módulos "Apache" e "MySQL".

Configuração do Banco de Dados
4. Crie o Banco de Dados
Abra o phpMyAdmin através do XAMPP e crie um novo banco de dados chamado salao_maquiagem.

5. Importe o Banco de Dados
No phpMyAdmin, selecione o banco de dados salao_maquiagem e importe o arquivo database.sql localizado no diretório database do projeto.


Execução do Projeto

6. Acesse o Projeto no Navegador
Abra seu navegador e acesse o projeto através do endereço:

```bash
http://localhost/nome-do-repositorio
   ````

### Como Usar
1. Faça login utilizando as credenciais fornecidas.
2. Utilize o painel de controle para gerenciar usuários, agendamentos, funcionários e serviços.
