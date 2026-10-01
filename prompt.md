# Configurador completo de orquestração adaptativa — Codex + Orca + Superpowers + Jev

Configure ou reconcilie meu ambiente para operar com orquestração obrigatória em qualquer interação com o Codex, incluindo perguntas simples, pesquisa, redação, análise, planejamento e desenvolvimento de software.

Este é um pedido para executar a configuração necessária, verificar o resultado e entregar evidências. Deve funcionar tanto numa máquina nova quanto em reexecuções sobre uma instalação existente.

Meu objetivo é melhorar qualidade, velocidade e uso dos recursos disponíveis. O coordenador permanece responsável pelo trabalho; agentes executam conteúdo; Superpowers orienta o método; Jev aconselha decisões delimitadas; controles verificam permissões, vínculos, viabilidade e conclusão.

Não prometa economia de tokens, redução do limite semanal ou aceleração sem medição local.

## 1. Escopo e continuidade

Configure a infraestrutura e as políticas descritas aqui. Não retome automaticamente tarefas antigas nem execute operações com clientes, mensagens, publicações ou alterações de produção alheias à configuração.

Prossiga com ações reversíveis e necessárias já autorizadas. Solicite informação ou aprovação somente quando houver uma dependência real que não possa ser resolvida pelo contexto.

Preserve trabalhos, sessões, credenciais, projetos, journals e correções existentes. Não encerre processos interativos que possam conter trabalho não salvo sem autorização específica.

Não trate este prompt como autorização para contornar restrições do ambiente, consentimentos obrigatórios ou requisitos de confiança de hooks.

## 2. Descoberta do ambiente e contrato vigente

Antes de alterar qualquer coisa, identifique:

- Sistema operacional, shell, usuário e diretórios efetivos.
- Instalações e versões reais do Codex e do Orca.
- Binário, shim, launcher e perfil realmente utilizados.
- CODEX_HOME efetivo de cada superfície relevante.
- Configurações globais, de projeto, perfis e precedência entre elas.
- AGENTS.md aplicáveis e integrações locais já existentes.
- Skills, plugins, ferramentas nativas e mecanismos de delegação disponíveis.
- Instalação, contrato, autenticação e estado operacional do Jev.
- Limites e permissões observados da sessão atual.

Se existir a integração `orchestrator-mode`, leia integralmente seu `roles/GLOBAL-CONTRACT.md`, além dos módulos necessários. Não substitua o contrato completo por um resumo.

Falha de leitura, divergência ou incompatibilidade bloqueia o trabalho que dependa desse contrato. Preserve evidências e informe o impedimento específico.

Reconheça que esta orquestração é uma integração local/customizada. Ela não possui autoridade nativa para modificar instruções superiores, permissões ou capacidades da plataforma.

Descubra caminhos nesta máquina. Não copie nomes de usuário, IDs, hashes, snapshots ou caminhos absolutos de outra instalação.

## 3. Bootstrap de uma máquina nova

Na ausência comprovada da integração, execute um bootstrap mínimo, por meio de executores reais, para instalar ou configurar as dependências necessárias.

Esse bootstrap:

- Existe somente para dependências ausentes.
- Não desativa contratos, trust ou gates que já existam.
- Não transforma o coordenador em implementador.
- Não cria identidades, catálogos ou capacidades fictícias.
- Não afirma ter alterado retroativamente o modelo da sessão atual.
- Termina quando a infraestrutura necessária estiver disponível.

Use mecanismos suportados e fontes oficiais. Se não houver executor ou mecanismo adequado para uma etapa, informe o bloqueio dessa etapa e conclua o trabalho independente permitido.

## 4. Configuração idempotente e preservação

Implemente ou reutilize um configurador com descoberta, estado desejado, reconciliação e verificação.

Se já existir um configurador saudável, amplie-o por migrações compatíveis. Não crie outro motor concorrente para resolver o mesmo problema.

Mantenha:

- Manifesto versionado dos componentes gerenciados.
- Identificação de propriedade dos arquivos e blocos.
- Histórico das migrações.
- Detecção de alterações externas.
- Plano de rollback por camada.
- Resultado NOOP quando o estado já estiver correto.

Faça backup seletivo antes de modificar arquivos existentes. Registre o conteúdo anterior e as mudanças efetivas sem capturar segredos desnecessários.

Use gravações seguras, validação antes da publicação e proteção contra execuções concorrentes quando aplicável.

