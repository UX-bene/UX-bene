# Digest NN/g - 29/09/2026

> 9 conteúdos. Temas: IA e transparência, contexto para agentes, prototipagem com IA, processo editorial com IA, design de produtos de IA, empatia e jornada do usuário, heurísticas de usabilidade.

| # | Conteúdo | Tipo | Tema | Sobre (1 linha) |
|---|---|---|---|---|
| 1 | Quando divulgar o uso de IA? O framework PACED | Artigo | IA / Conteúdo | Cinco fatores para decidir se e como revelar que IA participou da criação. |
| 2 | Os 3 papéis do contexto para agentes de IA | Artigo | IA | Contexto global, local e ambiente: como usuários avançados organizam o que o agente sabe. |
| 3 | Teste interações complexas mais cedo com prototipagem por IA | Artigo | Design Process / IA | Processo de 6 passos para criar protótipos interativos com IA e testá-los antes do desenvolvimento. |
| 4 | A IA ajuda a escrever um artigo, mas não assume a responsabilidade por ele | Artigo | IA / Editorial | Como a NN/G usa IA na edição sem terceirizar o julgamento editorial. |
| 5 | Projetando produtos e recursos de IA: guia de estudos | Artigo (guia) | IA / Estratégia | Curadoria em 4 seções sobre valor, prompts, recomendações por tipo de produto e estado da arte. |
| 6 | Mapeamento de empatia: o primeiro passo do design thinking | Artigo | Design Process | Mapa de 4 quadrantes (diz, pensa, faz, sente) para alinhar o time sobre o usuário. |
| 7 | Journey Mapping 101 | Artigo | Design Process | Os 5 componentes de um mapa de jornada e como ele difere de outros mapas. |
| 8 | 10 heurísticas de usabilidade para design de interfaces | Artigo | Design de interação | Os princípios de Nielsen, inalterados há 30 anos. |
| 9 | Como conduzir uma avaliação heurística | Artigo | Métodos / Design Process | Passo a passo com 3 a 5 avaliadores independentes. |

---

