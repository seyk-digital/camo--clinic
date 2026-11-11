# CAMO CLINIC — projeto para GitHub e Vercel

Site estático em HTML, CSS e JavaScript, sem etapa de build. Para testar localmente, abra `index.html` ou sirva esta pasta com qualquer servidor estático.

## Publicação na Vercel

Importe a pasta/repositório no Vercel e configure o Framework Preset como **Other**, Build Command vazio e Output Directory como `.` (raiz do projeto). `vercel.json` define a configuração de site estático. O arquivo inicial é `index.html`.

## Estrutura

- `index.html` — página inicial.
- `styles.css` — estilos responsivos.
- `script.js` — menu mobile e ano do rodapé.
- `assets/` — imagens utilizadas pelo site.
- `vercel.json` — configuração de hospedagem estática.

As imagens são carregadas por caminhos relativos explícitos (`./assets/...`). Mantenha a pasta `assets` no mesmo nível do `index.html` ao enviar o projeto ao GitHub. O site também inclui uma abertura de marca com o logotipo, revelação ao rolar, indicador de progresso da página e respeito à preferência do navegador por movimento reduzido.

A galeria de antes e depois tem navegação responsiva por estrias, cicatrizes e manchas. Os pares de imagem são espaços reservados: inclua somente fotos reais com autorização e aprovação da clínica.

## Observação de conteúdo

A página preserva o conteúdo provisório do projeto original. Complete e valide informações clínicas, biografia e contato antes da publicação pública.
