# TechQuiz — Conexão IA

Quiz educativo sobre **Inteligência Artificial & Conceitos de TI**, desenvolvido com HTML, CSS e JavaScript puro para o projeto de Desenvolvimento Front-end para Web.

## Funcionalidades

- Página inicial com identidade visual própria e explicação de como jogar.
- Seis questões em `perguntas.json`, com alternativas, resposta correta, explicação e fonte.
- Feedback imediato, progresso, pontuação e reinício.
- Layout responsivo, navegação por teclado, foco visível e anúncios de feedback para tecnologias assistivas.
- Sem dependências externas, contas, coleta de dados ou serviços pagos.

## Integrantes e divisão de tarefas

**Pendente:** preencher os nomes e usuários GitHub reais do grupo antes da entrega. Não foram fornecidos na criação do projeto.

| Responsabilidade sugerida | Integrante |
| --- | --- |
| Página inicial e conteúdo | A definir pelo grupo |
| Tela de jogo e interações | A definir pelo grupo |
| CSS e revisão de acessibilidade | A definir pelo grupo |
| Questões, fontes e documentação | A definir pelo grupo |

Adicionar os integrantes reais em Settings > Collaborators. Cada integrante deve realizar e revisar suas próprias contribuições; este projeto inicial não representa participação individual do grupo.

## Executar localmente

Abra a pasta no VS Code e use a extensão Live Server no `index.html`.

Alternativamente, com Python instalado, execute dentro desta pasta:

```sh
python -m http.server 8000
```

Depois abra http://localhost:8000. O carregamento do JSON precisa de HTTP; abrir `index.html` diretamente por duplo clique pode bloquear o `fetch`.

## Arquivos

- `index.html`: estrutura semântica das telas.
- `style.css`: paleta, tipografia, componentes e adaptação para celular.
- `script.js`: leitura das perguntas e funcionamento do jogo.
- `perguntas.json`: fonte única dos dados; `resposta` é o índice da alternativa correta, começando em zero.
- `favicon.svg`: ícone vetorial original.
- `.nojekyll`: publicação estática no GitHub Pages.

## Identidade visual

Fundo verde-escuro `#101b19`, destaque verde-claro `#b5f4c8`, texto `#f0f5ed` e fonte de sistema Arial/Helvetica. A ilustração de conexões foi construída em SVG diretamente no HTML.

## Publicação no GitHub Pages

No repositório, abra Settings > Pages. Em Build and deployment, escolha Deploy from a branch, branch `main`, pasta `/ (root)` e salve. Aguarde a publicação e use o endereço HTTPS mostrado pelo GitHub.

## Trabalho em grupo

Crie branches para as próximas mudanças (por exemplo, `feature/pagina-inicial`, `feature/tela-jogo`, `feature/estilo-base` e `feature/perguntas-json`). Faça commits pequenos e integre as mudanças com revisão do grupo.

## Verificação antes de entregar

- [ ] Preencher integrantes e divisão real de tarefas.
- [ ] Adicionar os colaboradores no GitHub.
- [ ] Revisar as perguntas em grupo.
- [ ] Confirmar site publicado com HTTPS e abrir os links em janela anônima.
- [ ] Confirmar a tag `cp1-entrega` no repositório.
- [ ] Enviar no Blackboard os links do repositório e do site até 27/10/2026.

O CP1 exige a base visual e três ou mais questões; a lógica de jogo já está incluída como extensão funcional.

## Fontes das questões

- IBM: https://www.ibm.com/think/topics/machine-learning
- MDN, HTML: https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content
- MDN, HTTP: https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/Overview

As explicações foram redigidas para este quiz, a partir dos conceitos das fontes indicadas.
