# Banco de leitura

App para treinar a leitura em **português europeu**, do 1.º ao 4.º ano do ensino básico, no estilo NeuroPlay.

## Como usar

Abrir o ficheiro `index.html` num navegador (Chrome, Safari, Edge ou Firefox). Não precisa de instalação nem de internet, porque os 1317 exercícios estão incluídos no próprio ficheiro.

## O que tem

- **Perfis** para várias crianças, cada uma com o seu ano, mapa, progresso e caderneta.
- **Mapa por ano** com 48 temas (letras → sílabas → palavras → frases → textos), divididos em níveis curtos de cerca de 8 exercícios.
- **Tipos de exercício:** escolha múltipla, palavra e imagem, ordenar sílabas ou palavras, separação silábica, compreensão de textos e leitura em voz alta.
- **Revisões em jogo** a cada 3 temas e uma grande revisão no fim de cada ano: balões, memória, certo ou errado e comboio.
- **Desafio das palavras difíceis** com os exercícios em que a criança errou.
- **Autocolantes e estrelas:** 120 autocolantes normais e autocolantes dourados nas revisões.
- **Fichas para imprimir** em A4, por tema ou mistas, com página de soluções opcional.
- **Área para adultos** com progresso por tema, exercícios a treinar, gestão de perfis, guia de utilização, definições de voz e som, e cópia de segurança.

## Estrutura

| Ficheiro | Conteúdo |
|---|---|
| `index.html` | A app completa (HTML, CSS e JavaScript, sem dependências) |
| `dados/banco.json` | O banco de exercícios em JSON: temas, textos, itens e respostas |

O progresso fica guardado no navegador (`localStorage`). Para passar para outro aparelho, use a cópia de segurança em **Para adultos → Definições**.

## Notas

- Exercícios alinhados com as Aprendizagens Essenciais de Português (DGE), 1.º ciclo.
- Os resultados servem para orientar o treino. Não são um diagnóstico.
