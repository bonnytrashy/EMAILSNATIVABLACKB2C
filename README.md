# Esquenta da Black Nativa 2026 | E-mail B2C

E-mail de abertura do Esquenta da Black Nativa, da Nativa Ecocosméticos.

## Arquivos

| Arquivo | O que é |
| --- | --- |
| `email-esquenta-black.html` | HTML completo, pronto para colar no editor de HTML da RD Station |
| `email-esquenta-black.txt` | Versão em texto puro |
| `preview.html` | Prévia lado a lado em 600 px (desktop) e 375 px (celular) |
| `previews/*.png` | Capturas em 600 px e 375 px, nos modos claro e escuro |
| `images/logo-nativa.png` | Logo com fundo branco embutido (continua legível no modo escuro) |
| `images/esquenta-black-cremes-multifuncionais.jpg` | Imagem principal (1086 x 1448, exibida a 600 px) |
| `images/p1.jpg` a `images/p6.jpg`, `images/sequiserusar.jpg`, `images/1709936094_logo_end.webp` | Arquivos originais da pasta de recursos da campanha |
| `vercel.json` | Configuração da hospedagem na Vercel |

## Hospedagem das imagens (Vercel)

O repositório é privado, mas a Vercel publica o conteúdo dele como site estático, e é de lá que o e-mail
puxa as imagens. Para publicar: na Vercel, **Add New > Project**, importe `bonnytrashy/EMAILSNATIVABLACKB2C`
sem framework e sem comando de build. A raiz do domínio abre a prévia (`preview.html`).

Com o projeto publicado como `emailsnativablackb2c`, as URLs ficam assim (troque o domínio se o projeto tiver outro nome):

- `https://emailsnativablackb2c.vercel.app/images/logo-nativa.png`
- `https://emailsnativablackb2c.vercel.app/images/esquenta-black-cremes-multifuncionais.jpg`

O `vercel.json` libera as imagens com cache de 7 dias e `Access-Control-Allow-Origin: *`.

Para ver a prévia localmente, rode um servidor na pasta (por exemplo `python -m http.server`) e abra `preview.html`.

## Assunto e pré-cabeçalho

- **Assunto (no HTML):** O esquenta da Black Nativa começou ☀️
- **Teste A/B:**
  - Seu cabelo já entrou no clima do verão?
  - Os 4 queridinhos do verão estão com 20% OFF
- **Pré-cabeçalho:** Os Cremes Multifuncionais com 20% OFF e kits com até 30% OFF no site.

## Antes de disparar, preencher

Busque por `PREENCHER` no HTML:

1. `PREENCHER_URL_LOGO`: URL da Vercel de `images/logo-nativa.png`
2. `PREENCHER_URL_IMAGEM_PRINCIPAL`: URL da Vercel de `images/esquenta-black-cremes-multifuncionais.jpg`

Use as versões `logo-nativa.png` e `esquenta-black-cremes-multifuncionais.jpg` no e-mail, não os originais:
o Outlook não exibe `.webp`, e os originais `p*.jpg` têm de 3 a 4,5 MB, pesados demais para e-mail.

Descadastro e endereço ficam a cargo do rodapé automático da RD Station.

## UTMs

`utm_source=email&utm_medium=crm&utm_campaign=esquenta_black_2026` com `utm_content`:
`logo`, `imagem_principal`, `botao_principal`, `link_kits`.
