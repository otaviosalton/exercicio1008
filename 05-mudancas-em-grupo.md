# 05. Mudanças em grupo

> Nomeie uma série de commits e combine os esforços completos.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)

---

## Comandos desta seção (5)

### 1. `git branch`

```bash
git branch
```

**O que faz:**

<!-- Lista todas as branches locais existentes no repositório e indica qual está ativa. -->

**Quando usar / observação:**

<!-- Use para verificar em qual branch você está trabalhando no momento antes de criar ou alterar código. -->

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**

<!-- Cria uma nova branch local com o nome especificado a partir do commit atual. -->

**Quando usar / observação:**

<!-- Use quando for iniciar o desenvolvimento de uma nova funcionalidade sem alterar a branch principal. -->

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

<!-- Cria uma nova branch e alterna para ela imediatamente em um único comando. -->

**Quando usar / observação:**

<!--Use para economizar tempo ao criar uma linha de trabalho e já mudar direto para ela. -->

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

<!-- Combina o histórico de alterações da branch especificada para dentro da branch em que você está atualmente. -->

**Quando usar / observação:**

<!-- Use para integrar o trabalho concluído de uma funcionalidade de volta à branch principal do projeto. -->

---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**

<!-- Deleta a branch local especificada após garantir que suas alterações já foram mescladas. -->

**Quando usar / observação:**

<!-- Use para manter o repositório limpo excluindo branches antigas de tarefas que já foram finalizadas. -->

---

## Checklist deste arquivo

- [x] 1. `git branch`
- [x] 2. `git branch [nome-do-branch]`
- [x] 3. `git switch -c [nome-do-branch]`
- [x] 4. `git merge [nome-do-branch]`
- [x] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
