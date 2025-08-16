# **Larjam — Livro de Apoio Religioso do JAM (Jedaísmo Agnóstico Moderado)**

O Larjam é um conjunto de arquivos em formato markdown publicado em um repositório público no Github e utiliza o recurso Github Pages para sua divulgação.


Este projeto é um organismo filosófico vivo, aberto, colaborativo e em constante construção.

---

## 🌐 Site público

O Larjam está disponível em:  
👉 [https://eom-jam.github.io/larjam/](https://eom-jam.github.io/larjam/)

---

## 📖 Documentação

- [🤝 Guia de Colaboração](docs/colaboracao.md)
- [⚖️ Licença](docs/licenca.md)

---

## 🚀 Como rodar localmente

### 🔧 Pré-requisitos

- Python instalado
- MkDocs com tema Material:
```bash
pip install mkdocs-material
```

### ▶️ Rodar localmente

```bash
mkdocs serve
```
Acesse:
```
http://127.0.0.1:8000
```

### 📦 Gerar o site estático

```bash
mkdocs build
```

### 🚀 Publicar no GitHub Pages

```bash
mkdocs gh-deploy
```

---

## Estrutura do Projeto

```
larjam/
├── docs/                       # Arquivos Markdown do conteúdo
│   ├── index.md
│   ├── larjam.md
│   ├── fundamentos
│   │   ├── referencias_filosoficas.md
│   │   ├── crencas
│   │   │   ├── eom.md
│   │   │   ├── nomus.md
│   │   │   └── glossario.md
│   │   └── epistemologia
│   │       ├── emaranhamento.md
│   │       ├── eom.md
│   │       ├── nomus.md
│   │       └── glossario.md
│   ├── colaboracao.md          # Guia de Colaboração
│   ├── manifesto.md            # Como contribuir
│   └── licenca.md
├── mkdocs.yml                  # Configuração do site
└── README.md                   # Este arquivo
```

---

## ✨ Filosofia Viva

O Larjam não é um documento fechado.  
É um organismo filosófico em constante construção, evolução, alinhamento e emaranhamento.

A sua contribuição é um ato de externalização e alinhamento nomial, que fortalece o universo coletivo do JAM.

Agradecemos profundamente sua participação.

— JAM


# Publicação do JAM no Github
Para que o site MkDocs apareça corretamente no GitHub Pages, é necessário **publicar os arquivos estáticos gerados** (normalmente na pasta site) no branch correto do seu repositório.

### Passos para publicar MkDocs no GitHub Pages:

1. **Gere o site estático:**
   No terminal, execute:
   ```
   mkdocs build
   ```
   Isso cria a pasta site com os arquivos prontos para publicação.

2. **Publique no GitHub Pages:**
   O MkDocs facilita isso com:
   ```
   mkdocs gh-deploy
   ```
   Esse comando cria (ou atualiza) o branch `gh-pages` com o conteúdo da pasta site e configura o GitHub Pages automaticamente.

3. **Verifique as configurações do GitHub Pages:**
   - No repositório, vá em **Settings > Pages**.
   - Confirme que a fonte está definida para o branch `gh-pages` e a pasta `/ (root)`.

4. **Aguarde alguns minutos** e acesse a URL do seu GitHub Pages.

