# Como publicar o site (GitHub Pages, grátis)

1. Crie uma conta em https://github.com (o nome de usuário vira o endereço do site).
2. Crie um repositório PÚBLICO chamado exatamente `SEU-USUARIO.github.io` (ex.: `kapasistudios.github.io`).
   Esse nome deixa o site na raiz do domínio — o AdMob exige o `app-ads.txt` na raiz.
3. No repositório: *Add file → Upload files* e arraste TODO o conteúdo desta pasta
   (index.html, privacidade.html, termos.html, exclusao-de-dados.html, 404.html, estilo.css, app-ads.txt, .nojekyll).
   Este PUBLICAR.md pode ficar de fora. Clique em *Commit changes*.
4. *Settings → Pages*: Source = *Deploy from a branch*, Branch `main`, pasta `/ (root)` → Save.
5. Em 1–2 minutos o site abre em `https://SEU-USUARIO.github.io`.

Endereços para a Play Console:
- Política de privacidade: https://SEU-USUARIO.github.io/privacidade.html
- Exclusão de dados:      https://SEU-USUARIO.github.io/exclusao-de-dados.html
- Site do app:            https://SEU-USUARIO.github.io

IMPORTANTE: no `app-ads.txt`, troque `pub-0000000000000000` pelo seu ID de editor do AdMob
(AdMob → Configurações → Informações da conta), e só então envie o arquivo.