Não sobrescreva arquivos inteiros para alterar um bloco. Não duplique hooks, skills, wrappers, entradas de perfil ou processos.

Uma reexecução não deve resetar configurações saudáveis, apagar journals, repetir chamadas remotas já consumadas ou recriar tarefas.

Não congele versões, hashes ou contagens de testes históricas como verdades permanentes. Preserve a finalidade e as regressões das correções existentes.

## 5. Orquestração universal

Em cada turno que solicitar conteúdo, o coordenador deve delegar sua produção a pelo menos um executor real.

Isso se aplica a:

- Código e configuração.
- Perguntas simples.
- Pesquisa e explicações.
- Redação, revisão e tradução.
- Planejamento e análise.
- Novos pedidos e complementos em uma conversa existente.

Um executor pode ser reutilizado por uma nova atribuição explícita. A conclusão de um turno anterior não cobre conteúdo novo.

O coordenador pode comunicar andamento, esclarecer necessidades, organizar o trabalho, verificar evidências e sintetizar resultados recebidos.

Não use a obrigação de delegar para criar uma cadeia infinita. Um executor pode executar sua tarefa sem redelegar; nova divisão depende de benefício real.

Mantenha o fluxo proporcional à interação. Uma pergunta simples pode exigir apenas uma delegação curta e uma síntese. Não imponha planejamento extenso, supervisores ou múltiplas revisões a todas as respostas.

## 6. Limites do coordenador

O coordenador planeja, delega, acompanha, verifica e reporta.

Ele não deve:

- Implementar conteúdo ou alterações substanciais.
- Ler código em massa.
- Assumir a execução porque parece mais rápido.
- Fazer por shell, script, MCP, git ou outro mecanismo aquilo que seu papel proíbe diretamente.
- Produzir o trabalho principal e depois criar uma delegação apenas para aparentar conformidade.

Dentro do contrato vigente, pode:

- Ler instruções, contratos, configurações e evidências necessárias à coordenação.
- Executar verificações pertinentes, testes, typecheck e inspeção de diff.
- Usar git, gh, MCP e ferramentas de coordenação dentro do escopo autorizado.
- Manter notas de coordenação nos diretórios próprios permitidos.
- Fazer alterações triviais de configuração, limitadas a três linhas no total da tarefa, quando o contrato permitir.

Dividir uma alteração em várias operações não amplia esse limite.

## 7. Papéis, supervisores e revisão independente

Reconheça papéis pela delegação e pelo estado reais.

- Coordenador raiz: responsável pelo objetivo e pela integração final.
- Supervisor: agente delegado para coordenar um conjunto delimitado de subtarefas.
- Executor: produz conteúdo e executa o trabalho atribuído.
- Revisor independente: verifica sem participação material na solução revisada.
- Responsável por handoff integral: assume o escopo transferido conforme o mecanismo utilizado.

Títulos, mensagens e IDs copiados não criam autoridade.

Crie supervisores somente quando a redução da carga de coordenação, o paralelismo ou a especialização compensarem o custo e os slots ocupados.

Cada supervisor precisa de mandato, entregas, limites, dependências e critério de encerramento. Sua conclusão local não equivale à conclusão global.

Supervisores também respeitam os limites de coordenação. Não são executores disfarçados.

Exija revisão independente em segurança, autenticação, autorização, pagamentos, migrações, exclusão, criptografia e arquitetura importante.

Quem participou materialmente da autoria, implementação ou direção da solução não deve ser apresentado como revisor independente dela.

## 8. Modelos dinâmicos e fonte obrigatória

Não fixe nomes de modelos ou uma tabela permanente de modelos por função.

A fonte obrigatória dos candidatos é esta URL exata:

https://artificialanalysis.ai/models/recommend?intelligence=10&speed=10&cost=10&types=general%2Cagentic%2Ccoding%2Cmath%2Cinstruction-following%2Clong-context%2Cdocument-creation%2Cknowledge%2Clow-hallucination&ultralongcontext=true&reasoning=true&providers=openai&step=results

Em uma nova coordenação independente:

1. Obtenha a captura atual pelo launcher ou shim suportado.
2. Preserve a URL, os rótulos da fonte, os índices disponíveis e a proveniência.
3. Identifique os dez pares modelo/esforço apresentados pela fonte.
4. Escolha o maior índice de inteligência entre TODOS esses pares.
5. Aplique os desempates documentados do resolver.
6. Somente depois verifique disponibilidade e compatibilidade no catálogo real.
7. Configure modelo e esforço nos parâmetros efetivos.
8. Confira o contexto efetivamente aplicado.

