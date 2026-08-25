# Tabelas📅

## Dicionario de Dados

| Entidade  | Atributo     | Tipo    | Tamanho | Descrição                  |
| --------- | ------------ | ------- | ------- | -------------------------- |
| Motorista | id_motorista | INT     | -       | Identificador do motorista |
| Motorista | nome         | VARCHAR | 100     | Nome do motorista          |
| Motorista | cpf          | VARCHAR | 14      | CPF do motorista           |
| Motorista | telefone     | VARCHAR | 15      | Telefone do motorista      |
| Motorista | cnh          | VARCHAR | 20      | Número da CNH              |
| Veículo   | id_veiculo   | INT     | -       | Identificador do veículo   |
| Veículo   | placa        | VARCHAR | 8       | Placa do veículo           |
| Veículo   | modelo       | VARCHAR | 50      | Modelo do veículo          |
| Veículo   | capacidade   | INT     | -       | Capacidade de carga        |
| Veículo   | ano          | INT     | 4       | Ano do veículo             |
| Rota      | id_rota      | INT     | -       | Identificador da rota      |
| Rota      | origem       | VARCHAR | 100     | Local de origem            |
| Rota      | destino      | VARCHAR | 100     | Local de destino           |
| Rota      | distancia    | DECIMAL | 10,2    | Distância da rota em km    |
| Rota      | data         | DATE    | -       | Data da rota               |
| Rota      | id_motorista | INT     | -       | Motorista responsável      |
| Rota      | id_veiculo   | INT     | -       | Veículo utilizado          |

--- 

## Motorista

| id_motorista | nome            | cpf            | telefone    | cnh         |
| ------------ | --------------- | -------------- | ----------- | ----------- |
| 1            | João Silva      | 123.456.789-00 | 19999990001 | 12345678901 |
| 2            | Carlos Souza    | 234.567.890-11 | 19999990002 | 23456789012 |
| 3            | Marcos Oliveira | 345.678.901-22 | 19999990003 | 34567890123 |
| 4            | Pedro Santos    | 456.789.012-33 | 19999990004 | 45678901234 |

---

## Rotas

| id_rota | origem    | destino        | distancia | data       | id_motorista | id_veiculo |
| ------- | --------- | -------------- | --------- | ---------- | ------------ | ---------- |
| 1       | Campinas  | São Paulo      | 100.50    | 01/08/2026 | 1            | 1          |
| 2       | Campinas  | Santos         | 170.20    | 02/08/2026 | 2            | 2          |
| 3       | São Paulo | Curitiba       | 408.70    | 03/08/2026 | 3            | 3          |
| 4       | Campinas  | Ribeirão Preto | 220.40    | 04/08/2026 | 4            | 4          |
| 5       | Santos    | São Paulo      | 72.30     | 05/08/2026 | 1            | 2          |
| 6       | Curitiba  | Campinas       | 530.60    | 06/08/2026 | 2            | 1          |
| 7       | Campinas  | Sorocaba       | 85.10     | 07/08/2026 | 3            | 4          |
| 8       | São Paulo | Campinas       | 9.80      | 08/08/2026 | 4            | 3          |

 ---

 ## Veiculos

 | id_veiculo | placa   | modelo                   | capacidade | ano  |
| ---------- | ------- | ------------------------ | ---------- | ---- |
| 1          | ABC1D23 | Volvo FH 540             | 30         | 2022 |
| 2          | DEF4E56 | Scania R450              | 28         | 2021 |
| 3          | GHI7F89 | Mercedes Actros          | 25         | 2023 |
| 4          | JKL0G12 | Volkswagen Constellation | 20         | 2020 |
