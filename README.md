# 🧠 SQL Curso Interativo – Desafios com E-commerce

Bem-vindo ao repositório **SQL Curso Interativo com base em um e-commerce fictício**!  
Aqui você encontrará desafios práticos do **nível básico ao intermediário** focados em **raciocínio lógico, joins, agregações e subconsultas** usando SQL.

---

## 📚 Sobre o Projeto

Este curso interativo foi criado com o objetivo de:

- Ajudar iniciantes e intermediários a praticarem SQL de forma aplicada e divertida
- Simular cenários reais de análise de dados com uma base de e-commerce
- Estimular a resolução de problemas através da lógica e criatividade
- Criar um portfólio público com boas práticas de modelagem, queries e explicações

---

## 🗃️ Estrutura de Dados

O banco de dados simula uma loja online e é composto pelas seguintes tabelas:

| Tabela         | Descrição                          |
|----------------|------------------------------------|
| `clientes`     | Dados dos clientes                 |
| `produtos`     | Catálogo de produtos               |
| `pedidos`      | Pedidos feitos pelos clientes      |
| `itens_pedido` | Itens individuais de cada pedido   |
| `avaliacoes`   | Avaliações de clientes nos produtos|

📁 Os arquivos `.csv` estão disponíveis em `./banco_dados/`.

---

## 🚀 Como Usar

Você pode executar os exercícios localmente com **SQLite**, **PostgreSQL**, ou usar ferramentas online como:

- [SQLite Online](https://sqliteonline.com/)
- [DB Fiddle](https://www.db-fiddle.com/)
- [Mode SQL Editor](https://mode.com/sql-editor/)

### 👉 Passo a passo com SQLite:

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/sql-curso-interativo-ecommerce.git
cd sql-curso-interativo-ecommerce

# 2. (Opcional) Crie o banco em SQLite
sqlite3 ecommerce.db

# 3. Importe os dados
.mode csv
.import banco_dados/clientes.csv clientes
.import banco_dados/produtos.csv produtos
.import banco_dados/pedidos.csv pedidos
.import banco_dados/itens_pedido.csv itens_pedido
.import banco_dados/avaliacoes.csv avaliacoes
