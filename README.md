# controle-estoque-django

É um projeto final desenvolvido na faculdade referente ao curso de Python, para ser um  sistema de controle de estoque desenvolvido com Django.

# Principais funcionalidades implementadas:

Controle de entrada e saída de mercadorias

Alertas de estoque mínimo

Relatórios gerenciais personalizados

Módulo de inventário físico

**Diferenciais implementados**:
### 🔐 Matriz de Permissões

| Perfil          | Produtos | Movimentações | Relatórios | Configurações |
|-----------------|----------|---------------|------------|---------------|
|Administrador	| CRUD	| CRUD	| Completo	| Completo	| CRUD |
|Gerente	| CRUD	| CRUD	| Completo	| Visualização	| - |
|Operador	| Leitura	| Criar	| Básico	| -	| - |
|Auditor	| Leitura	| Leitura	| Completo	| -	| - |

### 🛠️ Tecnologias Utilizadas 
# Backend

- Django 5.1

- Django REST Framework

- Django Guardian (controle de permissões)

- Celery (para tarefas assíncronas)

# Frontend

- Bootstrap 5

- Chart.js (visualização de dados)

- DataTables (tabelas interativas)

# Banco de Dados

- PostgreSQL (produção)

- SQLite (desenvolvimento)

# Infraestrutura

- Docker (containerização)

- Gunicorn (servidor WSGI)

- Nginx (proxy reverso)

### 📦 Módulos Principais
# Gestão de Produtos

- Cadastro completo com múltiplas categorias

- Controle de códigos de barras

- Fotos e especificações técnicas

- Movimentações

- Entradas (comprovantes de compra)

- Saídas (vinculadas a pedidos)

- Transferências entre estoques

- Ajustes de inventário

# Relatórios

- Curva ABC de produtos

- Rotatividade de estoque

- Valores totais em inventário

# Histórico de movimentações

- Alertas

- Estoque abaixo do mínimo

- Produtos próximos do vencimento

- Inatividade de produtos