Não filtre os candidatos por disponibilidade antes de selecionar o máximo.

Não substitua silenciosamente o vencedor por um segundo colocado, modelo “parecido”, alias presumido ou fallback fixo.

Se o vencedor realmente não puder ser utilizado, interrompa o lançamento dependente e explique a causa. Diferencie indisponibilidade real de falha de normalização, captura ou mapeamento.

Para executores, supervisores e revisores, selecione dinamicamente pares observados e suportados, adequados à tarefa e ao risco. Prefira o menor custo suficiente, considerando evidência de competência e custo total.

Use modelo e esforço explícitos na criação quando o mecanismo permitir. Verifique se perfis de papel, herança ou configurações posteriores substituem esses parâmetros.

Não presuma que preço de API equivale ao consumo do limite semanal da assinatura.

## 9. Normalização e preservação das correções do resolver

Preserve a correção que distingue rótulo da fonte e identificador de execução.

Normalize somente o campo de esforço da fonte para lowercase quando esse for o contrato do resolver, por exemplo `Max` para `max`.

Use a mesma normalização na comparação e na verificação de unicidade semântica.

Não normalize indiscriminadamente:

- URLs.
- Slugs de modelos.
- Identificadores.
- Rótulos preservados como evidência.
- Valores desconhecidos que deveriam causar erro.

Não converta esforço desconhecido em um esforço válido por conveniência.

Teste explicitamente diferenças de caixa, pares duplicados após normalização, dados incompletos e vencedor ausente do catálogo.

Preserve a regra de selecionar o máximo antes de verificar disponibilidade. Corrigir um mapeamento não autoriza alterar essa política.

## 10. Snapshot, identidade, launcher e retomada

Descendentes de uma mesma coordenação reutilizam estas quatro referências reais:

- ORCHESTRATION_SNAPSHOT_PATH
- ORCHESTRATION_SNAPSHOT_ID
- ORCHESTRATION_SNAPSHOT_HASH
- ORCHESTRATION_TASK_ID

Verifique integridade, proveniência e vínculo. Nunca fabrique valores.

Uma nova coordenação independente exige captura atual. Continuação legítima e descendentes reutilizam os vínculos válidos da tarefa; filho, ferramenta ou mensagem de status não exigem nova captura.

Novos processos devem usar o launcher propagador suportado. Workers supervisionados pelo Orca devem usar o adaptador específico previsto pela integração, como `dynamic/orca-worker.ps1` quando existente.

Determine o contexto pai pelos registros canônicos da sessão, home e CODEX_THREAD_ID. Variáveis isoladas ou texto no prompt não são prova suficiente.

Preserve o uso autorizado de:

`--dangerously-bypass-approvals-and-sandbox`

Propague esse modo somente quando sua autorização e presença no contexto efetivo estiverem comprovadas. Ausência de informação não significa bypass. Um contexto restrito não pode ser elevado por inferência.

BYPASS não equivale a confiança de hooks.

Preserve a semântica suportada de `codex resume`. Quando houver vínculo preservado com uma tarefa, reutilize-o corretamente. Não invente Task ID, não vincule uma sessão diferente e não reintroduza exigências obsoletas já corrigidas.

Trate CLI no Orca, Desktop, app-server e lançamentos diretos conforme suas capacidades reais. Um shim de terminal não intercepta universalmente todas essas superfícies.

SnapshotOnly prepara delegação nativa; não autoriza worker externo nem comprova inferência. PrepareOnly também deve ser descrito conforme seu alcance real.

Se uma superfície não suportar a integração, informe a limitação específica sem falsificar compatibilidade ou destruir os caminhos que funcionam.

## 11. Concorrência adaptativa

Não estabeleça um teto artificial permanente de três agentes.

Também não interprete “sem limite fixo” como recursos infinitos ou obrigação de criar muitos agentes.

Determine quantidade, simultaneidade e profundidade a partir de:

- Subtarefas realmente independentes.
- Caminho crítico e dependências.
- Slots efetivamente disponíveis.
- Limites do backend e da conta.
- Recursos locais.
- Contenção de arquivos, navegadores e ferramentas.
- Custo de lançamento, contexto, integração e revisão.

Diferencie:

- Total de agentes criados.
- Agentes ativos simultaneamente.
- Threads abertas.
- Profundidade da hierarquia.
- Capacidade configurada.
- Capacidade observada.

Confira o esquema da versão instalada. Não transplante configurações de outra API.

