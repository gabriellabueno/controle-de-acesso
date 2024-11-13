<h1 align="center"> :closed_lock_with_key: Controle de Acesso </h1>
<div align="center">

[![ACESSE AQUI](https://img.shields.io/badge/ACESSE%20AQUI-black?style=for-the-badge&)](https://www.link-website-projeto.com/)  

</div>

Este projeto consiste em um sistema de Controle de Acesso que integra um software desktop desenvolvido em Java e um microcontrolador Arduino programado em C++. O sistema permite gerenciar o acesso de pessoas por meio de um cadastro que inclui nome, CPF e uma senha numérica de 6 dígitos.

O projeto foi desenvolvido para a disciplina de Programação Orientada a Objetos e apresentado durante a VI Feira do Conhecimento da FATEC Guarulhos.

## ✔️ Funcionalidades

- **CRUD de Pessoas**: O software permite cadastrar, buscar, alterar e excluir registros de pessoas que terão acesso.
- **Validação de Senha**: O sistema valida a senha informada pelo usuário e, com base nessa validação, envia um sinal ao Arduino.
- **Feedback Visual e Sonoro**:
  - **Acesso Permitido**:
    - LED verde aceso.
    - Buzzer emite um BIP específico.
    - Servo motor gira 90º, liberando a entrada.
  - **Acesso Negado**:
    - LED vermelho aceso.
    - Buzzer emite um BIP de negação.
    - Servo motor permanece parado, não liberando o acesso.

<div align="center">
    <img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/cadastro.png" width="400px" alt="Tela de Cadastro">  
    
    <img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/controle.png" width="400px" alt="Tela de Controle">  
    
    <img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/circuito-tinkercad" width="400px" alt="Circuito no Tinkercad">  
    <img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/circuito-fisico" width="400px" alt="Circuito Físico">  
</div>

<div align="center">
    <img src="/printscreen.png" width="400px" alt="Imagem do Projeto centralizada">  
</div>

## :hammer_and_wrench: Tecnologias

- **Java**: Desenvolvimento do software desktop.
- **Swing**: Interface gráfica do usuário..
- **C++**: Programação do Arduino.
- **Arduino**: Controlar a catraca de acesso.


