[![English Translation](https://img.shields.io/badge/English%20Translation-2d314a?style=for-the-badge)](https://github.com/gabriellabueno/controle-de-acesso/blob/main/README-translation.md) 


<h1 align="center"> :closed_lock_with_key: Controle de Acesso </h1>

Este projeto consiste em um sistema de Controle de Acesso que integra um software desktop desenvolvido em Java e um microcontrolador Arduino programado em C++. O sistema permite gerenciar o acesso de pessoas por meio de um cadastro que inclui nome, CPF e uma senha numérica de 6 dígitos. O sistema conta com persistência de dados utilizando o MySQL como banco de dados para a aplicação.

> Projeto desenvolvido para a disciplina de Programação Orientada a Objetos e apresentado durante a VI Feira do Conhecimento da FATEC Guarulhos.

<h2 align="center">✔️ Funcionalidades</h1>

- **CRUD de Pessoas**: O software permite cadastrar, buscar, alterar e excluir registros de pessoas que terão acesso.
- **Validação de Senha**: O sistema valida a senha informada pelo usuário e, com base nessa validação, envia um sinal ao Arduino.
- **Feedback Visual e Sonoro**:
  - *Acesso Permitido*:
    - LED verde aceso.
    - Buzzer emite um BIP específico.
    - Servo motor gira 90º, liberando a entrada.
  - *Acesso Negado*:
    - LED vermelho aceso.
    - Buzzer emite um BIP de negação.
    - Servo motor permanece parado, não liberando o acesso.

<div align="center">

### Interface Gráfica


<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/cadastro.png" alt="Tela de Cadastro">  

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/controle.png" alt="Tela de Controle">  


### Estrutura Física
     
[![Circuito no Tinkercad](https://img.shields.io/badge/Circuito%20no%20Tinkercad-orange?style=for-the-badge&)](https://www.tinkercad.com/things/0K7h18Z1G8F-controle-de-acesso)  

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/circuito-tinkercad.png" width="500px" alt="Circuito no Tinkercad">  

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/circuito-fisico.jpeg" width="300px" alt="Circuito Físico">  
</div>

<h2 align="center"> :hammer_and_wrench: Tecnologias e Componentes </h2>

- **Sofwtare Desktop**
  - **Java:** Linguagem de Programação.
  - **Swing:** Interface gráfica do usuário..
- **Banco de Dados**
  - **XAMPP:** Sistema de Gerenciamento de Banco de Dados (SGBD) do projeto.
  - **MySQL:** Banco de dados do sistema.
- **Estrutura Física**
  - **C++:** Programação do Arduino.
  - **Arduino Uno**: Controlar a catraca de acesso.
    - 2 LEDs (verde e vermelho); 2 resistores de 330 Ω (Ohms); Buzzer Piezo; Servo motor Posicional; Protoboard; Jumpers.
