# Acaízinho da Sandra 🍇

Site institucional de uma página para o **Acaízinho da Sandra**: açaizinho cremoso 70ml em 8 sabores (varejo e atacado) + açaí no pote 2L, 5L e 10L. Venda 100% pelo WhatsApp.

- **Status:** pronto para publicar
- **Hospedagem:** Netlify (plano grátis, sem build, sem plugins) - deploy via GitHub conectado ou Netlify Drop
- **Custo:** R$ 0

## Estrutura

```
acaizinho-da-sandra/
├── index.html          # site inteiro (HTML + CSS inline, sem dependências)
├── netlify.toml        # headers de segurança p/ Netlify
├── assets/
│   └── img/            # logo + fotos (logo.webp usada no site, logo.png = master)
├── .gitignore
└── README.md
```

## Ver localmente

Duplo clique em `index.html`: abre no navegador, sem servidor.

## Publicar (Netlify Drop)

1. Acesse `app.netlify.com/drop`
2. Arraste a pasta `acaizinho-da-sandra` inteira
3. Pronto: link `*.netlify.app` (renomeável em Site settings → Change site name)
4. Para atualizar: edite os arquivos, arraste a pasta de novo em Deploys

Ou conecte o repo GitHub no Netlify (sem comando de build, Publish directory: `.`).

## Editar conteúdo

- Preços: tabelas em `index.html` (seções `#sabores` e `#potes`)
- WhatsApp: trocar `5533999919339` nos links `wa.me/...`
- Fotos: arquivos em `assets/img/` referenciados no HTML
- Logo: `logo.webp` (web, 512px) gerada de `logo.png` (master 768px, mantido no repo)
- Fotos: `.webp` redimensionados (q78-85, largura max 768px); originais pesados removidos

## Imagens (fontes e masters)

- `logo.png` — master da logo (fundo transparente), mantido para regenerar `logo.webp`

## Links

- Instagram: https://www.instagram.com/acaizinhodasandra/
- WhatsApp: +55 33 99991-9339 → https://wa.me/5533999919339

## Cores (do sistema em C:\GitHub\acaizinho + identidade da marca)

- Fundo escuro ameixa `#2A1230`, açaí `#5B1F4D`, berry `#8E2A78`
- Rosa marca `#D81B8C`, teal `#0EA5A0`, dourado `#E8B84B`, creme `#FFF8F1`
