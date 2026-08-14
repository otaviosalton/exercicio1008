# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

<!-- Desfaz os commits posteriores ao commit especificado mantendo as alterações dos arquivos no seu diretório de trabalho. -->

**Quando usar / observação:**

<!-- Use quando quiser reorganizar ou juntar vários commits locais sem perder o código que já escreveu.-->

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

<!-- Descarta completamente todos os commits e alterações nos arquivos feitas após o commit especificado.-->

**Quando usar / observação:**

<!-- Use com muito cuidado apenas quando quiser jogar fora todo o trabalho feito e voltar o código exatamente para um estado antigo.-->

---

## Checklist deste arquivo

- [x] 1. `git reset [commit]`
- [x] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
