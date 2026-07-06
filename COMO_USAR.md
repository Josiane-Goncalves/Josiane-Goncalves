# Como usar este perfil no GitHub

## 1. Substituir o README

Copie o arquivo `README.md` desta pasta e substitua o `README.md` do repositório:

```txt
Josiane-Goncalves/Josiane-Goncalves
```

Depois rode:

```bash
git add README.md
git commit -m "style: update profile README layout"
git push origin main
```

## 2. Manter ou trocar a animação do Sheldon

No `README.md`, procure esta parte:

```html
<img height="210" src="https://64.media.tumblr.com/2e1b0647ee522b261dc3c87ff194472e/378df6548b6b776e-65/s400x600/7c7441a69cd1f660ea702e2930c1cd624c46c899.gifv" alt="Animação geek" />
```

Troque apenas o conteúdo de `src="..."` pelo link do GIF do Sheldon Cooper que você já usa.

Exemplo:

```html
<img height="210" src="LINK_DO_SEU_GIF_DO_SHELDON_AQUI" alt="Animação geek" />
```

## 3. Conferir a cobrinha

A cobrinha depende do arquivo:

```txt
.github/workflows/snake.yml
```

Depois de subir o arquivo, vá no GitHub em:

```txt
Actions > Generate GitHub contribution snake > Run workflow
```

Se der erro de permissão, vá em:

```txt
Settings > Actions > General > Workflow permissions
```

E marque:

```txt
Read and write permissions
```

## 4. O que ajustar depois

- Link dos projetos publicados na Vercel.
- Link correto do GIF do Sheldon Cooper.
- Ordem dos projetos em destaque.
- Repositórios fixados no perfil.
