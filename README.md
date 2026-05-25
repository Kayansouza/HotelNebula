<img width="1080" height="1288" alt="Capa do Hotel Nebula" src="https://github.com/user-attachments/assets/dd77d976-84a7-41ae-b8bb-f101f30af7f0" />

# 🌌 Hotel Nebula

Sistema de gerenciamento hoteleiro desenvolvido com banco de dados NoSQL utilizando **MongoDB**.  
O projeto tem como objetivo organizar informações de hóspedes, quartos e reservas de forma simples e flexível.

## 📋 Sobre o projeto

O **Hotel Nebula** simula o funcionamento básico de um hotel, permitindo armazenar dados importantes para o gerenciamento das hospedagens.

A modelagem do banco utiliza documentos e arrays, recursos importantes do MongoDB para representar informações de forma organizada.

## 🗂️ Coleções principais

| Coleção | Descrição |
|---|---|
| `hospedes` | Armazena os dados dos hóspedes |
| `quartos` | Armazena informações dos quartos e disponibilidade |
| `reservas` | Registra as reservas realizadas |

## 📁 Estrutura do banco de dados

### Hóspedes

```json
{
  "nome": "João da Silva",
  "cpf": "123.456.789-00",
  "email": "joao@email.com",
  "telefone": "(11) 99999-9999",
  "endereco": {
    "rua": "Rua Exemplo, 100",
    "cidade": "São Paulo",
    "estado": "SP",
    "cep": "01000-000"
  },
  "data_cadastro": "2026-05-25"
}
