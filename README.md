# XRPL Paper Wallet (Offline) — HTML + xrpl.js

Gerador **offline** de **Paper Wallet** para **XRP Ledger (XRP)** usando **[xrpl.js](https://github.com/XRPLF/xrpl.js)** e **qrcode**.  
Tudo roda **no navegador**, sem servidores.

> **Aviso**: Paper Wallet é útil para **estudo/backup frio**. Para valores reais, prefira **hardware wallets**.  
> Se usar este app, **rode offline** e guarde a **chave secreta** com extremo cuidado.

## Recursos
- Geração local (`ed25519` por padrão).
- Exibe **Classic Address** (r…), **X-Address**, **Secret** (family seed `s…`) e **QR Codes**.
- Fundo gráfico estilizado (Opção 2).
- Botões: **Imprimir**, **Salvar .txt**, **Limpar**.
- Zero chamadas de rede (exceto se usar CDNs).

## Como usar
1. Baixe este repositório.
2. Coloque `xrp_option2.png` ao lado de `index.html`.
3. Abra `index.html` no navegador (offline de preferência).
4. Clique **Gerar carteira** → anote ou imprima.
5. Guarde o papel em cofre. **Nunca compartilhe a chave secreta**.

## Licença
[MIT](./LICENSE)
