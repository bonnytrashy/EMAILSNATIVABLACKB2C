# Esquenta da Black Nativa 2026 | E-mail B2C

E-mail de abertura do Esquenta da Black Nativa, da Nativa Ecocosméticos.

## Arquivos

| Arquivo | O que é |
| --- | --- |
| `email-esquenta-black.html` | HTML completo, pronto para colar no editor de HTML da RD Station |
| `email-esquenta-black.txt` | Versão em texto puro |
| `images/logo-nativa.png` | Logo com fundo branco embutido (continua legível no modo escuro) |
| `images/sequiserusar.jpg` | Imagem principal do e-mail (1086 x 1448, 452 KB, exibida a 600 px) |
| `images/verao-cachos-vitoria.jpg` | Segunda foto do e-mail, no bloco dos kits (recorte 4:3 da p1, 152 KB) |
| `images/p1.jpg` a `images/p6.jpg`, `images/1709936094_logo_end.webp` | Arquivos originais da pasta de recursos da campanha |
| `vercel.json` | Configuração opcional, caso queira hospedar as imagens na Vercel |

## Hospedagem das imagens

O repositório é público e o e-mail puxa as imagens pelo jsDelivr, um CDN gratuito que entrega arquivos de
repositórios públicos do GitHub. As URLs já estão no HTML:

- `https://cdn.jsdelivr.net/gh/bonnytrashy/EMAILSNATIVABLACKB2C@main/images/logo-nativa.png`
- `https://cdn.jsdelivr.net/gh/bonnytrashy/EMAILSNATIVABLACKB2C@main/images/sequiserusar.jpg`
- `https://cdn.jsdelivr.net/gh/bonnytrashy/EMAILSNATIVABLACKB2C@main/images/verao-cachos-vitoria.jpg`

Para trocar uma imagem, envie um arquivo com **outro nome** e atualize o HTML. O jsDelivr guarda cópia em
cache por até 7 dias, então substituir um arquivo com o mesmo nome pode continuar mostrando a versão antiga.

Não renomeie, mova ou apague esses três arquivos nem deixe o repositório privado depois do disparo: os
e-mails já enviados continuam buscando as imagens nesses endereços.

## Assunto e pré-cabeçalho

- **Assunto (no HTML):** O esquenta da Black Nativa começou ☀️
- **Teste A/B:**
  - Seu cabelo já entrou no clima do verão?
  - Os 4 queridinhos do verão estão com 20% OFF
- **Pré-cabeçalho:** Os Cremes Multifuncionais com 20% OFF e kits com até 30% OFF no site.

## Importar na RD Station

O HTML está pronto: não há nada a preencher. Importe `email-esquenta-black.html` no editor de HTML da RD Station.
Descadastro e endereço ficam a cargo do rodapé automático da RD.

O e-mail usa `logo-nativa.png`, `sequiserusar.jpg` e `verao-cachos-vitoria.jpg`. Os outros arquivos de `images/`
ficam só como acervo: o Outlook não exibe `.webp`, e os originais `p*.jpg` têm de 3 a 4,5 MB, pesados demais para e-mail.

## UTMs

`utm_source=email&utm_medium=crm&utm_campaign=esquenta_black_2026` com `utm_content`:
`logo`, `imagem_principal`, `botao_principal`, `imagem_kits`, `link_kits`.

## E-mail B2C 1: linha destaque com 20% OFF (`/emailb2cblack1`)

Arquivo: `emailb2cblack1/index.html`, publicado em `https://emailsnativablackb2c.vercel.app/emailb2cblack1`.
Imagem principal: `images/sequiserusar.jpg`. Logo: `images/logo-nativa.png`.

- **Assunto (opções):**
  1. 20% OFF nos kits da linha destaque
  2. Seus favoritos do verão com 20% OFF ☀️
  3. No Pix, mais 5%. E NatCoins em dobro!
- **Pré-cabeçalho:** 7 kits do verão com 20% OFF. No Pix, mais 5%. E NatCoins em dobro até 09/11.

Grade com os 7 kits da linha destaque (fotos `images/b2c1-kit-1.jpg` a `b2c1-kit-7.jpg`, 480 px, tiradas da loja), links com UTM `utm_content=b2c1_kit_1` a `b2c1_kit_7`.
Sem rodapé próprio: endereço e descadastro ficam com o rodapé automático da RD Station.

Botão e imagem principal levam para a home do site (`utm_content=b2c1_botao_principal` e `b2c1_imagem_principal`). O HTML está pronto para importar, sem campos a preencher.