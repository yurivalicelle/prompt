# Configurador completo: Codex + Orca + Superpowers + Jev

Configure este ambiente para usar o Codex dentro do Orca com orquestração em todas as interações, delegação real, modelos escolhidos dinamicamente, Superpowers em toda a hierarquia e Jev integrado às decisões de coordenação.

Este prompt é um configurador inicial e um reconciliador idempotente: deve funcionar numa máquina nova e quando executado novamente sobre instalações anteriores.

Execute a configuração necessária dentro das permissões reais da sessão. Use executores para implementação. Preserve configurações saudáveis, correções já aplicadas, personalizações, credenciais, histórico e trabalho em andamento.

Prioridades:
1. Cumprir o pedido corretamente, respeitando privacidade, permissões e evidências.
2. Reduzir custo total, latência e retrabalho.
3. Usar paralelismo e modelos menores quando forem suficientes.
4. Manter a configuração compreensível, verificável e reversível.

Não confunda instalado, configurado, confiado, autenticado, testado, operacional e benefício medido.

## 1. Escopo e resultado esperado

Configure:

- Política persistente de orquestração para qualquer interação, com ou sem código.
- Integração apropriada com as skills do Orca.
- Superpowers oficial para coordenadores, supervisores, executores e revisores.
- Seleção dinâmica de modelos a partir da fonte autorizada.
- Snapshot compartilhado e imutável por tarefa.
- Jev para aconselhamento de distribuição, decomposição, paralelismo, prioridade, revisão, escalonamento e continuidade.
- Concorrência adaptativa, sem tamanho fixo de equipe.
- Hooks compatíveis e mínimos.
- Verificação, medição, documentação, backups e rollback seletivo.

Este pedido autoriza o trabalho de configuração pertinente. Não autoriza retomar tarefas antigas, reenviar mensagens, executar operações de clientes ou reproduzir efeitos externos para demonstrar funcionamento.

Não peça novamente autorização para ações já autorizadas. Quando faltar uma autorização real, prepare primeiro o resultado revisável e peça somente o necessário, explicando a origem da exigência.

## 2. Descoberta do ambiente

Antes de alterar arquivos, identifique:

- Sistema operacional, arquitetura e shell.
- Diretório atual, home do usuário e CODEX_HOME efetivo.
- Executáveis e versões reais de Codex e Orca.
- Uso por terminal do Orca, CLI independente, Desktop ou app-server.
- Configurações globais, de projeto, perfis, argumentos e overrides.
- Mecanismos de delegação e parâmetros realmente disponíveis.
- Skills, plugins, hooks e componentes de orquestração existentes.
- Runtimes e dependências necessárias.
- Sessões ou workers ativos que possam ser afetados.

Descubra caminhos; não fixe nome de usuário, unidade, diretório de cache ou versão.

Se houver várias homes, confira cada uma separadamente quando estiver no escopo. Não presuma que a home encontrada é a utilizada pela sessão ativa.

Não copie credenciais, sessões, bancos de confiança ou aprovações entre homes. Inspecione apenas os campos necessários, sem expor segredos.

## 3. Bootstrap numa máquina nova

Componentes ausentes são alvos da configuração. Não exija que um README, resolver, snapshot ou serviço personalizado já exista para permitir sua própria instalação.

Esta exceção de bootstrap vale somente para dependências comprovadamente ausentes. Ela não suspende instruções superiores, permissões ou gates já vigentes na sessão.

Durante o bootstrap:

- Use delegação real disponível.
- Descubra modelos e parâmetros aceitos pelo mecanismo atual.
- Delegue instalação, implementação e documentação.
- Registre quais garantias ainda dependem da configuração.
- Trate os requisitos da arquitetura final como critérios de ativação.

Não classifique um componente existente e defeituoso como “ausente” para contornar suas regras.

Se faltar mecanismo de execução adequado, prepare o que for permitido, preserve evidências e informe a dependência. O coordenador não assume implementação por falta de executor.

Não afirme que configurar um launcher alterou retroativamente o modelo ou as permissões da sessão atual.

## 4. Fontes, compatibilidade e instalação

Use documentação oficial e os guias correspondentes às versões instaladas.

Fontes principais:

