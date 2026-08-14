# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

<!-- Guarda temporariamente todas as alterações não salvas do seu diretório de trabalho limpando a branch. -->

**Quando usar / observação:**

<!-- Use quando precisar trocar de branch rapidamente para resolver algo urgente sem precisar fazer um commit incompleto. -->

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

<!-- Restaura as últimas alterações guardadas no stash e as remove da lista do stash ao mesmo tempo. -->

**Quando usar / observação:**

<!-- Use para recuperar e continuar o trabalho temporariamente guardado assim que retornar para a sua branch. -->

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

<!-- Exibe uma lista com todos os conjuntos de alterações temporárias que você guardou no stash. -->

**Quando usar / observação:**

<!-- Use para conferir os identificadores dos seus rascunhos salvos quando tiver mais de um stash criado. -->

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

<!-- Descarta definitivamente o conjunto de alterações temporárias mais recente ou o stash especificado. -->

**Quando usar / observação:**

<!-- Use para apagar rascunhos salvos do stash que você não vai mais utilizar para não acumular sujeira. -->

---

## Checklist deste arquivo

- [X] 1. `git stash`
- [X] 2. `git stash pop`
- [X] 3. `git stash list`
- [X] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
