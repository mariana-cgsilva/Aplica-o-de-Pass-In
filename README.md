# Pass-In - EN
pass.in

Pass-In is an application for managing participants in face-to-face events.

The tool enables the organizer to register an event and open a public registration page.

Registered participants can generate a credential for check-in on the day of the event.

The system will scan the participant's credential to allow entry to the event.

## Requirements

### Functional Requirements
- The organizer must be able to register a new event.
- The organizer must be able to view event data.
- The organizer must be able to view the list of participants.
- The participant must be able to register for an event.
- The participant must be able to view their registration badge.
- The participant must be able to check-in at the event.

### Business Rules
- The participant can only register for an event once.
- The participant can only register for events with available spots.
- The participant can only check-in to an event once.

### Non-Functional Requirements
- Check-in at the event will be performed through a QR code.

## API Documentation (Swagger)
For API documentation, please visit the following link: [API Documentation](https://nlw-unite-nodejs.onrender.com/docs)

## Database
In this application, we will use a relational database (SQL). For development environment, we will use SQLite for its ease of setup.


## ERD Diagram
ERD diagram of the database
![image](https://github.com/mariana-cgsilva/Pass-In/assets/142249220/ffaf5f20-28fc-4d58-bc0b-42a8dca89f71)



# Pass-In - PT
pass.in

O Pass-In é uma aplicação para gerenciar participantes em eventos presenciais.

A ferramenta permite que o organizador registre um evento e abra uma página de inscrição pública.

Os participantes registrados podem gerar uma credencial para check-in no dia do evento.

O sistema fará a leitura da credencial do participante para permitir a entrada no evento.

## Requisitos

### Requisitos Funcionais
- O organizador deve ser capaz de registrar um novo evento.
- O organizador deve ser capaz de visualizar dados do evento.
- O organizador deve ser capaz de visualizar a lista de participantes.
- O participante deve ser capaz de se inscrever em um evento.
- O participante deve ser capaz de visualizar sua credencial de inscrição.
- O participante deve ser capaz de fazer check-in no evento.

### Regras de Negócio
- O participante só pode se inscrever em um evento uma vez.
- O participante só pode se inscrever em eventos com vagas disponíveis.
- O participante só pode fazer check-in em um evento uma vez.

### Requisitos Não-Funcionais
- O check-in no evento será feito por meio de um código QR.

## Documentação da API (Swagger)
Para a documentação da API, visite o seguinte link: [Documentação da API](https://nlw-unite-nodejs.onrender.com/docs)

## Banco de Dados
Nesta aplicação, usaremos um banco de dados relacional (SQL). Para o ambiente de desenvolvimento, usaremos o SQLite pela facilidade de configuração.

## Diagrama ERD
Diagrama ERD do banco de dados
