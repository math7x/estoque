# Como usar e publicar

O aplicativo principal está no arquivo `index.html` e funciona diretamente em navegadores modernos.

## Usar localmente

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Pesquise ou filtre os itens por local.
4. Informe a quantidade física encontrada em cada produto.

As quantidades são salvas automaticamente no próprio navegador.

## Versão online

O projeto está integrado ao Vercel e pode ser acessado em:

[https://estoque-eta-six.vercel.app/](https://estoque-eta-six.vercel.app/)

Quando a integração do repositório com o Vercel está ativa, as atualizações enviadas para a branch principal geram uma nova publicação.

## Adicionar à tela inicial do iPhone

1. Abra o endereço da aplicação no Safari.
2. Toque em **Compartilhar**.
3. Selecione **Adicionar à Tela de Início**.
4. Confirme o nome e toque em **Adicionar**.

## Recursos da contagem

- pesquisa por nome ou código;
- filtros por local e itens ainda não contados;
- indicador de progresso;
- destaque de itens que atingiram o estoque mínimo;
- salvamento automático no navegador;
- exportação do resultado para planilha Excel.

## Atenção aos dados

O progresso utiliza o armazenamento local do navegador. Cada aparelho mantém seus próprios dados, e a limpeza dos dados do navegador pode apagar a contagem. Para arquivar ou transferir o resultado, utilize a exportação para planilha.

## Atualizar produtos

A lista fica definida na constante `PRODUTOS`, dentro do `index.html`. Depois de alterar essa lista, teste a busca, os filtros, o preenchimento e a exportação antes de publicar.
