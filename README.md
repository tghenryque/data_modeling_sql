# 🗄️ Data Modeling SQL

Este repositório contém um projeto completo de **modelagem de banco de dados relacional** desenvolvido em **MySQL**, com foco em boas práticas de estruturação de tabelas, integridade referencial e organização de entidades e relacionamentos.

---

## 📘 Sobre o Projeto

O objetivo deste projeto é representar um **cenário real de uma oficina mecânica**, onde é necessário armazenar informações sobre **clientes, veículos, cores, telefones e serviços** realizados.  

O modelo foi criado de forma a demonstrar:
- Relações **1:N** (cliente → carro, carro → serviço)
- Relações **N:N** (carro ↔ cor, com tabela associativa)
- Aplicação de **chaves primárias, estrangeiras e constraints**
- Tratamento de **campos opcionais** (telefone do cliente)
- Criação de uma **VIEW** para consulta geral dos dados

---

## 🧩 Estrutura do Banco de Dados

Entidades principais:
| Entidade     | Descrição |
|---------------|------------|
| **CLIENTE**  | Armazena dados pessoais do cliente (nome, CPF, email, sexo). |
| **CARRO**    | Representa o veículo do cliente (modelo, marca, placa). |
| **COR**      | Contém as cores possíveis para os veículos. |
| **CARRO_COR**| Tabela associativa que relaciona carros e cores (N:N). |
| **TELEFONE** | Registra telefones opcionais dos clientes. |
| **SERVICO**  | Armazena os serviços realizados para cada carro. |

---

## 🧱 Modelo Lógico

O diagrama lógico foi desenvolvido no **StarUML**.

📁 Arquivos disponíveis:
- `modelo-logico.mdj` → Arquivo original do StarUML  
- `modelo-logico.png` → Imagem exportada do modelo

Exemplo do relacionamento N:N (carro ↔ cor):

