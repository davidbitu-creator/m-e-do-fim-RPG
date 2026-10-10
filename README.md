# A Mãe do Fim

Ficha de boss com 366 PV, três fases, relógio de nascimento, rolagens, recursos e anotações.

## Publicar pelo navegador no GitHub Pages

1. Extraia o ZIP no computador. Não envie o ZIP ao repositório.
2. No GitHub, crie um repositório chamado `mae-do-fim`. Para o caminho gratuito mais simples, escolha **Public**. A ficha e a imagem ficarão acessíveis publicamente.
3. Na página do repositório, clique em **uploading an existing file** ou **Add file > Upload files**.
4. Envie `index.html` e `README.md` diretamente na raiz do repositório. O `index.html` não deve ficar dentro de uma pasta `github` ou `output`.
5. Clique em **Commit changes**.
6. Abra **Settings > Pages**.
7. Em **Build and deployment > Source**, selecione **Deploy from a branch**.
8. Em **Branch**, selecione `main` e `/(root)`. Clique em **Save**.
9. Aguarde a publicação, que pode levar até 10 minutos. A página **Settings > Pages** mostrará o endereço para acessar o site.

O endereço terá o formato `https://SEU-USUARIO.github.io/mae-do-fim/`.

## Arquivos

- `index.html`: site completo. CSS, JavaScript e imagem estão incorporados; não precisa de instalação, servidor próprio ou build.
- `README.md`: estas instruções. É opcional para o funcionamento do site.

## Usar e atualizar

Abra o link no navegador e controle o combate. O estado fica salvo somente naquele navegador e dispositivo; não é sincronizado pelo GitHub. Para trocar de dispositivo, use **Exportar estado** e depois **Importar**.

Para atualizar a ficha, substitua `index.html` no repositório e faça um novo commit. O Pages republica automaticamente a partir da branch selecionada.

Se aparecer 404, confirme que `index.html` está na raiz, a branch selecionada é `main`, a pasta é `/(root)` e a publicação terminou. Consulte a aba **Actions** para ver o resultado.

Documentação: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
