# Landing Page Barbearia

Site estático pronto para publicar no Cloudflare Pages.

## O que já está no projeto

- `index.html` como página principal
- `styles.css` com a identidade visual
- `script.js` com animação leve
- `assets/logo.svg` com o logo da barbearia
- imagens da galeria na pasta `assets/`

## Como publicar no Cloudflare Pages

### Opção 1: conexão com GitHub

1. Crie um repositório no GitHub e envie esses arquivos para ele.
2. Entre no painel do Cloudflare.
3. Abra `Pages`.
4. Clique em `Create a project`.
5. Escolha `Connect to Git`.
6. Conecte sua conta GitHub e selecione o repositório.
7. Em `Build settings`, deixe assim:
   - `Framework preset`: `None`
   - `Build command`: vazio
   - `Build output directory`: a pasta do projeto onde está o `index.html`
8. Clique em `Save and Deploy`.
9. Aguarde o link público ser gerado.

### Opção 2: upload direto

1. Abra o Cloudflare Dashboard.
2. Vá em `Pages`.
3. Clique em `Create a project`.
4. Escolha `Upload assets`.
5. Envie a pasta do projeto compactada em `.zip` ou os arquivos da pasta do site.
6. Finalize a publicação.

## Depois de publicar

1. Abra o link gerado pelo Cloudflare.
2. Teste o botão do Instagram.
3. Teste o botão do WhatsApp.
4. Se quiser um domínio próprio depois, conecte em `Custom domains`.

## Observação

As fotos da galeria estão sendo carregadas de URLs externas. Se você quiser, eu posso deixar tudo 100% local no projeto em uma próxima etapa.
