---
source-git-commit: d3e36cef27fce533e9435717d428d54b982fd427
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---
# Documentação colaborativa do Advertising Cloud

Este é o repositório de documentação do Adobe Advertising Cloud, incluindo documentos entre produtos, DSP e TV. (Posteriormente, incluirá documentos para Creative e Pesquisa.)

**Observação: Esta página não é publicada na documentação voltada para o cliente.**

## Índice

+ `TOC.md` na raiz de qualquer guia do usuário fornece a organização dos tópicos contidos no guia.
+ Cada guia do usuário tem um `TOC.md` exclusivo, no qual é possível ordenar todas as páginas/tópicos, conforme necessário.


## Guia do usuário

+ A introdução ao guia do usuário é chamada `overview.md`
+ Cada tópico no guia do usuário tem um diretório distinto.
   + Se houver um tópico no guia chamado *Implementation*, o diretório correspondente será `/implementation`
+ Todos os ativos de imagem são armazenados em `/assets` na raiz do guia do usuário.
   + Todas as imagens no diretório `/assets` serão localizadas.
   + Nenhuma imagem no diretório `/no-localize` será localizada (há uma surpresa). Isso pode ser usado para garantir versões in loc que os ativos específicos não sejam reproduzidos desnecessariamente.

## Metadados do guia do usuário

+ Os metadados que descrevem o guia do usuário são armazenados no `TOC.md`. Isso inclui:
   + produto - nome do produto/recurso.
   + nuvem - nuvem à qual este produto pertence.
   + público-alvo - público-alvo ou arquétipo no qual o guia é direcionado.
   + guia do usuário - nome do guia do usuário.

## Metadados de página

+ Os metadados necessários para descrever um documento são armazenados como parte de cada página individual. Isso inclui:
   + título - título da página
   + descrição - descrição da página
   + seo-title - título alternativo seo
   + descrição SEO - título alternativo para fins de SEO
   + abreviado - (campo opcional)
   + index - sim/não - a página será indexada pela plataforma de pesquisa Adobe
   + traduzir - sim/não - esta página será localizada
   + beta - este produto é beta?
   + redirecionar - pode ser usado para criar uma referência para uma nova página, caso seja necessário
   + doc-type: referência (padrão) / solução de problemas / desenvolvedor / tutorial / kb / whitepaper

## Mais Informações

Para obter mais instruções de publicação, guias de estilos, amostras e outros recursos, consulte:

+ [Contribuição das diretrizes do autor  **especificamente para o Advertising Cloud**](https://wiki.corp.adobe.com/pages/viewpage.action?spaceKey=EfficientFrontier&amp;title=Contributing+Author+Guidelines+for+Advertising+Cloud+Help)
+ [Criação colaborativa para todos os autores de Adobe](https://experienceleague.adobe.com/docs/authoring-guide-exl/using/home.html)

Consulte também:

+ contribuinte.md Para obter uma visão geral de como contribuir para a documentação.

<!-- * guidelines.md For an overview on what is expected in contributions and how to compose your documentation contributions. -->
+ code-of-behavior.md Para obter uma visão geral dos padrões de comportamento que esperamos enquanto você contribui para este projeto de documentação.
