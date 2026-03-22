# 📘 Guia de Citações Coloridas no GitHub (NOTE, TIP, WARNING e IMPORTANT)

Este guia explica como utilizar os **blocos de destaque oficiais do GitHub Markdown**, chamados de **Alerts**.

Eles permitem criar citações coloridas dentro de arquivos `README.md`, Issues e Pull Requests, deixando a documentação mais organizada e profissional.

---

## 🧠 O que são GitHub Alerts?

Os **Alerts** são blocos especiais baseados em Markdown que destacam informações importantes visualmente, semelhantes às caixas informativas usadas em documentações técnicas modernas.

Sintaxe básica:

```md
> [!TIP]
> Seu texto aqui
```

---

## 🔵 NOTE — Informação adicional

Use quando quiser adicionar uma observação complementar ou explicação extra.

### Código:

```md
> [!NOTE]
> Esta funcionalidade funciona apenas no GitHub Markdown.
```

### Resultado:

> [!NOTE]
> Esta funcionalidade funciona apenas no GitHub Markdown.

---

## 🟢 TIP — Dica prática

Ideal para sugestões, boas práticas ou atalhos úteis.

### Código:

```md
> [!TIP]
> Utilize nomes de variáveis claros para melhorar a leitura do código.
```

### Resultado:

> [!TIP]
> Utilize nomes de variáveis claros para melhorar a leitura do código.

---

## ⚠️ WARNING — Aviso importante

Use quando algo pode causar erro, problema técnico ou comportamento inesperado.

### Código:

```md
> [!WARNING]
> Não execute este comando em ambiente de produção.
```

### Resultado:

> [!WARNING]
> Não execute este comando em ambiente de produção.

---

## ❗ IMPORTANT — Informação crítica

Para destacar algo essencial que o leitor precisa saber.

### Código:

```md
> [!IMPORTANT]
> Certifique-se de instalar todas as dependências antes de executar o projeto.
```

### Resultado:

> [!IMPORTANT]
> Certifique-se de instalar todas as dependências antes de executar o projeto.

---

## 📊 Quando usar cada um?

| Tipo | Quando usar |
|------|-------------|
| NOTE | Informação complementar |
| TIP | Dica ou recomendação |
| WARNING | Possível risco ou erro |
| IMPORTANT | Informação essencial |

---

## ✅ Regras importantes

- Funciona apenas no **GitHub** (não em todo Markdown).
- Deve começar com `>` (citação).
- O identificador deve estar em maiúsculo.
- O texto precisa ficar na linha abaixo.

Formato correto:

```md
> [!TIP]
> Texto aqui
```

---

## 🚫 Exemplo incorreto

```md
[!TIP] Texto aqui
```

Isso **não funcionará**, pois falta o símbolo `>`.

---

## 💡 Dica Extra

Você pode usar emojis dentro dos alerts:

```md
> [!TIP]
> 🚀 Automatize tarefas repetitivas sempre que possível.
```

---

## 📚 Compatibilidade

✔ README.md  
✔ Issues  
✔ Pull Requests  
✔ Wikis GitHub  

---

## 👨‍💻 Autor
@DevBrendown

Guia criado para ajudar desenvolvedores a melhorar documentações usando Markdown moderno do GitHub.
