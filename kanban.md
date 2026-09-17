# Kanban — Acaízinho da Sandra 🍇

Site de uma página no Netlify: cardápio (açaizinho 70ml + potes), venda pelo WhatsApp.

## Fora do escopo (decisão da Sandra)
- Horário de funcionamento no site (pedidos combinados no WhatsApp)
- Foto real da Sandra/produção (cliente prefere manter a foto atual gerada por IA)

## Todo (a fazer)
- (nada no momento)

## Doing (fazendo)
- Cardápio de montagem do pedido (#pedido) com envio ao WhatsApp (investigando `*` na mensagem gerada)

## Done (pronto)

- [x] Estrutura inicial inspirada no Com Amor GV, com cores do sistema (`C:\GitHub\acaizinho`)
- [x] Nome exibido: Acaízinho da Sandra; WhatsApp (33) 99991-9339; Instagram @acaizinhodasandra
- [x] Logo com fundo transparente (`logo.png` master, `logo.webp` web 99KB, `favicon.png`)
- [x] Cardápio real em tabelas HTML: 8 sabores varejo/atacado + potes 2L/5L/10L e Zero 2L (10L R$ 120,00 confirmado)
- [x] Seção Whey com foto e resumo (10g proteína, 76kcal, zero açúcar/lactose, sem glúten)
- [x] Galeria com 4 fotos + seção "Quem provou, aprovou" (transcrição + foto do depoimento)
- [x] Sem seção de acompanhamentos (não há ainda)
- [x] Pagamento: somente Pix ou dinheiro (sem cartão)
- [x] Mensagens do WhatsApp sem emoji (estava quebrando como �)
- [x] Governador Valadares/MG na seção de contato
- [x] Header compacto, tabelas com cabeçalho sólido, fontes maiores, responsivo mobile/tablet
- [x] Nota do atacado em 2 linhas + aviso de caixa mista (valor pode variar)
- [x] Preços sempre com ,00 e `R$&nbsp;valor` (sem quebra de linha)
- [x] Textos sem travessão (—) para tom mais natural
- [x] Cardápio refeito em grid (sem `<table>`): cabeçalho em barra sólida, colunas lado a lado
- [x] Colunas com largura fixa + divisórias verticais (alinhamento de tabela de verdade)
- [x] Mobile (até 480px): sabores viram cartões empilhados com rótulos Varejo/Atacado, sem rolagem lateral
- [x] Títulos Whey/Galeria/Depoimento no padrão kicker (sem etiqueta estilo botão)
- [x] Galeria: ordem 1-2-3 (img-2, img-5, img-12, img-6), miniaturas quadradas menores
- [x] Galeria 2x2 no desktop (igual ao mobile)
- [x] Depoimento invertido + quebra de linha após "…"
- [x] Bug dos preços como pílula/`RR$ nbsp;` corrigido (colisão da classe `.num` + entidade quebrada)
- [x] Foto da seção Sabores: `img-4`; galeria sem `img-4` e sem imagens de dia/data (`img-5` no lugar)
- [x] Títulos com etiqueta inline: Whey e Galeria economizando espaço vertical
- [x] `netlify.toml`, `.gitignore`, `README.md`
- [x] Repo público no GitHub: https://github.com/Hal-Franca/acaizinho-da-sandra (branches `prod`, `staging`, `dev`; `prod` é a principal)
- [x] Seção Monte seu pedido (#pedido): 8 sabores + 4 potes com quantidades, nome/bairro/pagamento/obs, gera mensagem pronta no WhatsApp sem total estimado