- Codex: documentação oficial OpenAI.
- Orca: executável real e guias versionados das skills orchestration e orca-cli.
- Superpowers: https://github.com/obra/superpowers
- Jev/TypeSafe: documentação oficial e contrato local instalado.
- Modelos: URL Artificial Analysis definida neste prompt.

Não invente comandos, parâmetros, repositórios, endpoints ou suporte de ferramentas.

Reutilize módulos compatíveis existentes. Se uma integração personalizada estiver ausente, delegue sua implementação com contrato, documentação e testes. Identifique-a como integração local, sem apresentá-la como recurso nativo do produto.

Atualize dependências quando necessário à compatibilidade; não reinstale tudo nem atualize componentes saudáveis indiscriminadamente.

## 5. Estado desejado e idempotência

Mantenha estado desejado versionado e manifestos contendo:

- Componentes e origem.
- Versões e compatibilidade.
- Caminhos descobertos.
- Ownership de arquivos e blocos.
- Dependências.
- Hashes anteriores e posteriores.
- Migrações aplicadas.
- Backups e rollback.
- Critérios de aceitação.
- Resultado das verificações.

Separe esse estado administrativo dos schemas de snapshot, Jev, hooks e runtime.

Classifique o estado observado como ausente, compatível, desatualizado, personalizado, divergente, parcialmente instalado ou bloqueado.

Reexecução deve:

- Resultar em no-op quando o estado já estiver correto.
- Alterar somente diferenças necessárias.
- Preservar conteúdo fora dos blocos gerenciados.
- Evitar duplicação de hooks, políticas, perfis, agentes e motores.
- Preservar correções locais válidas.
- Não redefinir autenticação, confiança ou permissões.
- Não apagar snapshots, recibos, journals ou histórico.
- Não repetir chamadas externas já concluídas.

Uma configuração administrativamente idempotente ainda pode gerar uma nova captura quando uma nova coordenação independente exigir isso.

## 6. Preservação de correções e rollback

Não restaure arquivos inteiros a partir de templates antigos sem verificar diferenças e correções posteriores.

Use comparação de comportamento, ownership, versão, proveniência e testes. Hash diferente não significa automaticamente corrupção.

Faça backup seletivo antes de alterações. Publique mudanças de forma atômica quando possível e registre transações interrompidas.

Use exclusão mútua adequada em arquivos compartilhados. Lock residual exige investigação; não o apague automaticamente.

Prepare rollback por camada:

- Restaurar somente os itens daquela mudança.
- Conferir hashes atuais e dos backups.
- Recusar sobrescrever alterações posteriores não reconciliadas.
- Preservar evidências, recibos, journals e sessões.

Não congele hashes antigos como requisito universal. Preserve a propriedade funcional da correção, permitindo evolução compatível e revisada.

## 7. Política universal de orquestração

Instale uma política persistente aplicável em qualquer diretório e também em sessões sem sandbox e sem aprovações de comandos.

A política abrange perguntas simples, fatos, explicações, pesquisa, análise, comparação, recomendações, escrita, revisão, tradução, resumos, planejamento, organização, diagnóstico e código.

Em cada turno com solicitação de conteúdo:

1. O coordenador entende o pedido e define o encaminhamento.
2. Delega trabalho real a pelo menos um executor.
3. Acompanha e verifica o resultado.
4. Sintetiza e responde ao usuário.

Pode reutilizar executor por follow-up real. Uma conclusão anterior não cobre um pedido novo.

Para interações pequenas, use uma delegação pequena e contexto mínimo. Não crie planejamento extenso, supervisores ou revisões redundantes por padrão.

Comunicação estritamente operacional, acompanhamento e esclarecimentos necessários à delegação não exigem criar outro agente.

Não use “é simples”, “é mais rápido”, “não envolve código” ou “já tenho contexto” como justificativa para o coordenador produzir sozinho o conteúdo solicitado.

## 8. Papéis e limites

### Coordenador raiz

É a raiz única da tarefa. Planeja, delega, acompanha, verifica, integra e reporta.

Pode executar diretamente:

- Comunicação operacional e esclarecimentos.
- Leitura de instruções e configurações necessárias à coordenação.
- Inspeção de evidências.
- Testes, lint, typecheck e git diff.
- Notas e temporários autorizados em .codex/tmp/ e .codex/memory/.
- Configuração de até três linhas no total por tarefa.
- Git, gh, MCP e Orca CLI para coordenação, inspeção e operações autorizadas.

