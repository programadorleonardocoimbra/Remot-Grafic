# Remot Grafic — Gerador de Orçamentos e Pedidos

Site estático responsivo para a **Gráfica Remota**, desenvolvido em HTML, CSS e JavaScript puro. Ideal para abrir no IntelliJ IDEA e hospedar gratuitamente no GitHub Pages.

## Recursos
- Interface inspirada no layout de referência: formulário à esquerda, prévia em cupom amarelo à direita.
- Alternância entre **Orçamento** e **Pedido**.
- Cliente, contato, e-mail, forma de pagamento, datas e observações.
- Inclusão, edição e exclusão de produtos, com quantidade e preço unitário.
- Total calculado automaticamente (quantidade × preço unitário).
- Indicador **PEDIDO PAGO** e data de pagamento quando marcado.
- Impressão e geração de PDF usando a opção **Salvar como PDF** do navegador.
- Autosalvamento dos dados no armazenamento local do navegador (localStorage).
- Layout otimizado para celular com campos maiores.
- Botão Limpar Campos com confirmação.

## Abrir no IntelliJ IDEA
1. Extraia o ZIP.
2. No IntelliJ IDEA, clique em **File > Open** e selecione a pasta `Remot-Grafic`.
3. Abra `index.html` em um navegador ou execute pelo recurso de pré-visualização do IntelliJ.
4. Preencha dados, adicione itens e clique em **Orçamento em PDF** ou **Pedido em PDF**.
5. No diálogo de impressão, selecione **Salvar como PDF**, formato A4 e ative **Gráficos em segundo plano** quando necessário.

## Publicar no GitHub Pages
1. Crie um repositório, por exemplo `remot-grafic`.
2. Envie **os arquivos dentro da pasta Remot-Grafic** para a raiz da branch `main`, mantendo `index.html` na raiz.
3. No GitHub, entre em **Settings > Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`; salve.
5. O endereço ficará semelhante a `https://SEU-USUARIO.github.io/remot-grafic/`.

## Observações importantes
- GitHub Pages serve apenas arquivos estáticos. Não há banco de dados, login ou sincronização entre dispositivos.
- Os dados salvos ficam neste navegador e podem ser perdidos se o usuário limpar seus dados de navegação.
- O botão PDF utiliza o diálogo nativo de impressão e não envia dados a servidores.
- Não trata de documento fiscal; os cupons exibem **Cupom Não Fiscal**.
- Para imprimir as cores do cupom, habilite gráficos de fundo na configuração de impressão.

## Estrutura
```text
Remot-Grafic/
├── index.html
├── styles.css
├── app.js
├── README.md
└── assets/
    ├── logo-colorida.png
    └── logo-preta.png
```
