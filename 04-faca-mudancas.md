# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

<!-- Exibe o estado atual da área de trabalho e quais arquivos foram modificados ou adicionados. -->

**Quando usar / observação:**

<!-- Use frequentemente para verificar quais arquivos estão pendentes de commit antes de enviar suas alterações. -->

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

<!-- Mostra as diferenças exatas de linhas alteradas nos arquivos antes de serem adicionados à fila de commit. -->

**Quando usar / observação:**

<!-- Use para revisar linha por linha o que você alterou no código antes de executar o comando git add. -->

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

<!-- Adiciona as alterações de um arquivo específico para a área de preparação chamada staging. -->

**Quando usar / observação:**

<!-- Use quando quiser selecionar individualmente apenas um arquivo alterado para incluir no próximo commit. -->

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

<!-- Mostra as diferenças entre os arquivos que já estão no staging e a última versão salva no repositório. -->

**Quando usar / observação:**

<!-- Use para conferir as alterações que foram preparadas com o git add antes de confirmar o commit definitivo. -->

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

<!-- Remove o arquivo da área de preparação mantendo as alterações feitas no seu código local intactas. -->

**Quando usar / observação:**

<!-- Use quando adicionar um arquivo por engano no staging com o git add e quiser removê-lo da fila. -->

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

<!-- Grava as alterações preparadas no histórico do repositório acompanhadas de uma mensagem explicativa. -->

**Quando usar / observação:**

<!-- Use para salvar oficialmente um conjunto de mudanças concluídas e manter um histórico organizado do projeto.. -->

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
