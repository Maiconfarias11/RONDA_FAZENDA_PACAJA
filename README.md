# Visualizador KMZ/KML — Deploy Rápido

Este pacote contém o site pronto para deploy (single-page). O arquivo principal é **index.html**.

## Como publicar

### Opção A — GitHub Pages
1. Crie um repositório novo no GitHub (público).
2. Envie os arquivos desta pasta para o repositório: `index.html` e `404.html`.
3. No repositório, acesse **Settings → Pages** e em **Build and deployment** selecione **Deploy from a branch**.
4. Escolha a branch (ex.: `main`) e a pasta `/root`. Salve.
5. A URL ficará assim: `https://SEU_USUARIO.github.io/NOME_DO_REPO/`.

### Opção B — Netlify (arrastar e soltar)
1. Acesse https://app.netlify.com e faça login.
2. Clique em **Add new site → Deploy manually**.
3. Arraste a pasta inteira (ou o `.zip`) para a área de deploy.
4. A URL será gerada automaticamente.

### Opção C — Vercel (importar repositório)
1. Suba os arquivos para um repositório no GitHub/GitLab/Bitbucket.
2. Em https://vercel.com, **New Project → Import** e selecione o repositório.
3. As configurações padrão funcionam (projeto estático).

## Uso
- Abra o site e **selecione um arquivo `.kmz` ou `.kml`**; também é possível **arrastar e soltar** na tela inicial.
- O mapa e os controles (Mês, Trajetos, Exportar PDF) já estão inclusos no HTML original fornecido.

> Observação: Todos os recursos são servidos via CDN (Leaflet, JSZip, jsPDF, html2canvas). Não é necessário backend.