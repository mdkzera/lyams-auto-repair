# Lyam’s Auto Repair & Services

Site de uma página (HTML + CSS + JS mínimo, sem build) para a oficina **Lyam’s Auto Repair & Services**, em Miami, FL.

## Dados do cliente

- Endereço: 2695 W Flagler St, Miami, FL
- Telefone: +1 305-760-5465
- O site está em inglês (mercado: Miami, FL)

## Estrutura

```
index.html   página completa (CSS e JS inline)
robots.txt   permite indexação
```

## Visualizar localmente

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

## Pendências antes de publicar

Os pontos abaixo estão marcados com comentários `EDIT` em `index.html`.

- Definir o domínio e adicionar `rel="canonical"`, `og:url` e `og:image`
- Adicionar horário de funcionamento (e `openingHours` no JSON-LD)
- Adicionar o CEP no endereço do JSON-LD (não informado até agora)
- Substituir a ilustração do hero por foto real da oficina
- Confirmar a lista de serviços com o proprietário
- Criar `sitemap.xml` com o domínio final

## Deploy

É um site estático: funciona em GitHub Pages, Netlify, Vercel ou qualquer hospedagem estática. As fontes (Bricolage Grotesque e Instrument Sans) vêm do Google Fonts; em produção, vale hospedá-las junto com o site.

## Qualidade (medido localmente)

Lighthouse mobile: Performance 99, Accessibility 100, Best Practices 100, SEO 100 (com as fontes servidas localmente; o resultado em produção pode variar).
