# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

<!-- Exibe o histórico completo de commits realizados na branch atual em ordem cronológica inversa.-->

**Quando usar / observação:**

<!-- Use para consultar quais alterações foram feitas no projeto, por quem e quando foram salvas. -->

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

<!-- Exibe o histórico de commits de forma resumida, mostrando apenas o código hash e a primeira linha da mensagem. -->

**Quando usar / observação:**

<!-- Use quando quiser visualizar rapidamente vários commits na tela sem ocupar muito espaço do terminal. -->

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

<!-- Mostra as alterações detalhadas de código linha por linha introduzidas em cada commit para o arquivo especificado.-->

**Quando usar / observação:**

<!--Use para rastrear exatamente o que mudou no código interno de um arquivo ao longo de seus commits antigos.-->

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

<!-- Exibe o histórico acompanhado das estatísticas de arquivos alterados, linhas adicionadas e removidas por commit.-->

**Quando usar / observação:**

<!-- Use para entender o tamanho do impacto de cada commit sem precisar ver todo o código linha por linha. -->

---

## Checklist deste arquivo

- [X] 1. `git log`
- [X] 2. `git log --follow [arquivo]`
- [X] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [X] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
