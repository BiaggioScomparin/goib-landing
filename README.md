# GOIB — Landing Page · Lealdade e Justiça Nº 001

Landing page de captação de candidatos para a Loja Lealdade e Justiça Nº 001 do GOIB.

## ⚠️ Antes de publicar

Abra o arquivo `index.html` e localize esta linha:

```html
<a href="https://wa.me/55SEUNUMEROQUI?text=...
```

Substitua `55SEUNUMEROQUI` pelo número do WhatsApp com DDI + DDD, sem espaços ou traços.

**Exemplo:** se o número for `(11) 99999-1234`, use `5511999991234`

```html
<a href="https://wa.me/5511999991234?text=...
```

---

## 🚀 Como publicar na Vercel

### Opção 1 — Via interface web (sem instalar nada)

1. Acesse [vercel.com](https://vercel.com) e crie uma conta gratuita
2. Clique em **"Add New Project"**
3. Arraste a pasta `goib-landing` ou conecte ao GitHub
4. Clique em **Deploy** — pronto!

### Opção 2 — Via terminal (Vercel CLI)

```bash
npm install -g vercel
vercel login
vercel
```

---

## 📁 Estrutura do projeto

```
goib-landing/
├── index.html        ← Página principal
├── vercel.json       ← Config de deploy
├── README.md         ← Este arquivo
└── assets/
    └── logo.png      ← Logo do GOIB
```
