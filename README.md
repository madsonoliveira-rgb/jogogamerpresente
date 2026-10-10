# Destino Final

Jogo de corrida para PC, com senha, checkpoints, cofre e mensagem final.
É uma página só (`index.html`). As fotos já estão dentro do arquivo.

- Senha: `0000`
- Controles: setas ou WASD, Espaço usa o nitro, Esc pausa, F tela cheia, M som

## Hospedar no GitHub Pages

1. Crie um repositório novo no GitHub.
2. Envie o `index.html` e este `README.md` para a raiz do repositório
   (botão **Add file > Upload files**, depois **Commit changes**).
3. Vá em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**,
   branch `main`, pasta `/ (root)`, e clique em **Save**.
5. Espere 1 a 2 minutos. O link aparece no topo da mesma página,
   no formato `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Pelo terminal

```bash
git init
git add index.html README.md
git commit -m "Destino Final"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
git push -u origin main
```

Depois siga os passos 3 a 5 acima.

## Privacidade

No plano gratuito, o GitHub Pages exige repositório público. Qualquer pessoa
que tiver o link consegue abrir a página e ver as fotos. A senha `0000` só
bloqueia a tela, não protege o conteúdo. Use um nome de repositório que não
chame atenção e mande o link só pra ele.

Se preferir manter privado, o Cloudflare Pages e o Netlify aceitam
repositório privado ou o envio direto da pasta, sem tornar nada público.

## Trocar textos

As falas do rádio, as legendas das fotos e a carta final ficam no começo do
script, dentro do `index.html`, no bloco `CFG`. O local do presente fica
codificado logo acima. Se quiser mudar algo, me peça e eu gero uma nova versão.
