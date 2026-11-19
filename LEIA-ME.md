# Mercado — site reorganizado

## Como abrir
Abra `index.html` no navegador. O projeto é estático (HTML, CSS e JavaScript) e não exige instalação.

## Estrutura
- `index.html`: página inicial.
- `pages/`: páginas de Alimentos, Limpeza, Higiene pessoal, Carnes, Frutas, Congelados e Ofertas.
- `carrinho.html`: carrinho com contador, alteração de quantidades e remoção de itens.
- `buscar.html`: pesquisa de produtos.
- `css/base.css`: estilos gerais e variáveis.
- `css/shared.css`: cabeçalho e rodapé compartilhados.
- `css/components.css`: banners, categorias, cards e carrinho.
- `js/layout.js`: injeta cabeçalho e rodapé em todas as páginas.
- `js/catalogo.js`: categorias e catálogo demonstrativo.
- `js/app.js`: carrinho com persistência no navegador (`localStorage`).
- `assets/images/`: imagens originais fornecidas, organizadas.

## Importante antes de publicar
O carrinho funciona no navegador e mantém os itens salvos no dispositivo. O botão de finalizar pedido é apenas demonstrativo: para vender de verdade, será necessário integrar backend, estoque, frete, atendimento e pagamento. Os produtos e preços que não estavam definidos no material original estão identificados como demonstrativos no site. Os três preços originais (feijão, arroz e óleo) foram preservados.
