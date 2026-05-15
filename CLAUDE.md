# CLAUDE.md

## Visão Geral

Este repositório armazena snapshots de feeds XML do Gugacast. Não há aplicação
compilável aqui; o conteúdo principal são arquivos XML versionados.

## Estrutura do Repositório

- `feed.xml`: feed principal.
- `feed-secreto.xml`: variante adicional do feed.

## Fluxo de Trabalho

- Trate o repositório como dados estáticos, não como código executável.
- Não há build, testes automatizados ou pipeline de execução a documentar.
- Se precisar validar mudanças, use um editor ou validador XML; não reestruture o arquivo sem necessidade.

## Convenções e Limites

- Preserve XML bem formado, encoding, ordem dos elementos e namespaces existentes.
- Evite reformatação desnecessária; whitespace gera ruído grande no diff.
- Não altere URLs, GUIDs, datas, títulos ou `enclosure` sem instrução explícita.
- Se precisar ajustar os dois feeds, compare ambos para manter coerência editorial.

## Peculiaridades do Projeto

- O repositório é essencialmente uma base de dados manual em XML.
- Os commits recentes são correções incrementais no conteúdo do feed, não mudanças de infraestrutura.
