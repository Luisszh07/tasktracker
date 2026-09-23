# TaskTracker

Sistema de linha de comando (CLI) para organização de tarefas pessoais, desenvolvido como parte do desafio cumulativo do Bootcamp II.

## Descrição

O TaskTracker foi criado para resolver um problema comum na rotina de um estudante: acumular tarefas pessoais e acadêmicas de forma desorganizada (anotações soltas, lembretes espalhados, memória), o que gera esquecimentos e falta de clareza sobre o que já foi feito e o que ainda está pendente.

Com o TaskTracker, é possível:
- Cadastrar tarefas com título, descrição, prioridade e prazo
- Visualizar todas as tarefas cadastradas, organizadas por status
- Garantir a consistência dos dados através de validações (título obrigatório, prioridade restrita a Alta/Média/Baixa)

Este projeto é cumulativo e está sendo desenvolvido em 3 fases:
- **Fase 1** — Planejamento lógico e arquitetural (concluída)
- **Fase 2** — Estruturação do repositório, versionamento com Git/GitHub e implementação em Python (etapa atual)
- **Fase 3** — Containerização com Docker e deploy final

## Tecnologias Utilizadas

- **Python 3** — linguagem principal do sistema
- **Git & GitHub** — controle de versão e hospedagem do código

## Estrutura do Projeto

```
tasktracker-projeto/
├── README.md              # Este arquivo
├── .gitignore              # Arquivos e pastas ignorados pelo Git
├── docs/
│   └── planejamento_logico.pdf   # Planejamento lógico da Fase 1
└── src/
    └── main.py             # Código-fonte principal da aplicação
```

## Como Instalar e Executar

### Pré-requisitos
- Ter o [Python 3](https://www.python.org/downloads/) instalado no computador

### Passo a passo

1. Clone este repositório:
```bash
git clone https://github.com/Luisszh07/tasktracker.git
```

2. Entre na pasta do projeto:
```bash
cd tasktracker
```

3. Execute a aplicação:
```bash
python src/main.py
```

## Como Usar

Ao rodar o programa, um menu será exibido no terminal com as opções:

1. **Cadastrar nova tarefa** — informe título, descrição, prioridade (Alta, Média ou Baixa) e data limite
2. **Visualizar tarefas cadastradas** — veja a lista de tarefas pendentes e concluídas
3. **Sair da aplicação**

## Autor

Luís Henrique Sampaio Lopes — Ciência de Dados e Machine Learning, Bootcamp II