## 1. Quando divulgar o uso de IA? O framework PACED
**Tipo:** Artigo | **Tema:** IA / Conteúdo | **Publicado:** 25/09/2026 | **Original:** [When Should You Disclose AI Use? The PACED Framework](https://www.nngroup.com/articles/disclose-ai-paced/)

### Sobre o que é
O artigo argumenta que não existe regra universal para divulgar o uso de IA na criação de conteúdo. As reações do público variam conforme o contexto, então a NN/G propõe cinco fatores (PACED) para avaliar cada caso antes de decidir.

### Aprofundamento
A base é uma revisão de 47 estudos. A conclusão central é que não houve uma reação única do público à divulgação: em alguns contextos há penalidade de confiança, em outros nenhum efeito mensurável. Isso desmonta tanto o "sempre divulgue" quanto o "nunca divulgue".

Há um paradoxo da divulgação: leitores dizem querer ser informados, mas avaliam pior o conteúdo quando a divulgação aparece. Isso cria um dilema real para quem produz. Existe também o risco de terceiros: se o uso de IA for exposto depois por uma plataforma, e não revelado voluntariamente, a reação negativa tende a ser mais forte.

O mecanismo por trás das penalidades, segundo o texto, é a percepção de substituição: leitores punem mais o uso de IA quando acreditam que ela substituiu uma contribuição humana significativa, como criatividade, sinceridade ou julgamento pessoal. Por isso conteúdo humano e emocional (cartas pessoais, trabalho criativo) sofre escrutínio maior que conteúdo transacional (lembrete de consulta).

**Framework PACED**
1. **P - Policy (política):** exigências legais (como o AI Act da UE) e regras de plataformas podem obrigar a divulgar.
2. **A - Audience (público):** atitudes em relação à tecnologia; públicos favoráveis a tecnologia mostram penalidades de confiança menores.
3. **C - Context (contexto):** comunicações centradas no humano sofrem mais que as transacionais.
4. **E - Expectations (expectativas):** normas do setor e práticas da organização definem se o leitor espera a divulgação.
5. **D - Degree (grau de uso):** contribuições substanciais pedem mais atenção à divulgação, com um trade-off entre transparência e reputação.

### Pontos-chave
- 47 estudos revisados; sem reação consistente à divulgação.
- Paradoxo: leitores pedem divulgação, mas avaliam pior o conteúdo divulgado.
- Ser exposto por terceiros costuma doer mais que divulgar por conta própria.
- Penalidade cresce quando a IA parece ter substituído criatividade, sinceridade ou julgamento.
- PACED = Policy, Audience, Context, Expectations, Degree of AI use.

### Como pode ajudar
Serve para definir políticas de transparência sobre IA em conteúdo, comunicação e produto. É útil na hora de decidir rótulos, avisos e diretrizes editoriais, e para argumentar internamente que a decisão depende de contexto, não de um padrão único.

---

## 2. Os 3 papéis do contexto para agentes de IA
**Tipo:** Artigo | **Tema:** IA | **Publicado:** 18/09/2026 | **Original:** [The 3 Roles of Context for AI Agents](https://www.nngroup.com/articles/3-agent-context-roles/)

### Sobre o que é
Usuários avançados de IA têm sucesso menos por escreverem prompts sofisticados e mais por curarem três tipos de contexto que moldam como o agente interpreta tarefas e produz resultados.

### Aprofundamento
O contexto global é a informação de base que raramente muda e influencia as ações do agente em todas as interações: diretrizes de marca, boas práticas, regras de governança e preferências do usuário. Vale a pena curá-lo com cuidado, pois vale para tudo.

O contexto local é específico da tarefa em curso: arquivos do projeto, listas de tarefas, dados de pesquisa e histórico da conversa. Costuma ficar em arquivos que o agente pode ler e atualizar.

O contexto ambiente é o fluxo bruto e não curado: e-mails, transcrições de reunião, feeds sociais. Fornece pano de fundo valioso sem ter sido organizado antes. Um participante do estudo resumiu o uso: quer essas informações no momento e depois nunca mais precisará delas.

Um exemplo ilustra o ponto: um participante dirigiu o Claude com o prompt mínimo "Read the MD file and implement it", porque o contexto local já continha detalhe suficiente. Os participantes guardavam global e local em arquivos dedicados, e acessavam o ambiente por conexões de API e MCP.

**Framework: estratégia por papel**
1. Global: curar com cuidado.
2. Local: manter acessível, mas contido na tarefa.
3. Ambiente: conectar a fontes ao vivo.

### Pontos-chave
- Três papéis: global, local, ambiente.
- Prompt eficaz depende mais da arquitetura de contexto que de instruções polidas.
- Global e local ficam em arquivos; ambiente entra via API e MCP.
- Cada papel pede uma estratégia de manejo diferente.

### Como pode ajudar
Ajuda a estruturar como se alimenta um agente de IA com informação, ao montar fluxos de trabalho repetíveis. Apoia decisões sobre o que documentar de forma permanente, o que manter por projeto e o que apenas conectar.

---

## 3. Teste interações complexas mais cedo com prototipagem por IA
**Tipo:** Artigo | **Tema:** Design Process / IA | **Publicado:** 11/09/2026 | **Original:** [Test Complex Interactions Earlier with AI Prototyping](https://www.nngroup.com/articles/test-earlier-with-ai/)

### Sobre o que é
Ferramentas de IA permitem criar protótipos interativos de alta fidelidade rapidamente, o que possibilita testar com usuários antes da implementação pelos desenvolvedores.

### Aprofundamento
A tese é que interfaces complexas revelam problemas só quando são interativas. Telas estáticas escondem falhas de fluxo, estados e casos de borda.

No caso da Ramp, um designer sênior de produto usou o Cursor para prototipar a edição conversacional de políticas de despesa. O protótipo interativo expôs uma falha de usabilidade sobre o rastreamento de edições que não teria sido encontrada com telas estáticas; o trabalho levou três semanas.

Em um estudo da Purdue University sobre filtros de tráfego, pesquisadores compararam wireframes estáticos feitos à mão com protótipos interativos gerados por IA. Os participantes deram feedback bem mais específico e acionável com a versão interativa, apontando casos de borda impossíveis de testar de forma estática.

As ressalvas: o design continua sendo responsabilidade humana, pois a IA executa decisões e não entende hierarquia visual nem conteúdo de forma natural; e há a armadilha da fidelidade, em que o acabamento polido sugere prontidão para produção e pode embutir suposições não examinadas.

**Passo a passo**
1. Definir requisitos do protótipo: quais interações e estados importam para a pesquisa.
2. Tomar decisões de design: layout, hierarquia, interações e casos de borda.
3. Coletar dados: reais (higienizados) ou sintéticos.
4. Escrever prompts detalhados combinando especificação e dados.
5. Usar ferramentas como Cursor, v0 ou Figma Make.
6. Iterar e refinar: espere várias rodadas.

### Pontos-chave
- Protótipo interativo revela falhas que telas estáticas não mostram (caso Ramp, 3 semanas).
- Estudo da Purdue: feedback mais específico com protótipo interativo.
- Seis passos, de requisitos a iteração.
- Cuidado com a armadilha da fidelidade.

### Como pode ajudar
Útil para validar fluxos complexos antes de investir em desenvolvimento, e para decidir quais decisões de design precisam ser tomadas antes de prototipar.

---

## 4. A IA ajuda a escrever um artigo, mas não assume a responsabilidade por ele
**Tipo:** Artigo | **Tema:** IA / Editorial | **Publicado:** 11/09/2026 | **Original:** [AI Can Help Write an Article, but It Can't Stand Behind It](https://www.nngroup.com/articles/ai-editorial-process/)

### Sobre o que é
A NN/G descreve como usa IA no processo editorial mantendo a responsabilidade humana: a IA pode contribuir com palavras e até ideias, mas o julgamento editorial é humano.

### Aprofundamento
Quatro usos são descritos. Clareza e estilo: ferramentas como Copilot e Grammarly ajudam editores a reformular parágrafos de forma concisa, e revisores humanos verificam se a mudança realmente fortalece o argumento.

Conformidade de formato: a IA gera resumos dentro de limites rígidos (160 caracteres) e adapta conteúdo a estruturas exigentes de guias de estudo e glossários.

Adaptação multicanal: a IA ajuda a extrair e reaproveitar conteúdo em cursos, relatórios, vídeos e podcasts, com revisão humana final.

Crítica lógica: a IA aponta possíveis problemas factuais e contradições, levando editores a checar as afirmações nas fontes originais, sem a IA atestar a exatidão.

O que não se delega: avaliar se uma ideia merece ser publicada, se o argumento se sustenta, e endossar pessoalmente o conteúdo antes de associar a reputação da NN/G. O texto lembra que pensar acontece por vários canais, não só escrevendo; logo, a IA no rascunho não implica terceirizar o pensamento.

### Pontos-chave
- Quatro usos: clareza e estilo, formato, multicanal, crítica lógica.
- Resumos de 160 caracteres como exemplo de restrição de formato.
- IA sinaliza problemas; humano verifica nas fontes.
- Julgamento e responsabilidade editorial não são delegáveis.

### Como pode ajudar
Serve de modelo para definir onde a IA entra em processos de produção de conteúdo e onde a decisão precisa ficar com uma pessoa.

---

## 5. Projetando produtos e recursos de IA: guia de estudos
**Tipo:** Artigo (guia de estudos) | **Tema:** IA / Estratégia de produto | **Publicado:** 18/09/2026 | **Original:** [Designing AI Products and Features: Study Guide](https://www.nngroup.com/articles/designing-ai-study-guide/)

### Sobre o que é
Curadoria de recursos da NN/G, por Tanner Kohler, para projetar produtos de IA de forma responsável, com foco em avaliar se a IA de fato agrega valor.

### Aprofundamento
A filosofia rejeita tanto o entusiasmo acrítico quanto o ceticismo generalizado: dar à IA uma chance real, mas apontar quando "o rei está nu".

Seção 1, Estratégia e proposta de valor (12 recursos): "movido por IA" não é proposta de valor; resolva problemas reais em vez de novidade; não adote chat por padrão sem validar com usuários; e considera quatro superpoderes da IA: criação de conteúdo, resumo, análise de dados e tomada de perspectiva.

Seção 2, Assistência de prompt (5 recursos): a "barreira de articulação", em que usuários têm dificuldade de especificar o que querem; recomenda sugestões de prompt relevantes ao contexto e combinar prompts com elementos de GUI.

Seção 3, Recomendações por produto (14 recursos): chatbots, resumos, intranet e agentes; transparência sobre capacidades; ambiguidade do ícone de brilho (✨).

Seção 4, Estado do design de produtos de IA (5 recursos): observações datadas, incluindo alertas de 2021 sobre excesso de investimento antes do ChatGPT. O guia cita ainda podcasts (Henry Modisett, da Perplexity; Paige Lord, do GitHub) e vídeos sobre UI generativa.

### Pontos-chave
- 4 seções, 36 recursos (12 + 5 + 14 + 5).
- Quatro superpoderes: criar conteúdo, resumir, analisar dados, assumir perspectiva.
- Barreira de articulação: sugestões contextuais e GUI ajudam.
- Não usar chat por padrão sem validação.

### Como pode ajudar
Ponto de entrada para quem precisa de um mapa da literatura sobre design de IA; ajuda a decidir por onde estudar e como questionar propostas de recursos de IA.

---

## 6. Mapeamento de empatia: o primeiro passo do design thinking
**Tipo:** Artigo | **Tema:** Design Process | **Publicado:** 14/01/2018 | **Original:** [Empathy Mapping: The First Step in Design Thinking](https://www.nngroup.com/articles/empathy-mapping/)

### Sobre o que é
O mapa de empatia é uma visualização colaborativa que articula o que sabemos sobre um tipo de usuário, externalizando conhecimento para criar entendimento compartilhado.

### Aprofundamento
Os quatro quadrantes: Diz (citações diretas da pesquisa), Pensa (pensamentos internos, inclusive crenças que o usuário hesita em expressar), Faz (ações observáveis) e Sente (estados emocionais: preocupações, empolgação).

Os benefícios: reduz viés com dados, alinha o time em uma visão única, expõe lacunas de pesquisa quando quadrantes ficam vazios, revela necessidades que nem os usuários reconhecem e ajuda a entender o que move o comportamento.

O mapa funciona melhor com dados qualitativos reais, complementa outros métodos e rende mais no início do processo de design.

**Passo a passo**
1. Definir o escopo: um usuário ou um segmento agregado.
2. Reunir materiais: quadro, post-its, marcadores.
3. Coletar pesquisa qualitativa: entrevistas, estudos de campo, diários.
4. Gerar post-its por quadrante.
5. Agrupar notas semelhantes em temas.
6. Refinar e documentar versão e data.

### Pontos-chave
- Quadrantes: Diz, Pensa, Faz, Sente.
- Quadrante vazio = lacuna de pesquisa.
- Precisa de dados qualitativos reais.
- Melhor no início do processo.

### Como pode ajudar
Serve para sintetizar pesquisa e alinhar times antes de definir soluções, especialmente quando há opiniões divergentes sobre o usuário.

---

## 7. Journey Mapping 101
**Tipo:** Artigo | **Tema:** Design Process | **Publicado:** 09/12/2018 | **Original:** [Journey Mapping 101](https://www.nngroup.com/articles/journey-mapping-101/)

### Sobre o que é
Um mapa de jornada visualiza o processo pelo qual uma pessoa passa para atingir um objetivo, combinando ações, pensamentos e emoções em uma narrativa estruturada.

### Aprofundamento
Cinco componentes: ator (uma persona, um ponto de vista por mapa); cenário e expectativas (situação, objetivo e resultado esperado); fases da jornada (estágios como descobrir, experimentar, comprar, usar); ações, mentalidades e emoções plotadas ao longo das fases; e oportunidades (insights acionáveis, com responsáveis).

Artefatos relacionados: mapas de experiência (comportamento humano geral, sem foco no produto); service blueprints (estendem o mapa com processos internos de suporte); e story maps (foco em planejamento de funcionalidades e releases).

O valor está em forçar a conversa e um modelo mental alinhado entre equipes, além de gerar um artefato compartilhado. O processo revela pontos de atrito e de satisfação, permitindo tratar dores de forma sistemática e não em silos.

### Pontos-chave
- 5 componentes: ator, cenário, fases, ações/mentalidades/emoções, oportunidades.
- Um ator por mapa.
- Diferença entre journey map, mapa de experiência, blueprint e story map.
- Alinhamento entre equipes é o principal ganho.

### Como pode ajudar
Útil para enxergar a experiência ponta a ponta, priorizar pontos de atrito e decidir quem é dono de cada melhoria.

---

## 8. 10 heurísticas de usabilidade para design de interfaces
**Tipo:** Artigo | **Tema:** Design de interação | **Publicado:** 24/04/1994 | **Original:** [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/)

### Sobre o que é
Princípios gerais de Jakob Nielsen, desenvolvidos em 1990 e refinados em 1994, que seguem inalterados após 30 anos e se aplicam de apps complexos a realidade virtual.

### Aprofundamento
Os dez princípios, em síntese: manter o usuário informado com feedback em tempo razoável; usar linguagem e convenções do mundo real, sem jargão interno; oferecer saídas de emergência, desfazer e refazer; manter consistência interna e externa (padrões do setor); prevenir erros com restrições e confirmações em vez de só recuperar; privilegiar reconhecimento sobre lembrança; acomodar novatos e experts com atalhos e personalização; manter design estético e minimalista, removendo o irrelevante; dar mensagens de erro claras, em linguagem simples, com solução sugerida; e oferecer ajuda e documentação pesquisáveis, focadas em tarefa e contextuais.

**Lista**
1. Visibilidade do status do sistema.
2. Correspondência entre sistema e mundo real.
3. Controle e liberdade do usuário.
4. Consistência e padrões.
5. Prevenção de erros.
6. Reconhecimento em vez de memorização.
7. Flexibilidade e eficiência de uso.
8. Design estético e minimalista.
9. Ajudar a reconhecer, diagnosticar e corrigir erros.
10. Ajuda e documentação.

### Pontos-chave
- Dez heurísticas estáveis por 30 anos.
- Consistência tem duas faces: interna e externa.
- Prevenir erro vale mais que só tratar erro.
- São princípios gerais, não regras específicas.

### Como pode ajudar
Base para revisar interfaces, justificar decisões de design e dar vocabulário comum a times.

---

## 9. Como conduzir uma avaliação heurística
**Tipo:** Artigo | **Tema:** Métodos / Design Process | **Publicado:** 25/06/2023 (data conforme listagem) | **Original:** [How to Conduct a Heuristic Evaluation](https://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/)

### Sobre o que é
Guia para aplicar as 10 heurísticas de Nielsen como método de identificação de problemas de design em uma interface.

### Aprofundamento
A preparação envolve montar uma equipe de 3 a 5 avaliadores independentes, treiná-los nas heurísticas, praticar com um design simples (como um app de clima), definir onde documentar (PDF interativo, planilha ou whiteboard) e restringir o escopo a uma tarefa, seção, grupo de usuários ou dispositivo.

Na avaliação independente, cada avaliador reserva de 1 a 2 horas, primeiro se familiariza com o produto e depois faz uma segunda passada apontando violações das heurísticas, registrando problemas e recomendações (o artigo exemplifica com a Banana Republic).

Na consolidação, sintetiza-se por diagrama de afinidade, discutem-se concordâncias e discordâncias e priorizam-se problemas pelo impacto nos objetivos de negócio. A ressalva: não substitui pesquisa com usuários reais, e as heurísticas são diretrizes, não leis.

**Passo a passo**
1. Preparar: equipe de 3 a 5, treino, escopo e documentação.
2. Avaliar de forma independente por 1 a 2 horas cada.
3. Consolidar por afinidade e priorizar por impacto.

### Pontos-chave
- 3 a 5 avaliadores independentes.
- 1 a 2 horas por avaliador; duas passadas.
- Priorização por impacto no negócio.
- Não substitui teste com usuários.

### Como pode ajudar
Método rápido e barato para encontrar problemas óbvios antes de testes com usuários e para priorizar o que investigar.

---

## Ver também
- [Democratizing User Research (vídeo)](https://www.nngroup.com/videos/democratizing-user-research/) - Lola Famulegun sobre escalar pesquisa além dos pesquisadores (5 min).
- [Design + Development: 5 Tips for Working Together (vídeo)](https://www.nngroup.com/videos/design-development-5-tips-for-working-together/) - Kelley Gordon sobre colaboração entre design e desenvolvimento (3 min).
- [Using AI for UX Work: Study Guide](https://www.nngroup.com/articles/ai-work-study-guide/) - curadoria sobre uso de IA no trabalho de UX.
- [How AI Works and How Users Think About It: Study Guide](https://www.nngroup.com/articles/ai-functionality-study-guide/) - guia sobre funcionamento da IA e modelos mentais.
- [When to Use Which User-Experience Research Methods](https://www.nngroup.com/articles/which-ux-research-methods/) - clássico para escolher método de pesquisa.
