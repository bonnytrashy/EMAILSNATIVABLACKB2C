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

Este repositório é privado, então as imagens não podem ser servidas daqui. Suba as duas imagens de `images/`
no gerenciador de imagens da RD Station e cole as URLs geradas no HTML (veja a lista abaixo).

Para ver a prévia localmente, rode um servidor na pasta (por exemplo `python -m http.server`) e abra `preview.html`.

## Assunto e pré-cabeçalho

- **Assunto (no HTML):** O esquenta da Black Nativa começou ☀️
- **Teste A/B:**
  - Seu cabelo já entrou no clima do verão?
  - Os 4 queridinhos do verão estão com 20% OFF
- **Pré-cabeçalho:** Os Cremes Multifuncionais com 20% OFF e kits com até 30% OFF no site.

## Antes de disparar, preencher

Busque por `PREENCHER` no HTML:

1. `PREENCHER_URL_LOGO`: URL pública de `images/logo-nativa.png`
2. `PREENCHER_URL_IMAGEM_PRINCIPAL`: URL pública de `images/esquenta-black-cremes-multifuncionais.jpg`

Descadastro e endereço ficam a cargo do rodapé automático da RD Station.

## UTMs

`utm_source=email&utm_medium=crm&utm_campaign=esquenta_black_2026` com `utm_content`:
`logo`, `imagem_principal`, `botao_principal`, `link_kits`.
