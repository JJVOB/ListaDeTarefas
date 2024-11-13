
## 📝 Projeto de Lista de Tarefas Completa

Este é um projeto de lista de tarefas desenvolvido com o framework Laravel, onde cada usuário pode gerenciar suas tarefas de forma personalizada. A aplicação permite criar, editar e visualizar tarefas, além de possuir um sistema de autenticação de usuários que permite que cada usuário tenha sua própria lista de tarefas.

# 📋 Funcionalidades
- Autenticação de Usuários:
- Cadastro de novos usuários
- Login e logout seguro
- Gestão de Tarefas:
- Criar novas tarefas
- Editar e atualizar tarefas existentes
- Listar todas as tarefas do usuário autenticado
- Marcar tarefas como concluídas
  
🚀 Tecnologias Utilizadas
- Laravel         -> Framework PHP para desenvolvimento web
- MySQL           -> Banco de dados para armazenamento de informações dos usuários e tarefas
- Bootstrap       -> Framework CSS para estilização (opcional)
- Blade Templates -> Engine de templates do Laravel para renderização de views


## 📂 Estrutura do Projeto

├── app/                    # Lógica de autenticação e gerenciamento de tarefas

├── database/               # Migrations e seeders para criação das tabelas

├── resources/

    │   ├── views/              # Views com templates Blade
    
├── routes/

    │   └── web.php             # Definição de rotas para navegação da aplicação
    
├── public/                 # Arquivos públicos (CSS, JS)

├── .env                    # Configurações de ambiente (credenciais, banco de dados)

└── README.md               # Documentação do projeto


## 🖥️ Telas da Aplicação

- Tela de Login e Cadastro: Permite que o usuário faça login ou registre uma nova conta.
- Tela de Listagem de Tarefas: Exibe todas as tarefas do usuário, com opções para adicionar, editar e remover.
- Tela de Edição de Tarefas: Permite a atualização das informações de uma tarefa existente.

## 📌 Funcionalidades Futuros
- Filtros de Tarefas: Filtrar tarefas por status (concluídas, pendentes, etc.)
- Compartilhamento de Tarefas: Opção para compartilhar tarefas entre usuários
- Notificações: Lembrar o usuário de tarefas próximas do prazo de conclusão

## 🔒 Segurança
- Este projeto segue as boas práticas de segurança do Laravel, como:

    - Proteção CSRF para evitar ataques de falsificação de solicitação.
    - Autenticação com Hashing de Senhas para garantir a segurança das credenciais dos usuários.


## By JJVOB

