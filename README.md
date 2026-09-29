# TaskManager

Sistema desktop para gerenciamento de tarefas e agendamentos desenvolvido em Python utilizando a biblioteca Tkinter.

O projeto foi criado como atividade prática para aplicar conceitos de programação, interfaces gráficas, funções, eventos e manipulação de dados.

---

## Sobre o projeto

O TaskManager permite que o usuário cadastre tarefas, defina prioridades, acompanhe o status das atividades e registre compromissos na agenda.

A aplicação possui uma interface simples, organizada e fácil de utilizar.

---

## Funcionalidades

### Gerenciamento de tarefas

- Cadastro de novas tarefas;
- Definição de título;
- Cadastro de descrição;
- Informações sobre o responsável;
- Definição de prioridade;
- Cadastro de data e horário;
- Seleção de status;
- Visualização das tarefas em uma tabela;
- Marcação de tarefas como concluídas;
- Exclusão de tarefas;
- Contadores automáticos no Dashboard.

### Sistema de agenda

- Cadastro de compromissos;
- Registro de título;
- Cadastro de data;
- Cadastro de horário;
- Registro do local;
- Visualização dos próximos agendamentos.

### Validações

O sistema realiza validações básicas antes de salvar os dados:

- O título da tarefa é obrigatório;
- A data da tarefa é obrigatória;
- O horário da tarefa é obrigatório;
- O título do compromisso é obrigatório.

As mensagens de aviso são exibidas utilizando `messagebox`.

---

## Tecnologias utilizadas

- Python 3;
- Tkinter;
- ttk;
- Programação orientada a objetos;
- Listas e dicionários;
- Eventos e funções;
- Interface gráfica desktop.

---

## Componentes Tkinter utilizados

Durante o desenvolvimento foram utilizados os seguintes componentes:

| Componente | Utilização |
|---|---|
| `Tk` | Criação da janela principal |
| `Label` | Exibição de textos e títulos |
| `Entry` | Entrada de informações curtas |
| `Text` | Campo para descrição |
| `Button` | Execução de ações |
| `Frame` | Organização dos elementos |
| `Combobox` | Seleção de prioridade e status |
| `Treeview` | Exibição das tarefas em formato de tabela |
| `messagebox` | Avisos e mensagens ao usuário |

---

## Requisitos

Para executar o projeto, é necessário ter instalado:

- Python 3.9 ou superior;
- Tkinter.

No Ubuntu ou Debian, instale o Tkinter com o comando:

```bash
sudo apt install python3-tk
```

No Windows, o Tkinter normalmente já é instalado junto com o Python.

---

## Como executar o projeto

1. Clone este repositório:

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
```

2. Acesse a pasta do projeto:

```bash
cd TaskManager
```

3. Execute o programa:

```bash
python main_simples.py
```

No Linux, também pode ser necessário utilizar:

```bash
python3 main_simples.py
```

---

## Estrutura do projeto

```text
TaskManager/
│
├── main_simples.py
├── main.py
├── tarefas.json
└── README.md
```

### Arquivos principais

- `main_simples.py`: versão simplificada da aplicação;
- `main.py`: versão mais completa do sistema;
- `tarefas.json`: arquivo utilizado para armazenar os dados na versão completa;
- `README.md`: documentação do projeto.

---

## Como utilizar

1. Execute o arquivo `main_simples.py`;
2. Acesse a opção **Tarefas** no menu lateral;
3. Clique no botão **Nova tarefa**;
4. Preencha os dados solicitados;
5. Clique em **Salvar tarefa**;
6. Selecione uma tarefa na tabela;
7. Utilize os botões **Concluir** ou **Excluir**;
8. Acesse a opção **Agenda** para cadastrar compromissos.

---

## Dashboard

O Dashboard apresenta automaticamente:

- Quantidade total de tarefas;
- Quantidade de tarefas pendentes;
- Quantidade de tarefas concluídas;
- Lista das tarefas cadastradas.

---

## Observação

A versão `main_simples.py` armazena os dados apenas enquanto o programa está aberto.

Ao fechar o programa, as informações cadastradas são apagadas.

A versão mais completa, presente no arquivo `main.py`, possui recursos adicionais, como:

- Salvamento em arquivo JSON;
- Filtros;
- Pesquisa de tarefas;
- Edição de tarefas;
- Dashboard mais completo;
- Organização visual aprimorada.

---

## Objetivo acadêmico

O objetivo deste projeto é praticar os seguintes conceitos:

- Criação de interfaces gráficas com Tkinter;
- Criação de janelas;
- Organização de elementos com `Frame`;
- Utilização de botões e eventos;
- Criação de funções;
- Manipulação de listas e dicionários;
- Validação de dados;
- Uso de tabelas com `Treeview`;
- Desenvolvimento de aplicações desktop em Python.

---

## Autor

Desenvolvido por Heloisa Bolognesi.

Projeto desenvolvido para fins acadêmicos.