Não implementa código nem lê código em massa. Não contorna esses limites usando shell, scripts, redirecionamentos, MCP ou fragmentação de alterações.

### Supervisor

Coordena uma frente realmente delegada e vinculada à mesma tarefa e snapshot.

Seu mandato contém objetivo, entregáveis, recursos, decisões locais, limites, dependências, critérios de encerramento/escalonamento, benefício e custo.

Mantém os limites do coordenador e delega conteúdo. Não cria nova raiz, não recaptura modelos por conta própria e não aprova conclusão global.

Crie supervisores somente quando reduzirem carga de coordenação ou melhorarem o resultado. Preserve capacidade para executores úteis.

### Executor

É um subagente nativo realmente delegado ou worker Orca com Task/Dispatch válidos.

Executa o escopo recebido e pode criar descendentes úteis. Não redelega apenas para cumprir formalidade nem cria recursão sem trabalho.

### Revisor independente

Não participou materialmente da autoria, direção ou implementação do trabalho revisado.

É obrigatório para segurança, autenticação, autorização, pagamentos, migração, exclusão, criptografia e arquitetura importante. Nos demais casos, a revisão acompanha risco e método.

Título ou autoatestação não provam independência.

### Handoff

Transfere responsabilidade conforme o pedido e o protocolo. Handoff integral não cria supervisão automática.

## 9. Modelos dinâmicos

Use exclusivamente esta URL para a lista de candidatos:

https://artificialanalysis.ai/models/recommend?intelligence=10&speed=10&cost=10&types=general%2Cagentic%2Ccoding%2Cmath%2Cinstruction-following%2Clong-context%2Cdocument-creation%2Cknowledge%2Clow-hallucination&ultralongcontext=true&reasoning=true&providers=openai&step=results

Não altere os parâmetros. Registre fonte, data, valores observados e eventual divergência entre URL e interface.

Exija dez pares modelo/esforço distintos, com métricas válidas. Não complete resultados ausentes com modelos lembrados ou capturas antigas.

Para o coordenador raiz:

1. Compare o índice de inteligência entre todos os dez pares da fonte.
2. Escolha o maior.
3. Em empate, use menor Index Cost comparável, maior velocidade e posição na fonte.
4. Somente depois valide o vencedor no catálogo real do runtime.
5. Se estiver realmente indisponível, bloqueie o lançamento.

Não filtre por disponibilidade antes de escolher o máximo. Não substitua o vencedor por segundo colocado ou fallback silencioso.

Para executores, supervisores e revisores:

- Escolha pares observados na captura e suportados no mecanismo.
- Considere capacidade, dificuldade, contexto, ferramentas, risco, custo e latência.
- Use o menor custo suficiente para cumprir o escopo.
- Escalone por evidências de insuficiência, não pela existência de um modelo mais forte.
- Não mantenha tabela permanente de nomes por tipo de tarefa.

Configure modelo e esforço nos parâmetros reais de lançamento.

Confira se perfis, arquivos de papéis ou overrides substituem a seleção. Não permita que um modelo fixo nesses arquivos anule silenciosamente o roteamento dinâmico.

Catálogo, parâmetros solicitados e modelo efetivo são evidências distintas.

## 10. Correção obrigatória de capitalização do esforço

Preserve a correção do falso WINNER_UNAVAILABLE causado por diferenças como `Max` na fonte e `max` no catálogo.

O comportamento exigido é:

- Preservar o rótulo original da fonte como evidência.
- Normalizar somente o campo de esforço da fonte para minúsculas antes da comparação.
- Validar o resultado contra os esforços realmente suportados.
- Usar o mesmo normalizador na verificação de unicidade dos pares.

Variantes como `Max` e `MAX` do mesmo modelo representam o mesmo par e não podem contar como candidatos distintos.

Não aplique lowercase indiscriminadamente a identificadores de modelos, URLs ou outros campos. Não use normalização para aceitar esforços desconhecidos ou mapear modelos por semelhança.

Diferencie:

- Divergência de capitalização resolvível.
- Mapeamento ausente ou ambíguo.
- Esforço desconhecido.
- Esforço não suportado.
- Vencedor ausente ou oculto.
- Indisponibilidade remota posterior.

