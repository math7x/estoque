<h1 align="center">Contagem de Estoque</h1>

<p align="center">
  Aplicativo web responsivo para tornar a conferência física do estoque mais simples, rápida e confiável.
</p>

<p align="center">
  <img alt="HTML" src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img alt="CSS" src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111">
  <img alt="Mobile first" src="https://img.shields.io/badge/interface-mobile--first-0EA5E9?style=flat-square">
</p>

## Problema que resolve

A contagem manual costuma exigir anotações separadas, conferências repetidas e retrabalho para organizar o resultado. Este projeto concentra o processo em uma única tela, adaptada para celular, e ajuda a identificar rapidamente itens pendentes ou abaixo do estoque mínimo.

## Principais recursos

- lista de produtos organizada por local e categoria;
- pesquisa por nome ou código;
- filtro de itens ainda não contados;
- indicador de progresso da contagem;
- destaque visual para estoque mínimo e itens sensíveis;
- salvamento automático no próprio navegador;
- exportação do resultado para planilha Excel;
- layout responsivo, modo claro/escuro e uso como atalho na tela inicial do celular.

## Como funciona

1. A pessoa responsável abre o sistema no celular ou computador.
2. Filtra os produtos pelo local onde a contagem será realizada.
3. Informa a quantidade física encontrada em cada item.
4. O progresso e os alertas são atualizados automaticamente.
5. Ao finalizar, o resultado pode ser exportado para conferência ou arquivamento.

## Execução local

O projeto não exige instalação ou servidor de aplicação. Basta abrir o arquivo `index.html` em um navegador moderno. Para uso recorrente no celular, consulte o guia [COMO_USAR.md](./COMO_USAR.md).

> A biblioteca de exportação da planilha é carregada por CDN. Portanto, a interface e o salvamento local funcionam sem backend, mas a exportação pode exigir conexão com a internet.

## Publicação com Vercel

O repositório é integrado ao Vercel para disponibilizar o aplicativo pela web e manter a versão online alinhada às atualizações do projeto.

🔗 **Acessar a aplicação:** [estoque-eta-six.vercel.app](https://estoque-eta-six.vercel.app/)

## Privacidade dos dados

As quantidades digitadas ficam armazenadas no `localStorage` do navegador utilizado. O aplicativo não possui login, banco de dados ou envio automático das informações para servidores externos.

Isso significa que:

- cada navegador e dispositivo mantém sua própria contagem;
- limpar os dados do navegador pode apagar o progresso salvo;
- para transferir ou arquivar o resultado, deve-se utilizar a exportação para planilha.

## Estrutura do projeto

```text
.
├── index.html       # aplicação completa
├── COMO_USAR.md    # orientações de publicação e uso
└── teste.html      # arquivo auxiliar de testes
```

## Tecnologias

- HTML5;
- CSS3 responsivo;
- JavaScript sem framework;
- Web Storage API;
- SheetJS para geração da planilha.

## Contexto

Projeto desenvolvido para facilitar uma necessidade operacional real: realizar contagens com menos papel, menos etapas manuais e melhor visibilidade do andamento.

---

Desenvolvido por [math7x](https://github.com/math7x).