Quando suportado, `agents.max_concurrent_threads_per_session` controla threads de agentes simultaneamente abertas e exclui a raiz; `agents.max_threads` pode existir como alias legado. Verifique a semântica efetiva antes de editar.

Não confunda essas opções com `max_concurrent_subagents` de outras interfaces.

Não use zero, valores enormes ou chaves inventadas como sinônimo de ilimitado.

Reutilize agentes adequados, use filas e execute em ondas quando necessário. Não burle limites abrindo processos externos indiscriminadamente.

Se observar apenas três agentes simultâneos, investigue a causa. Não conclua automaticamente que há um limite artificial nem prometa superá-lo sem suporte real.

## 12. Delegação, contexto e Orca

Toda atribuição deve conter contexto suficiente e mínimo:

- Objetivo e resultado esperado.
- Escopo e limites.
- Arquivos ou recursos relevantes.
- Dependências.
- Restrições e permissões.
- Modelo/esforço ou configuração efetiva.
- Referências reais da tarefa quando aplicáveis.
- Skills pertinentes.
- Verificações e formato do retorno.

Não presuma herança automática de contexto. Também não copie toda a conversa quando um pacote menor for suficiente.

Distribua tarefas independentes em paralelo. Serialize dependências reais e alterações concorrentes no mesmo recurso.

Use delegação nativa para trabalho interno do Codex.

Para estado, identidade e coordenação supervisionada do Orca, use a skill `orchestration` e o guia compatível com a versão instalada.

Para worktrees, terminais, recursos gerenciados e handoff integral, use `orca-cli` conforme seu contrato.

Não substitua silenciosamente uma operação Orca solicitada por outro mecanismo.

No Orca, exija Task/Dispatch atuais e os vínculos previstos. Processe mensagens antes do ack e confirme o destino do terminal após aceite.

Timeout, ausência de resposta ou falta de evidência não autorizam duplicação de worker, retry, release ou conclusão.

## 13. Superpowers em toda a hierarquia

Use Superpowers oficial:

https://github.com/obra/superpowers

Descubra a instalação real, sua versão e os locais de descoberta. Preserve instalações saudáveis e evite cópias concorrentes.

O coordenador aplica `using-superpowers` e identifica as skills pertinentes ao tipo de interação.

Supervisores, executores e revisores também aplicam as skills pertinentes ao próprio mandato.

Quando houver SUBAGENT-STOP, interprete-o conforme a versão instalada: dispensa de bootstrap não significa dispensa de skills relevantes ou de seus gates.

Não edite skills oficiais para remover exigências. Não crie um selecionador permanente que substitua o mecanismo oficial de descoberta.

Use Superpowers para organizar o método: compreensão, planejamento, execução, depuração, revisão e verificação conforme a tarefa.

Não aplique automaticamente TDD, worktrees ou processos de desenvolvimento a perguntas e redações que não precisam deles.

O agente que conduz o fluxo identifica os pontos em que conselho do Jev pode ajudar. Jev pode aconselhar entre alternativas válidas, mas não decide que uma skill obrigatória deixou de ser obrigatória.

## 14. Base científica e limites da analogia

Registre uma fundamentação curta, separada das instruções carregadas em todo turno.

Considere:

- Kahneman: Thinking, Fast and Slow.
- Tversky e Kahneman: Judgment under Uncertainty: Heuristics and Biases.
- Kahneman: Maps of Bounded Rationality.
- Kahneman e Klein: Conditions for Intuitive Expertise.
- Kahneman e Lovallo: Timid Choices and Bold Forecasts.
- Tversky e Kahneman: The Framing of Decisions and the Psychology of Choice.
- SOFAI: Fast, slow, and metacognitive thinking in AI.
- Fast and Slow Planning.
- System-1.x: Learning to Balance Fast and Slow Planning with Language Models.
- Agents Thinking Fast and Slow: A Talker–Reasoner Architecture.

Diferencie trabalhos originais, versões da mesma pesquisa e estudos independentes.

Use RouteLLM e FrugalGPT como evidência complementar sobre roteamento e custo, sem atribuir ao livro uma influência central não demonstrada.

Registre o material efetivamente consultado. Um excerto do livro não equivale à leitura integral.

Sistemas 1 e 2 são inspiração funcional. Não trate Jev, um modelo maior, esforço alto ou uma cadeia de agentes como equivalentes científicos diretos dos sistemas humanos.

Não assuma que vieses humanos se transferem de forma idêntica ao Jev.

