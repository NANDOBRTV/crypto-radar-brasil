# CriptoRadar Brasil

Blog estático em português sobre criptoativos, com cotações indicativas em BRL, calculadora BTC/BRL, artigos educativos, páginas institucionais e arquivos básicos de SEO. Projetado para hospedagem estática gratuita e administração pelo navegador do celular.

## Recursos

- Cotações indicativas de BTC, ETH, SOL, BNB e XRP pela API pública da CoinGecko.
- Calculadora de Bitcoin para reais com atualização no navegador.
- Mensagens de erro quando a API falha ou limita as consultas.
- Intervalo mínimo de 60 segundos entre solicitações manuais para reduzir chamadas repetidas.
- Três artigos individuais: funcionamento do Bitcoin, segurança e riscos.
- Páginas Sobre, Contato, Privacidade e Termos de Uso.
- Metadados SEO, canonical, Open Graph, favicon, robots.txt e sitemap.xml.
- Layout responsivo e sem dependências de build.

## Publicação pelo GitHub Pages

1. Abra [Settings → Pages](https://github.com/NANDOBRTV/criptoradar-brasil/settings/pages).
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/(root)`, e salve.
4. Aguarde a publicação.
5. Confirme o status e a URL exibida na página Pages. O endereço esperado é https://nandobrtv.github.io/criptoradar-brasil/.

O endereço acima é o esperado, não uma garantia de que o deploy esteja ativo. É necessário conferir o status no GitHub Pages.

## API e limites

A página consulta a API pública CoinGecko diretamente do navegador. A API pode limitar solicitações, mudar os termos ou ficar indisponível. Não há chave privada no código. Se houver erro, tente novamente depois; não automatize consultas frequentes.

## Monetização: antes de ativar anúncios

O espaço publicitário da página inicial é apenas um placeholder. Não há IDs nem código de anúncios de uma rede. Para monetizar:

1. Cadastre o site na rede escolhida e aguarde aprovação.
2. Adicione somente o código oficial fornecido pela conta aprovada.
3. Atualize a política de privacidade e implemente o mecanismo de consentimento exigido para a região e a rede.
4. Confira as políticas da rede, conteúdo original, navegação, desempenho e propriedade do site.
5. Não clique nos próprios anúncios nem incentive cliques.

Nenhuma conta de anúncios, aprovação, receita ou pagamento é configurado automaticamente por este repositório.

## Páginas

- `index.html`: início, cotações e calculadora.
- `artigos/`: conteúdo educativo individual.
- `sobre.html`, `contato.html`, `privacidade.html`, `termos.html`: páginas institucionais.
- `robots.txt`, `sitemap.xml`, `favicon.svg`: descoberta e identidade do site.

## Nota editorial

Conteúdo informativo, sem aconselhamento financeiro individual ou promessa de rentabilidade. Cotações são indicativas e podem divergir de preços de negociação. Revise periodicamente os artigos, links e informações legais.
