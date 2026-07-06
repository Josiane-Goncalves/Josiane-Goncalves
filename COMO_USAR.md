# Como usar este perfil no GitHub

## 1. Crie o repositório de perfil

No GitHub, crie um novo repositório público com exatamente este nome:

```txt
Josiane-Goncalves
```

O nome precisa ser igual ao seu usuário do GitHub para o README aparecer no seu perfil.

## 2. Adicione os arquivos

Envie estes arquivos para a raiz do repositório:

```txt
README.md
.github/workflows/snake.yml
```

A estrutura deve ficar assim:

```txt
Josiane-Goncalves/
├── README.md
└── .github/
    └── workflows/
        └── snake.yml
```

## 3. Faça commit e push

```bash
git add .
git commit -m "feat: add profile README with contribution snake"
git push origin main
```

## 4. Ative a animação da cobrinha

Depois do push:

1. Abra o repositório no GitHub.
2. Vá na aba `Actions`.
3. Clique no workflow `Generate GitHub contribution snake`.
4. Clique em `Run workflow`.
5. Aguarde a execução finalizar.

O workflow criará uma branch chamada `output` com os arquivos SVG da animação.

## 5. Se a cobrinha não aparecer

Verifique:

- O repositório é público?
- O nome do repositório é exatamente `Josiane-Goncalves`?
- O arquivo `README.md` está na raiz?
- O GitHub Actions está habilitado?
- A branch `output` foi criada após rodar o workflow?

