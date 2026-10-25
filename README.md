# price-advisor-callback

Página estática usada como `redirect_uri` do OAuth do Mercado Livre durante o desenvolvimento do Price Advisor.

- Endereço: <https://marcellosantos160-hue.github.io/price-advisor-callback/>
- A página só exibe na tela os parâmetros `code` e `state` recebidos. Ela não guarda nem envia dados a nenhum servidor.
- A troca do `code` por um token é feita localmente, com PKCE. Este repositório não tem nenhuma credencial.
- Quando o site definitivo existir, o `redirect_uri` será trocado pelo domínio dele.
