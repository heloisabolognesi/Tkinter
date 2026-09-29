TaskManager Simples

Aplicação desktop de tarefas e agendamentos desenvolvida em Python com Tkinter.

Este projeto foi criado para praticar os principais componentes de uma interface gráfica em Python.

Funcionalidades

Tarefas

•
Cadastrar novas tarefas;

•
Informar título, descrição, responsável, data e horário;

•
Definir prioridade: Alta, Média ou Baixa;

•
Definir status: Pendente, Em andamento ou Concluída;

•
Visualizar tarefas em uma tabela;

•
Marcar uma tarefa como concluída;

•
Excluir tarefas;

•
Exibir contadores no Dashboard.

Agenda

•
Cadastrar compromissos;

•
Informar título, data, horário e local;

•
Visualizar os próximos agendamentos.

Componentes do Tkinter utilizados

•
Tk — janela principal;

•
Label — textos e títulos;

•
Entry — campos de texto curtos;

•
Text — campo de descrição;

•
Button — botões e ações;

•
Frame — organização da interface;

•
Combobox — seleção de prioridade e status;

•
Treeview — tabela de tarefas;

•
messagebox — mensagens de aviso e confirmação.

Requisitos

•
Python 3.9 ou superior;

•
Tkinter instalado.

No Ubuntu ou Debian, instale o Tkinter com:

Bash


sudo apt install python3-tk



No Windows, o Tkinter normalmente já vem instalado junto com o Python.

Como executar

Abra o terminal na pasta do projeto e execute:

Bash


python3 main_simples.py



No Windows, também pode ser utilizado:

Bash


python main_simples.py



Estrutura do projeto

Plain Text


TaskManager/
├── main_simples.py
├── main.py
├── tarefas.json
└── README.md



O arquivo recomendado para esta versão simples é o main_simples.py.

Como usar

1.
Execute o arquivo main_simples.py;

2.
Na tela inicial, consulte os contadores e as tarefas cadastradas;

3.
Acesse Tarefas no menu lateral;

4.
Clique em Nova tarefa;

5.
Preencha os campos obrigatórios;

6.
Clique em Salvar tarefa;

7.
Selecione uma tarefa na tabela para concluí-la ou excluí-la;

8.
Acesse Agenda para cadastrar compromissos.

Validações

O programa não permite salvar:

•
Uma tarefa sem título;

•
Uma tarefa sem data;

•
Uma tarefa sem horário;

•
Um compromisso sem título.

As mensagens de validação são exibidas usando messagebox.

Observação importante

Esta versão armazena os dados apenas enquanto o programa está aberto. Ao fechar o programa, as listas de tarefas e agendamentos são reiniciadas.

A versão mais completa do projeto utiliza o arquivo tarefas.json para manter os dados salvos.

Objetivo acadêmico

O objetivo do projeto é praticar:

•
Criação de janelas com Tkinter;

•
Organização de componentes usando Frame;

•
Criação de eventos com command;

•
Uso de funções para cadastrar, concluir e excluir dados;

•
Manipulação de listas e dicionários em Python;

•
Construção de uma interface gráfica simples e funcional.