A correção não elimina bloqueios legítimos nem autoriza fallback.

Em reexecuções, preserve esse comportamento e seus testes. Não reinstale uma versão antiga do resolver que reintroduza a comparação literal defeituosa.

Modelo vencedor, hash, versão e quantidade de testes de uma correção anterior são evidência histórica; não são defaults permanentes.

## 11. Snapshot e lançamento

Em nova coordenação independente, obtenha captura atual antes do lançamento pela rota suportada.

Todos os descendentes da mesma tarefa recebem:

- ORCHESTRATION_SNAPSHOT_PATH
- ORCHESTRATION_SNAPSHOT_ID
- ORCHESTRATION_SNAPSHOT_HASH
- ORCHESTRATION_TASK_ID

Use identificadores reais e SHA256 dos bytes exatos do snapshot. Não invente vínculos.

O snapshot permanece imutável durante a tarefa. Descendentes e follow-ups não repetem a pesquisa da fonte sem necessidade de uma nova coordenação independente.

Quando a ferramenta nativa não aceitar variáveis de ambiente, transmita explicitamente as quatro referências no contexto mínimo e confira o vínculo.

Use modelo e esforço explícitos por parâmetros suportados. Quando overrides exigirem contexto isolado ou recortado, use essa modalidade.

Confirme lançamento e contexto efetivo. Texto na mensagem, herança presumida ou sucesso do wrapper não provam o modelo utilizado.

Não tente trocar retroativamente o modelo de uma sessão aberta. Prepare o lançamento correto para a próxima sessão aplicável e informe essa limitação.

## 12. Permissões, resume e Desktop

Preserve o modo parental efetivamente observado.

Quando o usuário iniciar legitimamente com:

`--dangerously-bypass-approvals-and-sandbox`

a rota propagadora deve conservar esse modo quando suportado e autorizado.

Isso não autoriza:

- Instalar bypass como padrão global.
- Elevar um pai restrito.
- Ignorar confiança de hooks.
- Remover gates de negócio.
- Inventar autoridade Task/Dispatch.
- Contornar restrições superiores.

Confira identidade canônica, CODEX_HOME e último contexto parental. Ausência, ambiguidade ou conflito não permitem presumir bypass.

Diferencie:

- Resume independente: valida a sessão exata e prepara nova coordenação/captura.
- Continuação explícita da mesma tarefa: preserva tarefa, snapshot e hash.
- SnapshotOnly: prepara referências para delegação nativa.
- PrepareOnly: prepara um lançamento externo estrito.

Resume normal não deve exigir TaskId manual apenas por uma regra obsoleta do wrapper. Preserve validações de identidade e use o contrato atual.

SnapshotOnly não inicia processo, não prova inferência, não muda permissões e não autoriza worker externo. Perfil Desktop não reproduzível pela CLI continua bloqueando o lançamento externo, sem impedir preparação nativa suportada.

Não duplique sessões ativas nem encerre terminais com trabalho sem autorização pertinente.

## 13. Concorrência e profundidade adaptativas

Não fixe a equipe em três agentes nem estabeleça teto artificial permanente para total de agentes ou profundidade.

Dimensione o trabalho por:

- Unidades independentes.
- Caminho crítico.
- Dependências.
- Disputas por arquivos e recursos.
- Necessidade de revisão.
- Benefício esperado.
- Custo de contexto e coordenação.
- Capacidade técnica observada.

Diferencie:

- Agentes criados ao longo da tarefa.
- Threads abertas simultaneamente.
- Agentes executando.
- Agentes aguardando ou concluídos.
- Profundidade.
- Slots livres efetivos.

Ver apenas três agentes simultâneos não prova um limite universal.

Descubra limites no runtime, host, perfil, configuração de projeto e argumentos efetivos.

Valide na versão instalada os parâmetros de concorrência. A documentação atual apresenta `agents.max_concurrent_threads_per_session` e o alias legado `agents.max_threads`. Não transplante `max_concurrent_subagents` da Agents API para o arquivo de configuração da CLI.

Se um limite configurável impedir trabalho útil, ajuste-o com justificativa, suporte comprovado e verificação posterior. Não use zero, negativos, números arbitrariamente enormes ou “unlimited” sem semântica documentada.

