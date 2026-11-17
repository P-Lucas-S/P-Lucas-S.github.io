# Portfólio · Pedro Lucas de Souza Ribeiro

Site estático publicado no GitHub Pages: https://p-lucas-s.github.io

- `index.html`: a página (HTML, CSS e JS num arquivo só, sem build). O chat do topo conversa ao vivo com o agente em agente-mercadinho.onrender.com, que libera este domínio por CORS.
- `img/`: capturas das demos.
- `curriculo.pdf`: currículo em PDF (versão pública, sem telefone).
- `.github/workflows/manter-demos-acordadas.yml`: chama as demos do Render a cada 10 min, de segunda a sexta, das 8h às 20h (Brasília), para que não estejam dormindo quando alguém abrir. Ao abrir, a própria página também acorda todas as demos em segundo plano.

O GitHub desativa rotinas agendadas em repositórios sem commits por 60 dias; se isso acontecer, reative em **Actions → Manter demos acordadas → Enable workflow**.
