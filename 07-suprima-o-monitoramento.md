# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

<!-- Define regras para o Git ignorar automaticamente arquivos temporários, pastas de build e padrões especificados. -->

**Quando usar / observação:**

<!-- Use para evitar o envio de senhas, logs de execução ou arquivos pesados de compilação para o repositório. -->

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

<!-- Lista no terminal todos os arquivos do projeto que estão sendo ignorados pelas regras do arquivo .gitignore. -->

**Quando usar / observação:**

<!-- Use para conferir se uma regra de ignore funcionou corretamente e qual arquivo está sendo ignorado pelo Git. -->

---

## Checklist deste arquivo

- [x] 1. Arquivo `.gitignore`
- [x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