Não importe tolerância experimental a violações, planos parciais ou recompensas negativas para permissões, segurança ou conclusão.

As adaptações propostas aqui precisam de avaliação local. Não anuncie que a configuração reproduz arquiteturas treinadas dos papers.

## 15. Divisão funcional entre ferramentas, Jev e agentes

Separe três funções, sem exigir três agentes ou três chamadas:

1. Verificação e controle determinísticos.
2. Conselho tipado e delimitado do Jev.
3. Produção de conteúdo, investigação e raciocínio aberto por agentes.

Ferramentas e controladores verificam fatos computáveis, contratos, viabilidade, vínculos, permissões e transições.

Jev aconselha escolhas entre alternativas finitas, scores e decisões compatíveis com suas primitivas reais.

Agentes produzem texto, código, planos, pesquisa, interpretações e revisões.

O coordenador mantém a responsabilidade por escolhas discricionárias e pelo resultado final. O controlador não transforma toda escolha em uma decisão determinística.

Não use Jev para escrever conteúdo, gerar código, inventar evidências, justificar uma decisão com texto que a API não produz ou autorizar efeitos externos.

Não peça ao Jev algo que software pode verificar diretamente com maior precisão e menor custo.

## 16. Jev inicial obrigatório e consultas adicionais

Preserve a classificação inicial obrigatória pelo Jev, fora do UserPromptSubmit, conforme o contrato instalado.

Se houver recibo válido do mesmo escopo, reutilize-o conforme as regras existentes.

Antes de conteúdo dependente dessa classificação, o coordenador pode preparar somente o enquadramento operacional, as alternativas iniciais suportadas e o DTO minimizado, usando contexto já observado.

Não crie uma dependência circular exigindo que um executor faça o planejamento substantivo antes da classificação necessária para autorizá-lo.

Depois dessa etapa, executores podem elaborar alternativas substantivas para decisões posteriores.

Use as interfaces reais, incluindo quando existentes:

- `decision.py validate/evaluate` v2.
- `control.py validate/next/reevaluate`.

Não invente comandos, campos ou schemas.

Separe claramente:

- Classificação inicial obrigatória.
- Validações locais sem API.
- Reuso de recibo válido.
- Consultas posteriores opcionais e justificadas.

Uma nova chamada ao Jev deve corresponder a uma decisão permitida que possa mudar a próxima ação. Não consulte por filho, ferramenta, status ou transição de rotina.

Reutilize os componentes instalados de fluxo e supervisão quando adequados. Não crie controladores duplicados.

## 17. Ampliação do papel consultivo do Jev

Configure suporte, conforme o contrato real permitir, para aconselhar:

- Divisão entre alternativas de trabalho.
- Prioridade de subtarefas prontas.
- Paralelismo útil e ordem de execução.
- Distribuição entre executores disponíveis.
- Modelo e esforço dos descendentes.
- Necessidade e escopo de supervisão.
- Prioridade e profundidade de revisão opcional.
- Próxima evidência a obter.
- Encaminhamento de casos novos ou ambíguos.
- Escalonamento.
- Continuidade, redistribuição e encerramento.

Prefira decidir no nível do subproblema relevante. Um pedido pode conter etapas simples e etapas exigentes; um único rótulo para o prompt inteiro não precisa governar toda a execução.

Essa granularidade não significa consulta a cada passo. Agrupe decisões compatíveis quando o contrato permitir e reutilize decisões válidas.

Jev recebe somente alternativas admissíveis e informação suficiente para distingui-las. O controlador confirma que a recomendação continua viável antes da execução.

A recomendação não pode:

- Alterar a regra do modelo máximo da raiz.
- Eliminar delegação obrigatória.
- Remover revisão independente exigida.
- Ampliar permissões.
- Transferir autoridade de outra tarefa.
- Transformar uma falha em sucesso.

## 18. Preparação correta de cada decisão

Para cada decisão material, registre de forma curta:

- Qual ação poderá mudar.
- Quais são as alternativas.
- Quais evidências as diferenciam.
- Quais dados estão ausentes.
- Qual é o custo de um erro.
- Qual verificação será usada.
- Qual é o escopo de validade e reuso.

Evite substituir a pergunta difícil por uma pergunta mais fácil:

- Plausibilidade não equivale a correção.
- Familiaridade não equivale a competência.
- Similaridade não equivale a autorização.
- Relevância de um arquivo não equivale a cobertura.
- Presença de um teste não equivale a teste adequado.
- Confiança não equivale a evidência de conclusão.

