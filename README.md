# 🖥️ Prática de Fundamentos: Comandos de Terminal (CMD)

Este arquivo documenta os exercícios práticos realizados no Prompt de Comando (Windows). O objetivo da atividade foi adquirir fluência na navegação de diretórios, criação de pastas via linha de comando e validação do ambiente de desenvolvimento.

---

## 🛠️ Comandos Explorados

| Comando | Função |
| :--- | :--- |
| `cd [pasta]` | Entra em um diretório específico. |
| `cd ..` | Retorna um nível de diretório (volta para a pasta anterior). |
| `dir` | Lista todos os arquivos e pastas do diretório atual. |
| `mkdir [nome]` | Cria uma nova pasta (Make Directory). |
| `--version` / `-v` | Verifica a versão de um software instalado. |

---

## 📝 Detalhamento das Atividades

### Atividade 1: Exploração e Listagem
* Navegação até a pasta principal de usuário (`Documents`).
* Execução do comando `dir` para mapear e listar todos os diretórios de estudo e projetos existentes (como pastas da faculdade Una, Alura, etc.).

### Atividade 2: Estruturação de Pastas (Árvore de Diretórios)
Exercício de criação de diretórios aninhados (uma pasta dentro da outra) sem usar a interface gráfica:
1. Criação e acesso: `mkdir projetos` ➔ `cd projetos`
2. Criação e acesso: `mkdir exercicios` ➔ `cd exercicios`
3. Criação e acesso: `mkdir logica` ➔ `cd logica`
4. Retorno à raiz: Utilização do comando `cd ..` sequencialmente três vezes para voltar ao ponto de partida.

### Atividade 3: Verificação do Ambiente de Desenvolvimento
Validação das ferramentas essenciais de programação instaladas na máquina para garantir que o ambiente está pronto para compilar e executar códigos:
* **.NET SDK:** Execução de `dotnet --version`
* **Git:** Execução de `git --version`
* **Node.js:** Execução de `node -v`

---
**Desenvolvido por Lucas Nery Miranda | Estudante de Ciência da Computação - Una**
