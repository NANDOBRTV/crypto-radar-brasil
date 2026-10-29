# CriptoRadar Brasil

Site estático em português com cotações indicativas de BTC, ETH, SOL, BNB e XRP em reais, conversor BTC/BRL e conteúdo educativo. Feito para hospedagem estática gratuita.

## Publicar pelo GitHub Pages
1. Abra **Settings** deste repositório.
2. Entre em **Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)), depois clique em **Save**.
5. Aguarde a publicação. O endereço esperado será `https://nandobrtv.github.io/criptoradar-brasil/`; confirme o endereço e o status na própria página Pages.

## Cloudflare Pages
A tentativa de criar o projeto pelo acesso Cloudflare conectado retornou erro HTTP 401 `8000011`, relacionado à instalação Git do Cloudflare Pages. Nenhum projeto nem deploy Cloudflare foi confirmado. Para tentar novamente, abra Cloudflare > Workers & Pages e reconecte/reinstale a integração GitHub, ou publique pelo GitHub Pages usando os passos acima.

## Dados de mercado
A página consulta a API pública CoinGecko diretamente do navegador. Não requer chave nesta versão, mas está sujeita a limites, disponibilidade e termos do fornecedor. Há intervalo mínimo de 60 segundos entre consultas manuais. Se a API estiver indisponível, a página informa que não conseguiu carregar os preços.

## Antes de monetizar
- O espaço de publicidade ainda não contém anúncios reais.
- Solicite aprovação na rede de anúncios e só depois insira o código oficial fornecido pela sua conta.
- Atualize a política de privacidade e adicione um canal de contato real antes de submeter o site para análise.
- Cotações são indicativas; não constituem recomendação financeira.

## Arquitetura
A versão inicial está concentrada em `index.html`, incluindo CSS e JavaScript para facilitar a publicação inicial. Nenhuma chave privada ou segredo é necessário.
