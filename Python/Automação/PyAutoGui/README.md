# 🤖 PyAutoGUI — Automação de Interface Gráfica com Python

Esta pasta documenta o estudo da biblioteca **PyAutoGUI**, utilizada para automação de tarefas em ambiente desktop por meio do controle programático de mouse e teclado.

O foco principal deste material está no aprendizado da biblioteca, na compreensão de seus recursos e na aplicação prática de seus principais comandos.


## 📚 Sobre a Biblioteca

O **PyAutoGUI** é uma biblioteca Python voltada para automação de interfaces gráficas (GUI).  
Ela permite simular interações humanas com o sistema operacional, como:

- Movimentação do mouse;
- Cliques;
- Digitação automática;
- Pressionamento de teclas;
- Combinação de atalhos;
- Captura de posição da tela.

Essa abordagem é útil para automatizar tarefas repetitivas quando não há integração direta via API ou acesso estruturado ao sistema.

Entretando, devemos levar em considerção alguns aspectos técnicos relevantes, como:

- A automação depende da resolução e layout da tela;
- Mudanças visuais podem comprometer a execução;
- É fundamental controlar o tempo entre ações;
- Scripts automatizados devem ser executados com cautela.

A biblioteca é especialmente indicada para:

- Automação simples de tarefas repetitivas;
- Protótipos;
- Rotinas internas;
- Testes automatizados básicos.


## 📗 Estudo de Caso

### 📌 Contexto
Todos os dias, o sistema atualiza as vendas do dia anterior.
O seu trabalho diário, como analista, é enviar um e-mail para a diretoria, assim que começar a trabalhar, com o faturamento e a quantidade de produtos vendidos no dia anterior. O sistema disponibiliza as vendas no drive da empresa.

### 🎯 Desafio Proposto

Automatizar o processo de cadastro de informações em um sistema, simulando:

1. Abertura do navegador;
2. Acesso ao sistema;
3. Login automatizado;
4. Navegação até área de cadastro;
5. Inserção automática de dados.

O exercício permitiu consolidar:

- Sequenciamento lógico de comandos;
- Sincronização entre ações;
- Controle completo de mouse e teclado via script.



## 🛠️ Tecnologias Utilizadas

- Python
- PyAutoGUI
- Biblioteca `time`
- Pandas


