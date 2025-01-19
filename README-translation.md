<h1 align="center"> :closed_lock_with_key: Access Control </h1>

This project consists of an Access Control system that integrates a desktop software developed in Java and an Arduino microcontroller programmed in C++. The system allows managing people's access through a registration that includes name, CPF, and a 6-digit numeric password. The system has data persistence using MySQL as the database for the application.

> Project developed for the Object-Oriented Programming course and presented during the VI Knowledge Fair at FATEC Guarulhos.

<h2 align="center">✔️ Features</h2>

- **CRUD for People**: The software allows registering, searching, modifying, and deleting records of people who will have access.
- **Password Validation**: The system validates the password provided by the user and, based on this validation, sends a signal to the Arduino.
- **Visual and Audio Feedback**:
  - *Access Granted*:
    - Green LED turns on.
    - Buzzer emits a specific BEEP.
    - Servo motor rotates 90º, allowing entry.
  - *Access Denied*:
    - Red LED turns on.
    - Buzzer emits a denial BEEP.
    - Servo motor remains stationary, not allowing access.

<div align="center">

### Graphical Interface

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/cadastro.png" alt="Registration Screen">  

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/controle.png" alt="Control Screen">  


### Physical Structure
     
[![Circuit in Tinkercad](https://img.shields.io/badge/Circuit%20in%20Tinkercad-orange?style=for-the-badge&)](https://www.tinkercad.com/things/0K7h18Z1G8F-controle-de-acesso)  

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/circuito-tinkercad.png" width="500px" alt="Circuit in Tinkercad">  

<img src="https://github.com/gabriellabueno/controle-de-acesso/blob/main/imagens/circuito-fisico.jpeg" width="300px" alt="Physical Circuit">  
</div>

<h2 align="center"> :hammer_and_wrench: Technologies and Components </h2>

- **Desktop Software**
  - **Java:** Programming language.
  - **Swing:** Graphical user interface.
- **Database**
  - **XAMPP:** Database Management System (DBMS) of the project.
  - **MySQL:** System database.
- **Physical Structure**
  - **C++:** Arduino programming.
  - **Arduino Uno**: Controls the access turnstile.
    - 2 LEDs (green and red); 2 resistors of 330 Ω (Ohms); Piezo Buzzer; Positional Servo Motor; Protoboard; Jumpers.
