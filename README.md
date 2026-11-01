# Página de vendas: Mapa dos Concursos 2027

Site estático (HTML puro), pronto para a Vercel.

## Configurar
Abra `index.html` e preencha as duas linhas no topo:

```js
window.CHECKOUT_URL = "https://pay.hotmart.com/SEU_CODIGO";
window.PIXEL_ID = "SEU_PIXEL_ID";
```

Os parâmetros de UTM da URL da página são repassados automaticamente para o checkout.
