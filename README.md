![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

[![Status](https://img.shields.io/badge/Status-Concluído-blue)]()

<h1 align="center">👓 Clínica Oftalmológica – Ophtamuls</h1>

Projeto em Laravel desenvolvido para a disciplina de Processo de Desenvolvimento de Software, juntamente com [Allan França](https://github.com/Allanfd12) e [Fernanda Barbosa](https://github.com/fernandabmf), utilizando de várias tecnologias complementares. E o design da aplicação foi criado por [Malu Miranda Fróes](https://github.com/malumirandafr) pelo Figma.

O sistema "Ophtamuls" consiste em uma aplicação Web integrada com Banco de Dados (MySQL) que permite gerenciar de forma completa (Criar, Editar, Atualizar e Excluir) Consultas guardando dados como data e hora da consulta agenda, assim como gerenciar os Médicos e Pacientes que estão envolvidos em cada uma das consultas, e seus respectivos dados. Além disso, possui um sistema de login com email e senha, e também é possível gerenciar os usuários do sistema.

Abaixo está descrito em detalhes o objetivo da aplicação e como as diferentes linguagens foram utilizadas em conjunto para desenvolver a aplicação completa. Para ver imagens do produto final do projeto, vá até a Galeria.

<h2>🎯 Objetivo</h2>

Foi feito o Levantamento de Requisitos para o sistema com um dono de uma clínica oftalmológica por meio de uma entrevista, a medida que nos explicou suas necessidades e dificuldades do sistema atual, fizemos como objetivo atender sua demanda e trazer um escopo de um sistema que seria mais intuitivo e mais rápido de ser utilizado por ele e pelos funcionários de sua empresa.

<h2>📚 Tecnologias e Bibliotecas</h2>

<h3><img width=20 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/laravel/laravel-plain.svg" /> Laravel</h3>

O Laravel é um software PHP livre e Open-Source feito para desenvolvimento Web, a aplicação foi desenvolvida primordialmente nele.

<h3><img width=20 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" /> Bootstrap</h3>

O Bootstrap é um framework web para desenvolvimento de componentes de interface e front-end para aplicações Web, por meio dele que os componentes da aplicação foram desenvolvidos, visando chegar o mais próximo do design proposto.

<h3><img width=20 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" /> JavaScript</h3>

O JavaScript é uma das principais tecnologias para desenvolvimento Web, e nesta aplicação foi essencial para realizar a validação dos dados ao cadastrar ou editar algum dado, evitando assim que dados fossem guardados de forma errada ou que dados únicos como CPF e Email fossem duplicados.

<h3><img width=20 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" /> jQuery e Select2</h3>

O Select2 é uma biblioteca que utiliza do jQuery para trazer a aplicação de um Select mais dinâmico e flexível, na aplicação ele foi utilizado para permitir selecionar os Médicos e Pacientes que estivem cadastrados no sistema de forma dinâmica ao usar de uma API.

Além disso, o jQuery também foi utilizado para fazer as 'inputs masks' do sistema.

<h3><img width=20 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" /> MySQL</h3>

A aplicação consta com um banco de dados relacional em MySQL, com tabelas para 'Consultas', 'Médicos', Usuários' e 'Pacientes'. As tabelas possuem relacionamentos entre si. A tabela 'Consultas' recebe o 'id' de um paciente e de um médico, e a tabela 'Médicos' recebe o 'id' de um usuário, já que todo médico cadastrado utilizará o sistema, mas também nem todo usuário será um médico, como por exemplo uma atendente da clínica.

<h2>📷 Galeria</h2>

![Página de Login](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/d7a58bd0-2c7f-417a-ab66-7455b4f588e6)
![Página Home](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/45c97eae-3417-4d1b-a022-3fcc51ea7645)
![Listagem de PACIENTE](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/897b5e70-9fed-4db0-9413-0901ae89372a)
![Pesquisar de PACIENTE](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/c8e00dfc-6bfb-4e98-9601-74963762680c)
![Criar MÉDICO](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/a61dce6f-924d-4d84-a456-f5ecd2c687f7)
![Editar PRONTUÁRIO](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/e686f1fc-b273-40ea-8c04-573261ce1ed2)
![Visualizar CONSULTA](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/9fe16ae0-1ebf-4a0d-a880-8bba73841234)
![Excluir USUÁRIO](https://github.com/sergiomnds/clinica-oftalmologica-laravel/assets/85349959/f7b43030-1492-4be6-bb8b-211fffa32c75)


