# CriptoRadar Brasil

Site estático em português com cotações indicativas de BTC, ETH, SOL, BNB e XRP em reais, conversor BTC/BRL e conteúdo educativo. Feito para hospedagem estática gratuita.

## Publicar no Cloudflare Pages
1. Acesse o painel Cloudflare e abra **Workers & Pages**.
2. Selecione **Create application** e depois **Pages**.
3. Conecte sua conta GitHub e escolha `NANDOBRTV/criptoradar-brasil`.
4. Para um site estático sem build: framework preset **None**, build command vazio e build output directory `/` (ou deixe conforme a orientação atual do painel para projeto sem build).
5. Inicie o deploy e aguarde o status de sucesso. O domínio `*.pages.dev` só existe depois da criação do projeto.

## Dados de mercado
A página consulta a API pública CoinGecko diretamente do navegador. Não requer chave nesta versão, mas está sujeita a limites, disponibilidade e termos do fornecedor. Há intervalo mínimo de 60 segundos entre consultas manuais.

## Antes de monetizar
- O espaço de publicidade ainda não contém anúncios reais.
- Solicite aprovação na rede de anúncios e só depois insira o código oficial fornecido pela sua conta.
- Atualize política de privacidade e contato com dados reais antes de submeter para análise.
- O e-mail exibido na página é ilustrativo e deve ser substituído por um endereço válido antes de divulgar o site.
- Cotações são indicativas; não constituem recomendação financeira.

## Arquitetura
A versão inicial está concentrada em `index.html`, incluindo CSS e JavaScript para facilitar a publicação inicial. Nenhuma chave privada ou segredo é necessário.