Use critérios observáveis e alternativas que representem o problema real.

Trate “nenhuma alternativa adequada” ou incerteza conforme o schema e o consumidor suportados. Use `no_match` somente com a semântica documentada. Não invente `no_judgment` ou saídas que o controlador não entende.

Não reformule sucessivamente a mesma pergunta para obter uma resposta desejada, aumentar artificialmente a confiança ou contornar um journal falho.

## 19. Usos adicionais a avaliar

Avalie estes módulos conforme benefício e suporte:

### Seleção da próxima evidência

Jev pode ordenar buscas, documentos ou verificações candidatas quando há ambiguidade.

O agente decide e coleta a evidência. Dados ausentes continuam ausentes até serem obtidos.

### Fronteiras de competência

Use histórico verificável para identificar classes em que uma rota funciona bem, falha ou ainda é desconhecida.

Novidade, mudança de distribuição ou evidência insuficiente podem justificar revisão ou escalonamento.

### Classes de referência

Use casos comparáveis para estimar esforço, probabilidade de retrabalho e custo total.

Jev pode aconselhar a seleção da classe; cálculos ficam em software. Não transforme poucos exemplos em estatística confiável.

### Revisão por critérios

Separe dimensões como correção, completude, evidência e risco. Jev pode priorizar o que merece investigação.

O parecer final depende das verificações e da revisão exigidas.

### Continuidade orientada por progresso

Avalie se a próxima ação tem chance plausível de resolver uma pendência concreta. Identifique loops e trabalho duplicado.

Não considere esforço já gasto uma justificativa suficiente para continuar.

### Verificação opcional

Jev pode ajudar a escolher verificações adicionais de maior utilidade. As verificações obrigatórias permanecem fixadas pelo contrato e pela tarefa.

Para cada módulo, documente hipótese, integração, dados necessários, métrica e rollback.

Se não existir correspondência fiel no DTO atual, não comprima artificialmente a decisão em campos inadequados. Prepare um adaptador separado, versionado e testado antes de qualquer ativação.

## 20. Tratamento dos sete usos originalmente considerados

### 1. Retenção de contexto

Jev pode aconselhar quais itens explícitos preservar. Um agente produz o resumo.

Mantenha objetivos, restrições, decisões, evidências, pendências, vínculos e falhas relevantes.

Não afirme substituir a compactação nativa sem um ponto de integração real e validado. Não permita apagar informações necessárias à continuidade.

### 2. Documentação e testes de regras

Construa uma relação verificável entre regras, implementação e testes.

Jev pode sinalizar lacunas semânticas; ferramentas conferem existência e execução.

Inclua casos positivos e negativos. Permissões precisam ser verificadas no mecanismo que as aplica, não apenas na interface.

### 3. Seleção de skills

Jev pode aconselhar entre candidatas pertinentes já descobertas.

Preserve descoberta oficial, skills obrigatórias e gates. Não envie todos os arquivos de skills em cada interação.

### 4. Exploração de arquivos

Use primeiro buscas determinísticas, como `rg`.

Jev pode ordenar candidatos minimizados. Executores abrem os arquivos pertinentes e verificam cobertura antes de concluir.

### 5. Primeiro filtro de revisão

Jev pode classificar prioridade e risco de mudanças.

Isso não equivale a aprovação automática, revisão independente ou permissão de merge.

### 6. Testes de navegador

Jev pode selecionar entre ações observadas e permitidas.

O operador valida estado, perfil, destino e autorização. Não invente elementos da interface.

Respeite exclusividade de controle quando necessária e teste permissões reais, incluindo recusas esperadas.

### 7. Verificação de regras antes de editar

Use primeiro regras determinísticas para proibições objetivas.

Avaliação semântica pelo Jev exige ponto de interceptação real, política documentada para falhas e limiar validado por categoria.

Não adote confiança de 80% como regra universal nem use o Jev para liberar uma edição proibida.

Ative somente a cobertura comprovada. Não apresente um hook parcial como proteção de todas as formas de edição.

## 21. Estado atual e comunicação durante a execução

Mantenha um estado local compacto e versionado com:

- Objetivo.
- Responsáveis.
- Dependências.
- Resultados e fontes.
- Momento das observações.
- Pendências.
- Condições de invalidação.

Mensagens operacionais de progresso podem acompanhar a execução.

Uma entrega substantiva só pode usar resultados cujas próprias dependências estejam satisfeitas e atuais. Uma parte independente pode ser entregue sem esperar uma pendência irrelevante.

