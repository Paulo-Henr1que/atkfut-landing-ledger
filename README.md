# ATKFUT — Landing page (versão Ledger)

Visual escuro, estilo app/painel, com **simulador interativo**: o visitante informa preço pago, preço de venda, outros custos e peças vendidas, e vê a conta com os números dele.

- Ao vivo: https://paulo-henr1que.github.io/atkfut-landing-ledger/
- Outra variação (clara/editorial): https://github.com/Paulo-Henr1que/atkfut-landing-catalogo

Site estático (`index.html` + `style.css`), sem build.

## Base de conteúdo

Tudo que a página afirma sobre o app vem do site original ([atkfornecedor.com](https://atkfornecedor.com/)): pedido mínimo de 5 peças, escolha de times e modelos, catálogo, preço de fornecedor, ofertas e notificações no app, pagamento pelo app, links oficiais da App Store e do Google Play e as 4 avaliações de clientes publicadas lá. Nenhum recurso, número ou depoimento foi inventado.

## Decisões de conformidade (Google Ads / TikTok Ads)

| Original | Nesta versão | Por quê |
|---|---|---|
| "Fornecedor Oficial" | "Fornecedor atacadista" | "Oficial" junto a marcas de terceiros agrava a política de bens falsificados / PI |
| "Lucre R$80 a R$130 por camisa", "+R$12.000/mês" | Simulador com os números do próprio visitante + FAQ "não dá para prometer um valor" | Alegação de renda não substanciada (Misrepresentation / Business Opportunity) |
| Painel com "Lucro do mês R$ 9.240" | Mock do app com catálogo, oferta e carrinho de 5 peças, sem valores | Mesmo motivo acima |
| "Multiplique o lucro", "mercado sempre quente" | "Repita o pedido quando fizer sentido" | Promessa implícita de resultado |
| — | Seção "É pra você?" com quem **não** deve entrar | Revisores de oportunidade de negócio valorizam expectativas realistas |
| — | Ilustrações de camisa genéricas, sem escudo nem marca | Evitar uso de marca de terceiros na página |

## Risco que continua fora do alcance da página

**Bens falsificados / propriedade intelectual.** Se o catálogo vende réplicas com escudos de clubes e logos de fabricantes sem licença, Google Ads e TikTok Ads podem reprovar ou suspender a conta independentemente do texto da landing page. Não use fotos de produto com marcas de terceiros nos criativos de anúncio. A solução definitiva é produto licenciado.

## Pendências

1. Inserir o CNPJ no rodapé (há um `<!-- TODO -->` no `index.html`).
2. Se for anunciar como oportunidade de negócio no TikTok Ads, verificar se a categoria exige aprovação prévia.
3. Se adicionar formulário ou pixel de rastreamento, incluir página de política de privacidade.
