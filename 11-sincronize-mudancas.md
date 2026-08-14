# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

<!--Baixa todo o histórico e branches do repositório remoto sem alterar os seus arquivos locais. -->

**Quando usar / observação:**

<!-- Use para conferir as novidades no GitHub antes de decidir juntar as alterações com o seu trabalho. -->

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

<!-- Junta as alterações que foram baixadas do repositório remoto para dentro da sua branch local atual. -->

**Quando usar / observação:**

<!-- Use logo após o git fetch para aplicar as novidades da nuvem no seu projeto local. -->

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

<!-- Envia os commits da sua branch local diretamente para a branch especificada no repositório remoto. -->

**Quando usar / observação:**

<!-- Use sempre que terminar um bloco de tarefas para salvar e compartilhar o seu código no GitHub.-->

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

<!--Baixa o conteúdo do repositório remoto e atualiza imediatamente a sua branch local atual. -->

**Quando usar / observação:**

<!--Use no início do dia para sincronizar seu computador com o código mais recente enviado pela equipe. -->

---

## Checklist deste arquivo

- [X] 1. `git fetch [nome-remoto]`
- [X] 2. `git merge [nome-remoto]/[branch]`
- [X] 3. `git push [alias] [branch]`
- [X] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
