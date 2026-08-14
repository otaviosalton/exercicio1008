# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

<!-- Remove o arquivo especificado do diretório de trabalho e agenda sua exclusão no próximo commit. -->

**Quando usar / observação:**

<!-- Use quando quiser apagar definitivamente um arquivo que não é mais necessário no projeto. -->

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

<!-- Remove o arquivo do controle de versão do Git mas mantém o arquivo físico salvo na sua máquina local. -->

**Quando usar / observação:**

<!-- Use quando adicionar por engano um arquivo no Git que deveria ser ignorado mas você deseja manter no computador. -->

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

<!-- Renomeia ou move um arquivo alterando seu caminho e preparando a mudança automaticamente para o próximo commit. -->

**Quando usar / observação:**

<!-- Use para organizar a estrutura de pastas ou renomear arquivos mantendo o histórico de alterações rastreado pelo Git. -->

---

## Checklist deste arquivo

- [X] 1. `git rm [arquivo]`
- [X] 2. `git rm --cached [arquivo]`
- [X] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
