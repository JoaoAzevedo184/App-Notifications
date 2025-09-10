# ✅ To-Do List App

Um aplicativo simples de lista de tarefas com notificações, desenvolvido em **Kotlin** no **Android Studio**.  
Projeto acadêmico feito em dupla para prática de desenvolvimento mobile e uso de Git/GitHub.

---

## 🚀 Tecnologias
- Kotlin
- Android Studio
- Git/GitHub

---

## 🎯 Funcionalidades
- Adicionar tarefas com título e horário.
- Listar tarefas em ordem cronológica.
- Notificação no horário definido pelo usuário.
- Remover/editar tarefas (opcional, se houver tempo).

---

## 📂 Estrutura do Projeto
- `MainActivity.kt` → Tela principal com a lista.
- `Task.kt` → Data class da tarefa.
- `TaskAdapter.kt` → Adapter do RecyclerView.
- `NotificationHelper.kt` → Gerencia as notificações.
- `TaskRepository.kt` → Armazena as tarefas.

# 📌 Estrutura do Projeto

```
to-do-list-app/
│
├── .gitignore               # Arquivos/pastas a serem ignorados pelo Git
├── README.md                # Documentação inicial do projeto
├── app/                     # Código principal do Android
│   ├── build.gradle
│   └── src/
│       ├── main/
│       │   ├── AndroidManifest.xml
│       │   ├── java/com/seuprojeto/todolist/
│       │   │   ├── MainActivity.kt         # Tela principal
│       │   │   ├── Task.kt                 # Data class para representar tarefas
│       │   │   ├── TaskAdapter.kt          # Adapter para RecyclerView
│       │   │   ├── NotificationHelper.kt   # Classe utilitária para notificações
│       │   │   └── TaskRepository.kt       # Armazenamento simples (em memória ou SQLite/Room)
│       │   └── res/
│       │       ├── layout/
│       │       │   ├── activity_main.xml   # Layout principal
│       │       │   └── item_task.xml       # Layout de cada item da lista
│       │       └── values/
│       │           ├── colors.xml
│       │           ├── strings.xml
│       │           └── themes.xml
│       └── test/                           # Testes unitários
│
├── docs/                   # Pasta para documentação
│   ├── requisitos.md       # Lista de requisitos funcionais e não funcionais
│   ├── arquitetura.md      # Explicação da arquitetura escolhida
│   └── tarefas.md          # Organização do trabalho em dupla
│
└── build.gradle
```

---

## 📌 Organização do Trabalho (Dupla)
- Pessoa 1: Estrutura do projeto, telas, RecyclerView, Adapter.
- Pessoa 2: Notificações, lógica de agendamento, repositório de dados.
- Ambos: Testes, documentação e revisão de código.

---

## 📖 Como rodar o projeto
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/to-do-list-app.git
    ````

2. Abra no Android Studio.
3. Execute em um emulador ou dispositivo físico.