Uma capacidade técnica finita não é uma equipe de tamanho fixo.

Quando faltar capacidade, use fila, ondas e reaproveitamento. Supervisores também consomem slots; evite ocupar toda a capacidade com gestores.

Não crie agentes sem trabalho apenas para demonstrar quantidade. Não contorne limites usando outro mecanismo ou duplicando executores.

## 14. Contrato de delegação e Orca

Cada delegação deve conter:

- Objetivo e resultado esperado.
- Papel real.
- Contexto mínimo suficiente.
- Decisões e restrições relevantes.
- Dependências e recursos compartilhados.
- Diretório e arquivos sob responsabilidade, quando houver.
- Snapshot e tarefa.
- Skills e suas localizações.
- Critérios de aceitação.
- Verificações pertinentes.
- Formato do retorno.

Exija resumo, alterações, verificações executadas, resultados, riscos, limitações e pendências.

Paralelize partes independentes. Serialize dependências, edições conflitantes e recursos exclusivos. Prefira follow-up para correções do mesmo trabalho.

Use:

- Subagentes nativos para subtarefas internas sem dependência da identidade ou estado do Orca.
- Skill orchestration para coordenação supervisionada de Task/Dispatch, DAGs, perguntas, decisões e resultados.
- Skill orca-cli para recursos gerenciados pelo Orca e handoffs integrais.

Não substitua silenciosamente uma execução solicitada no Orca por execução nativa.

No Orca, confira identificadores reais, mensagens pendentes, reconhecimentos e resultados. Timeout, aceitação de dispatch ou terminal aberto não provam início ou conclusão do trabalho.

Após encerramento aceito, dê ao terminal o destino previsto: reutilização, retenção solicitada ou liberação.

## 15. Superpowers em toda a hierarquia

Use Superpowers oficial:

https://github.com/obra/superpowers

Descubra versão e caminho instalados. Instale ou reconcilie por mecanismo confiável quando necessário.

O coordenador aplica using-superpowers e as skills pertinentes. Supervisores, executores e revisores também aplicam as skills pertinentes ao próprio escopo.

A exceção SUBAGENT-STOP dispensa somente o bootstrap correspondente; não dispensa as demais skills aplicáveis.

Transmita localização, versão observada, referências e restrições aos descendentes.

Use o processo orientado por Superpowers para identificar:

- Qual fluxo atende à interação.
- O que é determinístico.
- Onde existe uma escolha útil para Jev.
- Qual trabalho pode ser paralelo.
- Qual revisão é necessária.
- Quando continuar ou escalar.

Superpowers fornece instruções; o agente continua responsável pelo método. Não crie um supervisor permanente apenas para selecionar skills.

Respeite gates pertinentes e as instruções do usuário. Não altere skills oficiais para suprimir exigências.

Não carregue todas as skills por padrão nem imponha testes de software a texto e pesquisa.

## 16. Jev como aconselhamento de coordenação

Jev deve participar das decisões que podem melhorar o resultado, preservando o controle do orquestrador.

A classificação inicial de cada tarefa substantiva é obrigatória conforme o contrato vigente, antes da execução de conteúdo. Durante bootstrap, aplique a exceção limitada a componentes ausentes descrita anteriormente.

O coordenador prepara alternativas e restrições mínimas. Planejamento aprofundado, pesquisa e implementação continuam delegados.

Use Jev para aconselhar, quando houver escolha real:

- Decomposição do trabalho.
- Agrupamento de unidades.
- Distribuição de modelos e esforços.
- Paralelismo viável.
- Prioridade e ordem.
- Necessidade e distribuição de revisão.
- Uso de supervisores.
- Continuidade, redistribuição ou escalonamento.

Não consulte Jev para confirmar uma ação já determinada por regras ou evidências.

Reutilize o contrato instalado. Para novos aconselhamentos compatíveis, use v2 com grupos e dimensões pertinentes. Não confunda versão do DTO com versão do snapshot.

Fluxo:

1. Preparar DTO genérico minimizado e alternativas finitas.
2. Executar a validação local.
3. Reutilizar recibo válido ou avaliar quando realmente permitido e necessário.
4. Validar o recibo.
5. Conferir viabilidade no controlador.
6. Executar a decisão permitida.
7. Reavaliar somente diante de mudança material comprovada.

