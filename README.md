# ATKFUT — Landing page (versão Ledger)

Visual escuro com a paleta do site original (verde neon `#22e06a` sobre verde-escuro `#04100a`), mock realista do app no topo e **simulador interativo**: o visitante informa preço pago, preço de venda, outros custos e peças vendidas, e vê a conta com os números dele.

As camisas mostradas são ilustrações SVG genéricas (sem escudo ou marca), para não usar propriedade intelectual de terceiros na página.

- Ao vivo: https://paulo-henr1que.github.io/atkfut-landing-ledger/
- Outra variação (clara/editorial): https://github.com/Paulo-Henr1que/atkfut-landing-catalogo

Site estático (`index.html` + `style.css`), sem build.

## Base de conteúdo

Tudo que a página afirma sobre o app vem do site original ([atkfornecedor.com](https://atkfornecedor.com/)): pedido mínimo de 5 peças, escolha de times e modelos, catálogo, preço de fornecedor, ofertas e notificações no app, pagamento pelo app, links oficiais da App Store e do Google Play e as 4 avaliações de clientes publicadas lá. Nenhum recurso, número ou depoimento foi inventado.

## Decisões de conformidade (Google Ads / TikTok Ads)

| Original | Nesta versão | Por quê |
|---|---|---|
| "Fornecedor Oficial" | "Atacado de camisas" | "Oficial" junto a marcas de terceiros agrava a política de bens falsificados / PI |
| "Direto da fonte, sem intermediário" | "Preço de atacado" | A razão social é "ATKFUT **Intermediações** Ltda." — dizer "sem intermediário" contradiz a própria empresa (Misrepresentation) |
| "Quanto vou ganhar?", "lucro", "renda garantida" | "Qual é a margem de revenda?", "resultado", "margem" | Menos palavras-gatilho de oportunidade de renda, mesmo em frases negativas |
| Mock do app sem aviso | "Imagem ilustrativa do app" | A tela mostrada não é captura real do aplicativo |
| "Lucre R$80 a R$130 por camisa", "+R$12.000/mês" | Simulador com os números do próprio visitante + FAQ "não dá para prometer um valor" | Alegação de renda não substanciada (Misrepresentation / Business Opportunity) |
| Painel com "Lucro do mês R$ 9.240" | Mock do app com catálogo, oferta e carrinho de 5 peças, sem valores | Mesmo motivo acima |
| "Multiplique o lucro", "mercado sempre quente" | "Repita o pedido quando fizer sentido" | Promessa implícita de resultado |
| — | Seção "É pra você?" com quem **não** deve entrar | Revisores de oportunidade de negócio valorizam expectativas realistas |
| — | Ilustrações de camisa genéricas, sem escudo nem marca | Evitar uso de marca de terceiros na página |

## Risco que continua fora do alcance da página

**Bens falsificados / propriedade intelectual.** Se o catálogo vende réplicas com escudos de clubes e logos de fabricantes sem licença, Google Ads e TikTok Ads podem reprovar ou suspender a conta independentemente do texto da landing page. Não use fotos de produto com marcas de terceiros nos criativos de anúncio. A solução definitiva é produto licenciado.

## Checklist antes de rodar anúncio

**Bloqueia aprovação (resolver antes de subir campanha):**
1. **Domínio próprio.** Não anuncie com `paulo-henr1que.github.io`: o domínio não bate com a marca anunciada e isso costuma virar reprovação por "Misrepresentation / identidade da empresa pouco clara". Use um domínio ou subdomínio da ATKFUT apontado para o GitHub Pages.
2. **Dados da empresa e contato visíveis.** Hoje a página só tem a razão social (a mesma que aparece na App Store: ATKFUT INTERMEDIACOES LTDA). Falta CNPJ, e-mail ou WhatsApp de atendimento e, de preferência, endereço. Há um `<!-- TODO -->` no rodapé do `index.html`.
3. **Política de privacidade.** A App Store aponta para `https://pedidoatacado.com/politicas-de-privacidade/`, mas é uma página da plataforma Pedido Atacado protegida por verificação anti-robô; confirme se ela cita a ATKFUT antes de linkar. Obrigatório se adicionar pixel do Google/TikTok, formulário ou cookies.

**Pode derrubar anúncio ou conta:**
4. **Criativos e palavras-chave sem marca de terceiro.** Nada de nome de clube, seleção ou fabricante (Nike, Adidas etc.) no texto do anúncio, nas palavras-chave ou nas imagens/vídeos. Fotos de camisa com escudo ou logo são o maior risco de suspensão por bens falsificados.
5. **Nada de promessa de ganho no anúncio.** A página evita isso; o anúncio precisa seguir a mesma linha (sem "lucre R$X", "renda extra garantida", "ganhe dinheiro").
6. **Loja do app.** O revisor pode abrir o link da App Store / Google Play. Se as capturas de tela do app mostram escudos e marcas de clubes, o risco de bens falsificados continua, mesmo com a página limpa.
7. **TikTok Ads:** se o anúncio for posicionado como oportunidade de revenda, verificar se a categoria exige aprovação prévia.