Não use um resultado antigo como se refletisse o estado atual.

Não crie um agente permanente de conversa apenas para imitar Talker–Reasoner. Jev não é o componente que redige respostas.

Mudanças de objetivo, evidência, recursos ou autorização devem atualizar o estado e seguir as regras de reavaliação aplicáveis.

## 22. Confiança, calibração e aprendizado operacional

Diferencie:

- Score segundo uma rubrica.
- Probabilidade de uma alternativa.
- Confiança retornada pela API.
- Acurácia observada.
- Autorização.
- Evidência de conclusão.

Em Choice e Score, `confidence` não deve ser interpretada automaticamente como probabilidade de a resposta estar correta.

Noul possui semântica própria. Não misture suas probabilidades com scores ou confiança de outras primitivas.

Os limiares locais de conclusão são critérios contratuais, não garantias estatísticas de correção.

Mantenha avaliações por tipo de decisão, domínio, versão de modelo, prompt, rubrica e integração.

Considere quantidade e representatividade das observações. Sem dados adequados, registre UNKNOWN.

Registre sucessos, falhas, falsos positivos, falsos negativos, timeouts e retrabalho.

Feedback pode melhorar rubricas e políticas versionadas. Isso não significa treinamento automático dos pesos do Jev.

Não reduza gates existentes para acomodar um resultado de baixa confiança.

## 23. Custo total, reflexão e valor da informação

Meça custo e latência de ponta a ponta, incluindo:

- Preparação e minimização.
- Consultas ao Jev.
- Lançamento de agentes.
- Contexto transmitido.
- Esperas.
- Execução.
- Verificação.
- Revisão.
- Integração.
- Retrabalho.

Não conclua que o fluxo melhorou porque uma chamada isolada ficou mais rápida.

Quando houver dados suficientes, compare o valor esperado de informação adicional com seu custo. Sem dados, registre hipóteses e incerteza.

Não presuma que mais raciocínio, debate, supervisores ou ciclos de autocorreção melhoram o resultado.

Raciocínio preliminar pode ser necessário para escolher uma verificação. Antes de aceitar a conclusão, exija evidência externa pertinente: testes, fontes, cálculos, documentos ou observação real, conforme a tarefa.

Evite repetir autorreflexão sem nova evidência ou hipótese útil.

Revise decisões passadas em lotes autorizados quando isso puder melhorar a política. Não crie chamadas extras ou automações de aprendizado contínuo sem necessidade e autorização.

Retire trabalho opcional quando não houver benefício demonstrável. Preserve todas as obrigações do contrato.

## 24. Privacidade, recibos e falhas

Siga o contrato instalado do Jev e sua política de minimização.

Use DTO genérico, minimizado e atestado quando exigido.

Não envie ao Jev:

- Credenciais.
- Identificadores pessoais ou de clientes.
- Documentos brutos.
- Conteúdo confidencial desnecessário.
- Paths, hashes, IDs de tarefas e outros vínculos que devem permanecer locais.

Preserve a semântica necessária à decisão. Se a minimização impedir uma avaliação válida, não fabrique evidência nem envie o material proibido.

Mantenha autenticação no mecanismo seguro previsto, como a variável apropriada quando exigida. Nunca imprima, copie para prompts ou comite a chave.

Reuso de recibo exige escopo e proveniência válidos. Semelhança com outro caso não transfere aprovação ou autoridade.

Mudança material precisa de proveniência e do procedimento documentado.

Journal falho, incerto ou tentativa parcialmente consumada bloqueia retry ou troca de task, schema e evento usada como contorno.

Não converta fixture, replay, migração ou reavaliação local em uma nova tentativa de API disfarçada.

Recuperação manual deve seguir o procedimento e a autorização específica exigidos.

Não migre registros apagando os originais nem marque falhas antigas como sucesso.

## 25. Persistência, hooks e carregamento econômico

Mantenha um núcleo global curto no AGENTS.md, apontando para o contrato completo e módulos apropriados.

Preserve a leitura integral exigida pelo contrato. Não injete este prompt de instalação, os papers e todo o histórico em cada turno.

Configure UserPromptSubmit, quando suportado, somente como lembrete estrutural.

O hook não deve:

- Navegar na web.
- Consultar o Jev.
- Criar agentes.
- Resolver modelos.
- Inventar snapshots.
- Classificar conteúdo por conta própria.
- Armazenar prompts desnecessariamente.

