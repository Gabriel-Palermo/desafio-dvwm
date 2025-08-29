*📝 Gerenciador de Tarefas (Laravel CRUD)*

Este projeto é um sistema simples de gerenciamento de tarefas desenvolvido em Laravel.
Ele possui operações CRUD completas (Criar, Listar, Editar, Excluir) e agora conta com uma nova funcionalidade de status de tarefa com filtros e busca.

🚀 Funcionalidades

Criar, editar, listar e excluir tarefas.

Cada tarefa possui:

Título (obrigatório)

Descrição (opcional)

Status: pendente, em andamento ou concluída.

Marcar tarefa como concluída/reabrir direto na listagem.

Filtro por status (pendentes, em andamento, concluídas, todas).

Busca por título na lista de tarefas.

Interface simples utilizando Blade Templates + Bootstrap 5.

📂 Estrutura da Atualização

Migration: adicionada coluna status na tabela tarefas.

Model (Tarefa.php): liberado status e descricao em $fillable.

Controller (TarefaController.php):

Novo método toggle() para concluir/reabrir tarefa.

Suporte a filtros e busca no método index().

Views:

index.blade.php: adicionados botão concluir/reabrir, filtro e busca.

create.blade.php e edit.blade.php: adicionados campos de descrição e status.

show.blade.php: exibindo também descrição e status.