Use os entrypoints reais de decision.py validate/evaluate e control.py validate/next/reevaluate quando existentes e compatíveis.

Jev aconselha. O controlador confere modelos, esforços, contexto, ferramentas, permissões, dependências, conflitos e slots atuais.

Jev não concede autorização, não lança agentes e não substitui verificações determinísticas.

## 17. Reuso, privacidade e falhas de Jev

Raiz, supervisores e executores identificam pontos úteis de Jev dentro de seus escopos.

Compartilhe decisões válidas quando o contrato permitir. Não faça uma chamada por filho, ferramenta, status, edição ou transição determinística.

Pergunte somente dimensões que possam alterar a próxima decisão. Opção fixada pelo método é restrição local, sem confiança inventada.

Não repita alternativas no body. Respeite Choice, Score e Noul conforme seus contratos. Probabilidade Noul não é um campo separado de confidence.

Envie somente estado genérico minimizado e revisado. Não envie conteúdo bruto, dados de clientes, documentos, credenciais, caminhos ou identificadores internos. IDs, hashes e proveniência ficam locais fora do body quando assim exigir o contrato.

Filtros automáticos não comprovam anonimização.

Preserve journals falhos ou incertos. Não faça retry automático, troque task/schema/evento, remova histórico ou crie outro escopo para escapar de uma falha.

Mudança material exige campos alterados e proveniência verificável. Migração v1→v2 exige originais conferidos; não converta recibos.

Recuperação manual exige protocolo próprio e autorização humana específica. Este configurador não autoriza recuperar chamadas históricas.

Reutilize flow.py, supervision_v2.py e outros componentes compatíveis em vez de criar motores duplicados.

## 18. Sete otimizações opcionais

Avalie e implemente os módulos úteis por executores, conforme contrato e suporte reais. Comece em shadow quando a qualidade ainda não estiver demonstrada.

Cada módulo precisa de entrada, saída, privacidade, falhas, fallback, testes e medição.

### 18.1 Sugestão de skills

Jev pode selecionar entre descrições mínimas de skills pertinentes. O agente lê e aplica as selecionadas, preservando skills obrigatórias e explicitamente solicitadas.

Não afirme redução de contexto se o catálogo continuar injetado pelo runtime.

### 18.2 Priorização de arquivos

Faça descoberta determinística com rg/rg --files. Jev pode ordenar candidatos usando metadados mínimos e aliases.

Ranking não comprova irrelevância dos demais arquivos nem substitui cobertura necessária.

### 18.3 Pré-triagem de revisão

Use perguntas binárias pertinentes às regras e riscos do projeto. Um roteiro de sete perguntas pode ser usado quando justificado, sem transformar essa quantidade em regra universal.

Triagem direciona revisão; não aprova automaticamente código, segurança ou conclusão.

### 18.4 Regras de acesso e testes

Mantenha matriz entre ator, recurso, ação, regra e resultado esperado.

Confirme testes positivos e negativos, execução e autorização no backend. Existência de um arquivo de teste não comprova cobertura.

Jev pode apontar ambiguidades e prioridades quando o contrato suportar.

### 18.5 Retenção de contexto e compactação

Jev pode ajudar a selecionar itens a preservar. Um executor redige o resumo.

Preserve objetivos, restrições, autorizações relevantes, decisões, pendências e referências de evidência.

Não substitua o compressor interno sem API suportada e integração demonstrada. Checkpoint não equivale a substituição da compactação.

### 18.6 Testes de navegador

Jev pode escolher entre ações observadas e permitidas numa sessão de teste.

Use perfis realmente autenticados, recursos isolados e validação de backend. Simular um perfil por texto não cria permissões.

O controlador valida identidade, ação e escopo antes da execução.

### 18.7 Fiscalização de regras antes de alterações

Use checks determinísticos para regras objetivas e Jev somente em ambiguidades pertinentes.

Não adote “80%” como limiar universal calibrado. Não transforme um score em autorização ou garantia de segurança.

Verifique quais ferramentas e rotas são realmente interceptadas. Um hook não cobre automaticamente toda forma de alteração.

Falha de otimização opcional permite o fluxo normal autorizado. Falha de gate obrigatório não pode virar aprovação.

Não trate demonstrações de vídeo, tempos anunciados ou resultados de outra ferramenta como prova de desempenho neste ambiente.