Use configuração e saída compatíveis com a versão instalada.

Diferencie:

1. Hook instalado.
2. Hook confiável.
3. Hook executado na sessão relevante.

Não modifique bases internas de trust nem trate bypass como consentimento de hooks.

Verifique cada CODEX_HOME efetivo. Configuração em um home não prova cobertura de outro.

Preserve Stop/Jev, identidade, aprovação exata, canais, checkpoints e regras de Humanizer ou entrega já existentes.

Mapeie a cobertura real de eventos e ferramentas. Não afirme interceptar caminhos que não foram verificados.

## 26. Pilotos e verificação da configuração

Comece medindo decisões já suportadas de distribuição, prioridade, revisão e continuidade.

Introduza novos módulos separadamente, inicialmente em shadow: registram propostas para comparação, sem produzir efeitos operacionais.

Para cada piloto:

- Defina hipótese e critérios de promoção e retirada.
- Preserve os mesmos gates no baseline.
- Separe desenvolvimento, histórico de roteamento e avaliação reservada.
- Evite vazamento dos casos de avaliação.
- Inclua casos comuns, ambíguos, novos e falhas relevantes.
- Compare tarefas equivalentes.
- Registre versões e configuração.
- Meça qualidade, severidade dos erros, custo, latência e retrabalho.
- Informe incerteza.
- Faça ablação apenas de componentes opcionais.
- Tenha rollback por módulo.

Não ative todos os experimentos somente porque aparecem na literatura.

Execute verificações adequadas para:

- Instalação inicial.
- Reexecução idempotente e NOOP.
- Backup, migração e rollback.
- Conflitos de configuração.
- Propagação de permissões e identidade.
- Modelo/esforço efetivos.
- Snapshot e vínculos.
- Retomada de sessões.
- Delegação nativa.
- Task/Dispatch e execução Orca quando disponíveis.
- Jev, reuso e falhas, sem consumir retries proibidos.
- Hook instalado, trust e execução.
- Delegação de pedidos com e sem código.

No resolver, inclua regressões para:

- Esforço com diferença de caixa.
- Duplicidade após normalização.
- Valor desconhecido.
- Captura incompleta.
- URL divergente.
- Vencedor ausente.
- Seleção do máximo antes da disponibilidade.
- Proibição de substituição silenciosa.

Verifique concorrência usando trabalho útil e capacidade realmente disponível. Não crie agentes descartáveis apenas para ultrapassar três.

Depois de checks adequados passarem, repita ou amplie testes somente por nova mudança, falha ou dúvida material.

## 27. Conclusão e entrega

Preserve os critérios atuais de COMPLETE.

Quando exigidos pelo contrato vigente, COMPLETE depende cumulativamente de:

- Objetivo implementado ou entrega integral atendida.
- Verificações pertinentes atuais.
- Revisão exigida concluída.
- Evidências vinculadas ao estado atual.
- Ausência de falhas impeditivas.
- Confiança de pelo menos 0,5.
- Residual de no máximo 0,25.
- Progress e residual na continuidade final.
- Agregação de confiança conforme o controlador, incluindo o mínimo aplicável às respostas Choice/Score solicitadas.

Esses critérios não podem ser relaxados porque um paper aceita soluções parciais.

Falha, timeout, resposta inválida ou ausência de evidência não vira conclusão.

Separe explicitamente:

- Instalado.
- Configurado.
- Confiável.
- Testado.
- Observado em execução.
- Benefício medido.

Um NOOP administrativo, uma fixture, um catálogo, SnapshotOnly, PrepareOnly ou uma suíte verde não prova funcionamento completo no ambiente real.

Ao finalizar, entregue:

1. Resumo do estado encontrado.
2. Alterações realizadas e componentes preservados.
3. Arquivos e blocos gerenciados.
4. Manifesto, backups e rollback.
5. Verificações executadas e resultados.
6. Evidências de delegação e execução real, quando disponíveis.
7. Capacidade configurada e concorrência observada.
8. Política dinâmica de modelos e seus limites.
9. Integrações Jev ativas, propostas e em shadow.
10. Benefícios medidos, com UNKNOWN onde faltarem dados.
11. Necessidade real de reiniciar ou abrir nova sessão.
12. Pendências e bloqueios específicos.

Não diga “tudo configurado e funcionando” se parte disso não foi demonstrada.

Mantenha o relatório final direto. A complexidade da configuração deve ficar nos artefatos verificáveis e no contrato, sem ser repetida em toda interação futura.
