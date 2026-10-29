# CriptoRadar Brasil

Portal estático em português sobre criptoativos, com editorias temáticas de notícias, mercado, Bitcoin, altcoins, regulação, tecnologia, segurança e educação. Inclui cotações indicativas em BRL, calculadora BTC/BRL, guias individuais e páginas institucionais. Projetado para hospedagem estática gratuita e manutenção pelo navegador do celular.

## Estrutura editorial

- `index.html`: página inicial com destaques editoriais e acesso às editorias.
- `noticias.html`: central de leitura e temas do portal.
- `mercado.html`: cotações indicativas de BTC, ETH, SOL, BNB e XRP pela API pública da CoinGecko, além de calculadora BTC/BRL.
- `bitcoin.html`, `altcoins.html`, `regulacao.html`, `tecnologia.html`, `seguranca.html` e `educacao.html`: páginas temáticas separadas.
- `artigos/`: guias educativos individuais.
- `sobre.html`, `contato.html`, `privacidade.html` e `termos.html`: páginas institucionais.
- `assets/site.css`: estilos compartilhados do portal.
- `robots.txt`, `sitemap.xml`, `favicon.svg`: arquivos de descoberta e identidade do site.

## Publicação pelo GitHub Pages

O repositório inclui um workflow em `.github/workflows/pages.yml` que tenta publicar o conteúdo da branch `main` no GitHub Pages a cada atualização.

- Site esperado: https://nandobrtv.github.io/crypto-radar-brasil/
- Workflow: https://github.com/NANDOBRTV/crypto-radar-brasil/actions/workflows/pages.yml
- Configurações do Pages: https://github.com/NANDOBRTV/crypto-radar-brasil/settings/pages

O arquivo de workflow foi adicionado, mas é necessário conferir a aba Actions e o status em Settings → Pages para confirmar a publicação. A presença do workflow, por si só, não comprova que o deploy foi concluído.

## API e limites

A página Mercado consulta a API pública CoinGecko diretamente do navegador. A API pode limitar solicitações, mudar os termos ou ficar indisponível. Não há chave privada no código. O navegador mantém um cache local de curta duração e aplica intervalo mínimo entre solicitações repetidas.

## Monetização: antes de ativar anúncios

O espaço publicitário atual é apenas um placeholder. Não há IDs nem código de anúncios de uma rede.

1. Cadastre o site na rede escolhida e aguarde aprovação.
2. Adicione somente o código oficial fornecido pela conta aprovada.
3. Atualize a política de privacidade e implemente o consentimento exigido para a região e a rede.
4. Confira as políticas da rede, conteúdo original, navegação, desempenho e propriedade do site.
5. Não clique nos próprios anúncios nem incentive cliques.

Nenhuma conta de anúncios, aprovação, receita ou pagamento é configurado automaticamente por este repositório.

## Nota editorial

Não publique manchetes atuais sem verificar data, fonte original e contexto. Diferencie notícia, análise e conteúdo educativo. Os textos existentes são introdutórios; as cotações são indicativas e podem divergir dos preços de negociação. O site não oferece aconselhamento financeiro individual nem promete rentabilidade.
