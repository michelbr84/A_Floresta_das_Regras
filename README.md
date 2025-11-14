# Agente Mestre de Planejamento de Livro

Este repositório contém a implementação do Agente Mestre de Planejamento de Livro — um editor sênior de IA e coordenador de projeto responsável por criar um Plano Completo de Produção para livros infantis. Ele coordena sete ferramentas especializadas de Agentes de IA para fornecer conteúdo completo e pronto para produção de projetos de livros infantis.

## Visão Geral

O Agente Mestre de Planejamento de Livro aceita uma entrada em formato JSON que descreve um projeto de livro infantil, incluindo a ideia da história, personagens, temas, imagens, detalhes do autor e muito mais. Ele processa essas informações para padronizar, completar e organizar para sete sub-agentes:

1. **Plano da História** — Gera o plano geral da história, análise do público e proposta de valor.
2. **Estrutura Narrativa** — Define o arco completo da história, eventos-chave, ritmo e momentos emocionais.
3. **Guia de Personagens e Cenários** — Descreve personagens principais e secundários e cenários para guiar escritores e ilustradores.
4. **Storyboard / Rascunho Visual** — Detalha o fluxo visual página por página e sugestões de ilustrações.
5. **Manuscrito** — Produz o texto completo da narrativa dividido por páginas, pronto para revisão editorial.
6. **Plano Editorial e de Produção** — Descreve cronogramas, responsabilidades, orçamentos, estratégias de publicação e marketing.
7. **Registro de Direitos Autorais** — Prepara um documento detalhado para registro de direitos autorais garantindo proteção legal.

## Funcionalidades

- Harmoniza elementos da história em todos os documentos para manter consistência.
- Inferência lógica de detalhes narrativos faltantes com base no contexto.
- Mantém um tom de narrativa quente, amigável para crianças, emocional e claro.
- Gerencia imagens e metadados do autor junto com o conteúdo da história.

## Uso

Para usar o Agente Mestre de Planejamento de Livro, forneça os dados do seu livro infantil em formato JSON incluindo campos como `titulo`, `ideia`, `tema`, `personagens`, `faixa_etaria`, `autor`, `idioma`, `moral`, `imagens` e outros.

O agente analisa esta entrada, organiza os dados, infere quaisquer partes faltantes e gera sete blocos estruturados de conteúdo prontos para cada sub-agente de IA especializado.

## Contribuição

Contribuições são bem-vindas! Por favor, faça um fork e envie pull requests seguindo os padrões de codificação e documentação do projeto.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para detalhes.

## Contato

Para dúvidas ou suporte, abra uma issue ou contate o mantenedor em [email@exemplo.com].