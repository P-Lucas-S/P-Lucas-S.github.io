# Portfólio · Pedro Lucas de Souza Ribeiro

Site estático publicado no GitHub Pages: https://p-lucas-s.github.io

- `index.html`: a página (HTML e CSS num arquivo só, sem build).
- `img/`: capturas das demos.
- `curriculo.pdf`: currículo em PDF.
- `.github/workflows/manter-demos-acordadas.yml`: chama as demos do Render a cada 10 min, de segunda a sexta, das 8h às 20h (Brasília), para que não estejam dormindo quando alguém abrir. Ao abrir, a própria página também acorda todas as demos em segundo plano.

O GitHub desativa rotinas agendadas em repositórios sem commits por 60 dias; se isso acontecer, reative em **Actions → Manter demos acordadas → Enable workflow**.