## 19. Persistência e hooks

Instale a política no mecanismo global suportado e confira precedência, overrides de projeto, limites de tamanho e necessidade de nova sessão.

Mantenha o núcleo global curto. Coloque contratos detalhados em arquivos referenciados, evitando repetir este configurador inteiro em cada turno.

UserPromptSubmit deve ser um lembrete curto e determinístico de papel, delegação e snapshot.

Ele não deve:

- Pesquisar a web.
- Consultar Jev.
- Criar agentes.
- Capturar modelos.
- Armazenar prompts brutos.
- Declarar autoridade ou referências inexistentes.

Instalação, confiança, carregamento e execução do hook são provas separadas.

Não edite banco de confiança nem instale bypass de confiança. Preserve decisões legítimas já existentes.

Confira schemas e eventos da versão instalada. Não use parâmetros não suportados como se bloqueassem ações.

PostToolUse não desfaz efeitos. Processos já iniciados, write_stdin e rotas especializadas podem exigir controles próprios.

Preserve hooks locais, Stop, identidade, aprovação exata, Humanizer, canais e checkpoints pertinentes. Não declare cobertura universal sem teste das rotas.

## 20. Verificação, medição e entrega

Execute verificações proporcionais ao que foi alterado. Não repita testes sem nova mudança, falha ou dúvida relevante.

Verifique, conforme aplicável:

- Instalação nova em ambiente isolado.
- Reexecução compatível como no-op.
- Migração incremental e preservação de personalizações.
- Recuperação de transação administrativa interrompida.
- Backup e rollback seletivo.
- Delegação real de tarefas com e sem código.
- Supervisão quando útil.
- Modelo e esforço solicitados versus efetivos.
- Precedência de perfis e configurações.
- Propagação de permissões e snapshot.
- Resume independente, continuação e SnapshotOnly.
- Integração Orca e tratamento de timeout.
- Jev, reuso, privacidade e preservação de falhas.
- Instalação, confiança e execução dos hooks.
- Limites configurados versus capacidade demonstrada.

Inclua regressões do resolver para:

- `Max`, `MAX` e `max`.
- Unicidade semântica após normalização.
- Esforços desconhecidos ou indisponíveis.
- Vencedor ausente ou oculto.
- Mapeamento inválido.
- URL divergente.
- Fonte incompleta.
- Escolha do máximo antes de verificar disponibilidade.
- Ausência de substituição por segundo colocado.

Demonstre concorrência com trabalho útil. Use mais de três agentes simultâneos quando capacidade e benefício permitirem; não fabrique carga apenas para atingir uma contagem.

SnapshotOnly bem-sucedido comprova preparação da captura. Não comprova lançamento, inferência, quota ou operação completa.

Para conclusão operacional, respeite os gates reais. No contrato atual de Jev, COMPLETE exige checks, revisão e evidências atuais, confiança mínima de 0,5 e residual máximo de 0,25. Em v2, considere o mínimo das questões Choice/Score realmente perguntadas; final continuity-only mantém progress e residual.

Esses limiares são política do contrato, não prova universal de calibração.

Reutilize ferramentas de medição existentes. Registre preparação, Jev, spawn, espera, execução, revisão, integração e retrabalho.

Compare qualidade e custo total. Ausência de medida é desconhecida, não zero. Replay não é execução live. Preço de API não representa automaticamente consumo do limite semanal do Codex.

Não prometa aceleração ou economia sem evidência comparável.

Entregue ao final:

1. Inventário e estado encontrado.
2. O que foi preservado, alterado e dispensou alteração.
3. Arquivos, manifestos e documentação.
4. Backups e rollback.
5. Verificações executadas e resultados.
6. Capacidade configurada e capacidade observada.
7. Integrações operacionais e limitações.
8. Otimizações em shadow ou ativadas.
9. Benefícios medidos e dados ainda desconhecidos.
10. Necessidade de nova sessão e qualquer ação realmente pendente do usuário.

Não declare “tudo funcionando” com base somente em arquivos criados, fixtures, catálogo, testes históricos ou retorno positivo de um launcher.

Execute o trabalho autorizado até o resultado verificável. Quando houver bloqueio real, preserve o que foi feito, explique exatamente o que falta e continue as partes independentes.
