# TKC-AUT-0017 — Simplificação mínima do método operacional

task_id: TKC-0017
order_id: TKC-0017-O01
short_ref: TKC-AUT-0017
request_type: proposta de autorização L2 documental/normativa
recipient / executor: AGT-001 III — coordenação técnica, ChatGPT GPT-6.2 (AUTODECLARADO)
sender: AGT-001 III
reviewer: AGT-002 — revisão independente por sessão distinta
authorization_state: PENDENTE — somente execução da C01 de preparação está autorizada
decision_ref: TKC-AUT-0017 @SHA #TRUE, revisão 1, a resolver após publicação
approval_channel / authorization_provenance: HUMAN-001, canal humano pertinente, MEDIADO; marcador não autentica identidade
status: PROPOSTA PUBLICADA, não autorizada nem executada
repository / branch: edinhogrubert/TeamKitCollection / main
base_commit: 30cc6388972a73534953928acbb09f435b48133e (base normativa; reconciliar commits C01 exclusivamente documentais antes de executar)
task_record: IA/tarefas/TKC-0017.md
product_scope_paths: nenhum
human_scope / documentation_scope_paths: AGENTS.md; IA/regras/comunicacao.md; IA/despachos/README.md; IA/tarefas/TKC-0017.md; IA/tarefas/indice.md (somente linha própria); IA/despachos/logs/TKC-EXE-0017.md; IA/despachos/retornos/TKC-RET-0017.md; IA/despachos/retornos/TKC-PAR-0017.md (revisão independente AGT-002)
documentation_write_authorization: PENDENTE de decisão específica sobre esta ordem; C01 autorizou apenas tarefa, linha do índice e esta AUT
revision: 1; published_order_sha: resolver pelo Git após publicação
capability_evidence: AGT-001 III publicação confirmada na RC-01 36f9ebe/30cc638 e claim C01 96de689a61ada9ce904189247a1a86ebf174c384; AGT-002 publicação confirmada 38352bb e revisão C19 26c74ff; revalidar capacidade aplicável e sessão no recebimento. Testes de produto não exigidos nesta ordem documental.
dependencies / claim_conflicts: RC-01 aceita 30cc638; piloto TKC-0016 concluído 56cd643; confirmar HEAD, posse C01 encerrada e ausência de conflito antes da execução.
feasibility_report_ref: ata RC-01, consolidação 36f9ebe e decisão 30cc638; consulta normativa C01, sem novo REQ/PAR preliminar. Revisão independente obrigatória da entrega.
risk: L2 — alteração normativa relevante, sem reduzir controles de segurança
cost_limit: R$ 0,00 absoluto, inclusive risco de cobrança futura; dúvida implica parada
log_path: IA/despachos/logs/TKC-EXE-0017.md
return_path: IA/despachos/retornos/TKC-RET-0017.md; parecer independente IA/despachos/retornos/TKC-PAR-0017.md
forbidden_actions: VM/Docker/testes de produto, execução remota, código, scripts, PROJETO.md, PAINEL.md, modelos legados, outras regras/tarefas, reescrita de histórico, CI/PR/proteção, permissões/credenciais, gastos, recursos faturáveis, force push/reset/rebase
stop_condition: qualquer conflito, capacidade/posse/autorização incerta, risco de cobrança, perda de regra indispensável, necessidade de outro caminho ou mudança material; parar e informar motivo

## Alteração autorizável

