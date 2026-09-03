# QR Code com Logo

Ferramenta HTML local para gerar QR Codes de 1000 por 1000 pixels com uma logomarca central.

## Arquivos

| Arquivo | Função |
|---|---|
| `QR Code v5.html` | Interface e lógica do gerador, versão registrada no commit `v6` |
| `logo.png` | Referência da logomarca central incorporada ao HTML |

## Como usar

1. Abra `QR Code v5.html` em um navegador.
2. Informe o endereço desejado.
3. Selecione `Gerar QR Code`.
4. Baixe o JPG para visualizar o link em `Comentários`, `Título` e `Assunto` nas propriedades do Windows.
5. Use o PNG quando preferir o formato sem perdas; o link fica gravado nos metadados técnicos `iTXt`.

## Requisito

É necessário acesso à internet durante o uso, pois a biblioteca `qrcode` versão 1.5.1 é carregada pelo CDN jsDelivr.

O processamento ocorre no navegador. O endereço informado é gravado somente no QR Code e nos metadados da imagem baixada.
