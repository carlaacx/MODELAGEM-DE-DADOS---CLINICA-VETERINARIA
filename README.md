# MODELAGEM-DE-DADOS---CLINICA-VETERINARIA
TRABALHO DE BANCO DE DADOS ULTILIZANDO MYSQL WORKBENCH PARA MODELAGEM PRATICA

Sistema de Clínica Veterinária 
Este repositório contém o modelo de banco de dados relacional desenvolvido no MySQL Workbench para o gerenciamento de uma clínica veterinária.

 Sobre o Projeto
O projeto modela as entidades principais para o funcionamento de um consultório veterinário, controlando clientes, seus animais, veterinários e o registro de consultas.

 Estrutura do Banco de Dados (Entidades)
CLIENTE: Armazena os dados dos donos dos animais (cpf, nome, telefone).

ANIMAL: Registra os pets vinculados aos seus respectivos donos (codigo, nome, data de nascimento, raça, cpf_cliente).

VETERINARIO: Cadastra os profissionais da clínica (crm, nome, data de admissão, salário).

CONSULTA: Controla o histórico e agendamento de atendimentos médicos (crm_veterinario, codigo_animal, data, hora, motivo).

 Tecnologias Utilizadas
MySQL Workbench (Modelagem EER e Geração de SQL)

MySQL / SQL (Banco de dados relacional)

 Como Utilizar
Abra o arquivo do modelo (.mwb) no MySQL Workbench se desejar visualizar o diagrama EER.

Utilize a ferramenta de Forward Engineering no Workbench para gerar o script SQL e criar as tabelas no seu servidor MySQL local.
