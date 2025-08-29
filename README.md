# 📝 Gerenciador de Tarefas (Laravel CRUD)

Este é um projeto simples de **Gerenciador de Tarefas** desenvolvido em **Laravel**.  
O sistema utiliza o padrão **MVC**, migrations, Eloquent ORM e Blade Templates para gerenciamento de tarefas.

---

## 🚀 Funcionalidades
- Criar, editar, listar e excluir tarefas.
- Cada tarefa possui:
  - **Título** (obrigatório)  
  - **Descrição** (opcional)  
  - **Status**: `pendente`, `em andamento` ou `concluída`.
- **Marcar tarefa como concluída/reabrir** diretamente na listagem.
- **Filtro por status** (todas, pendentes, em andamento, concluídas).
- **Busca por título**.
- Interface responsiva com **Bootstrap 5**.

---

## 📂 Atualização mais recente
- Adicionada coluna **status** na tabela `tarefas`.
- Criado botão para **alternar status** (Concluir/Reabrir).
- Implementado **filtro por status** na listagem.
- Implementado **campo de busca** por título.
- Views de criar/editar agora incluem **descrição e status**.

---