1. AGENTS.md: entrada curta, orientada a missão, autoridade, papéis, continuidade, custo zero absoluto, VM exclusivamente HUMAN-001 (inclusive após autorização), segurança, regras vigentes, estado e próximo passo. Reduzir duplicações e referências extensas; preservar requisitos únicos ou manter referência explícita à fonte normativa equivalente. Não adotar limite de linhas como critério isolado. Preservar versão anterior identificável pelo Git, eventos relevantes e links funcionais.
2. COM-001: versão nova, rito leve prospectivo para mudança delimitada, reversível, de baixo risco conhecido e critérios objetivos; tarefa como fonte detalhada de autorização, posse, checkpoints significativos, entrega, revisão, evidência e limites. Índice resumo/localizador, PROJETO macro, painel histórico já congelado. Um claim confirmado por executor/ciclo de escrita substantiva; não repetir claims por microajustes da mesma execução, preservar novos claims na substituição/retomada e segregação do revisor. Escopo/risco material exige nova decisão. Manter estados, proveniência, capacidade por função, gates, parada, controles de concorrência cooperativa e histórico lógico. Não confundir revisão com aceite.
3. COM-002: explicitar fluxo leve, autorização versionada na própria tarefa (TKC-XXXX @SHA #TRUE, identificação inequívoca do evento/revisão) ou AUT separada quando necessária; dispensar REQ/PAR/EXE/RET separados somente quando o registro integrado e autorização específica cobrirem seus eventos e evidências. Parecer prévio e ordem separada continuam quando risco/incerteza exigir. Preservar resolução de referências legadas e modelos para o fluxo separado, sem alterar modelos nesta ordem. Ajustar trechos conflitantes, não apenas anexar exceção ambígua. Transporte normal referência + SHA, contingência mediada não autoriza implantação. Identificação Agent/Task no commit quando disponível, autodeclarada, sem gate novo.

Esta tarefa modifica normas e, portanto, segue o rito vigente até a revisão e aceite; não usar o rito leve proposto para dispensar os registros desta própria alteração. A ordem autoriza executor e revisão documental independente com caminhos separados; AGT-002 só escreve após decisão humana aplicável ao seu papel e claim confirmado. A implementação não altera regras de segurança ou constituição, não promove M3-02, não fecha tarefas antigas. Não refazer o painel já histórico nem criar runner genérico. A vigência prospectiva do rito leve depende de aceite humano final após revisão, preservando autorizações anteriores.

## Critérios de aceite e verificações

- A01 — escopo: somente três arquivos normativos e registros próprios listados. Diff por base/HEAD e por tentativa, eventos preservados, nenhuma exclusão histórica oculta.
- A02 — AGENTS substancialmente menor, legível e com fontes essenciais localizáveis. Comparar tamanho antes/depois; não medir economia real de tokens por estimativa. Rastrear requisitos anteriores, especialmente sucessão e contrato do painel, autoridade, papéis, custo absoluto, VM exclusiva, segurança, hierarquia, contexto, qualidade e interrupção.
- A03 — COM-001/002 coerentes: autorização por revisão e caminhos, claim remoto, capacidade por função, escopo/risco, revisão independente aplicável, evidência e aceite distintos; sem lock automático. Fluxo leve prospectivo e legado resolvível, sem obrigação simultânea de documentos redundantes.
- A04 — inspeção de cenários documentais: mudança leve autorizada, falta de escrita/claim, conflito, mudança de escopo, revisão independente, execução humana de VM, handoff e decisão pendente/FALSE. Não rotular inspeção como teste operacional. Preservar cenários/limitações existentes.
- A05 — AGT-002 confere fontes primárias, diff, rastreabilidade de controles, links, compatibilidade dos modelos legados, coerência normativa e ausência de redução de segurança; parecer independente e aceite humano separados.
- A06 — nenhuma operação faturável, VM, Docker, teste de produto ou infraestrutura. Esforço/custo efetivo NÃO MEDIDO quando ausentes. Avaliar o método após dois incrementos reais; sem novo piloto administrativo.

## Entrega

AGT-001 publica claim antes da edição substantiva, confirma remoto, registra diff, revisões, limites, logs e retorno no escopo; atualiza tarefa e linha própria. AGT-002 recebe referência por HUMAN-001 para revisão específica, sem modificar os três arquivos normativos. Encerrar após decisão aplicável e registrar próxima entrega de produto. Nenhuma vigência nova ou aceite macro por autorrelato.

## Histórico de preparação

C01 autorizada por HUMAN-001 #TRUE para três caminhos documentais; base 30cc638, claim 96de689a61ada9ce904189247a1a86ebf174c384 confirmado. AGT-001 III autoria e registro; publicação técnica via conector GitHub, identidade conforme commit. Esta proposta permanece PENDENTE.
