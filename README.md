# ConsertaJunto · página de entrada

Página pública do projeto, publicada no GitHub Pages em **https://georginho1.github.io/consertajunto**.

| Endereço | Destino |
|---|---|
| `/` | Página de apresentação com links e QR codes |
| `/app/` | Redireciona para o app do cidadão (PWA, CloudFront) |
| `/painel/` | Redireciona para o painel do gestor (CloudFront) |

Os QR codes apontam para os endereços do GitHub Pages, não para o CloudFront. Se a infra da AWS for recriada e as URLs do CloudFront mudarem, basta atualizar `app/index.html` e `painel/index.html`; os QR codes já impressos continuam funcionando.

O código do projeto fica em repositórios privados; aqui só há HTML estático.
