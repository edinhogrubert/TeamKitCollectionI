# Índice de tarefas — TeamKitCollection

**Estado:** REGISTRO INICIAL — mecanismo de bloqueio/automação ainda não implementado  
**Regra:** consultar `IA/regras/comunicacao.md` (COM-001) e `IA/despachos/README.md` (COM-002) antes de assumir trabalho; consultar `IA/PROJETO.md` para o estado macro. Ordens publicadas e retornos são rastreados por `task_id`, mas não entregues automaticamente a IAs inativas.

| Task ID | Objetivo | Estado confirmado | Responsável ativo | Registro | Observação |
|---|---|---|---|---|---|
| TKC-0002 | Teste de sincronização incremental de regras e custo de contexto | CONCLUIDA (ensaio documental, revisão distinta por AGT-001) | NENHUM — tentativa TKC-0002-C01 encerrada | `IA/tarefas/TKC-0002.md` | Parecer `IA/despachos/retornos/TKC-PAR-0002.md` e log `IA/despachos/logs/TKC-EXE-0002.md` verificados; entrega `7954695`; sem validação operacional ou medição de tokens |
| TKC-0001 | Piloto COM-002: parecer independente M1 D2/D5–D8 e consistência COM | CONCLUIDA — encerramento administrativo aceito por HUMAN-001 com ressalvas (`MEDIADO`), sem aceite M1 | NENHUM — C01, C02 e C03 entregues, sem posse ativa | `IA/tarefas/TKC-0001.md` | Parecer `IA/despachos/retornos/TKC-PAR-0001.md`, log `IA/despachos/logs/TKC-EXE-0001.md`; integração `a183a47`, reconciliação `e054205`, reivindicação C03 `1718332`; parecer da revisão `APROVAR COM RESSALVAS` recebido via HUMAN-001 (`MEDIADO`); D8/D9 e M1 pendentes |
| TKC-0003 | Ajuste D6 do cabeçalho de M1_TEST_RELATORIO | EM_REVISAO — ajuste pontual entregue, aguardando revisão distinta | NENHUM — C01 ENTREGUE, sem posse ativa | `IA/tarefas/TKC-0003.md` | Apenas campo `Estado atual consolidado` alterado; posse C01 `4e51e67`; D6/D8/D9/M1 não aprovados |
| TKC-0004 | Preparação operacional do M3-02: pacotes, handoff e revisão entre IAs | BLOQUEADA — tentativa piloto C03 FALHOU (evidência mediada); C04 documental entregue; revisão C02 pendente | NENHUM — C01/C02/C04 ENTREGUES; C03 sem posse remota confirmada | `IA/tarefas/TKC-0004.md` | C02 reivindicada `4ba4c08`; C04 reivindicação `8b18435`, parecer `382e31f`, entrega `5e57ac1`; `IA/despachos/retornos/TKC-RET-0004-PILOTO-M3-02.md`; nova tentativa depende de decisão humana; M3-02 PENDENTE |
| TKC-0005 | Primeiro backend real e laboratório | EM_REVISAO — C07 orquestração publicada, execução pendente | NENHUM — C01–C07 ENTREGUES | `IA/tarefas/TKC-0005.md` | Menu 7 check, 8 API, 9 falha 503 e recuperação; PostgreSQL existente preservado |
| TKC-0006 | Script reprodutível de instalação Docker/Compose Ubuntu | EM_REVISAO — C01 entregou script Git; instalação na VM não verificada | NENHUM — C01 ENTREGUE, sem posse ativa | `IA/tarefas/TKC-0006.md` | Instalador `scripts/infra/install-docker-ubuntu.sh`, diagnóstico `--check` e instalação explícita `--install`; nenhum container criado pelo agente |
| TKC-0007 | Script PostgreSQL 16 no laboratório | EM_REVISAO — C02 digest fixado, execução na VM pendente | NENHUM — C01/C02 ENTREGUES | `IA/tarefas/TKC-0007.md` | PostgreSQL 16.16 linux/amd64 por digest; HUMAN-001 autorizado a implantar, ainda sem evidência operacional |
| TKC-0008 | Menu unificado e teste de persistência PostgreSQL | EM_REVISAO — C02 registrou INSERT/RESTART/SELECT MEDIADO | NENHUM — C01/C02 ENTREGUES | `IA/tarefas/TKC-0008.md` | Teste de persistência após reinício relatado com sucesso por HUMAN-001; bootstrap VM limpa ainda não testado |
| TKC-0009 | Handoff do DevOps e patch de scripts | EM_REVISAO — C04 entregou patch L2 (`backend-lab.sh` + `teamkit-lab.sh`) e TKC-RET-0009 | NENHUM — C01–C04 ENTREGUES, sem posse ativa | `IA/tarefas/TKC-0009.md` | Posse C04 `bb277a7`; `backend-lab.sh` `8d0cfa7`; `bash -n` e testes estáticos PASS; Docker na VM NÃO_EXECUTADO |
| TKC-0010 | Revisar risco de `errexit` no menu Bash | EM_REVISAO — C12 + OP7 + parecer AGT-002 (`2b1fa8a`); aguarda AGT-001 | NENHUM — C01–C12 + complementar OP7 ENTREGUES | `IA/tarefas/TKC-0010.md` | OP7/OP8/OP9 = RELATADO (HUMAN-001); TN-* = inspeção documental; parecer AGT-002 @ `2b1fa8a`; M3-02 permanece PENDENTE |
| TKC-0011 | Parecer técnico do backend FastAPI | EM_REVISAO — complemento C03 publicado, revisão AGT-001 pendente | NENHUM — C01/C02/C03 ENTREGUES | `IA/tarefas/TKC-0011.md` | Prioridades BE-001/002/003, intervenção mínima e gates A01–A09; claim `8babbba1`; testes NÃO EXECUTADOS |
| TKC-0012 | Matriz QA/Segurança independente | EM_REVISAO — TKC-PAR-0010-QA publicado por AGT-002, aguardando revisão final de AGT-001 | NENHUM — C04 ENTREGUE, sem posse ativa | `IA/tarefas/TKC-0012.md` | Parecer TKC-PAR-0010-QA.md publicado e C04 encerrado |
| TKC-0013 | Consolidação de arquitetura e dependências | EM_REVISAO — TKC-PAR-0013 entregue, revisão independente pendente | NENHUM — C02 AGT-001 ENTREGUE | `IA/tarefas/TKC-0013.md` | Parecer L0/L1 de interfaces e bloqueadores; faltam TKC-PAR-0010/0011 e execução VM |
| TKC-0014 | Piloto de painel, handoff e AGT-ACI | EM_REVISAO — C02 continuidade estratégica entregue; revisão e ensaio de sucessão pendentes | NENHUM — C01/C02 ENTREGUES | `IA/tarefas/TKC-0014.md` | Handoff `26dca2f`; AGENTS.md v0.1.2 `1c762da`; painel histórico; C02 `8244c9d`; demais propostas não homologadas |
| TKC-0015 | Fortalecimento operacional do método multiagente | CONCLUIDA — etapa documental, ressalvas reconciliadas | NENHUM — C01–C05 ENTREGUES | `IA/tarefas/TKC-0015.md` | Parecer C04 `47d047a`; claim C05 `efea458`; entrega `ad53847`; M3-02 PENDENTE |
| TKC-0016 | Piloto operacional M3-02: teste unitário de indisponibilidade do backend | CONCLUIDA — piloto aprovado, 4/4 MEDIADO, encerramento autorizado | NENHUM — C20 ENTREGUE | `IA/tarefas/TKC-0016.md` | evidência `4883797`; retorno `fe95ede`; C20 `12e336f`; M3-02 PENDENTE de aceite separado |
| TKC-0017 | Simplificação mínima do método operacional (RC-01) | PENDENTE — C01 entregue, AUT aguarda #TRUE | NENHUM — C01 ENTREGUE | `IA/tarefas/TKC-0017.md` | `TKC-AUT-0017 @bf4bbb6`; claim `96de689`; sem alteração normativa |
| M1-REVISAO | Revisão documental M1 e auditoria D2/D5–D8 | EM_ANDAMENTO (macro) | NÃO ATRIBUÍDO NESTE ÍNDICE | `IA/PROJETO.md` | Linha informativa: **não constitui reivindicação de posse**; Bloco 3 já publicado, auditoria dirigida pendente |
| M3-01 | Especificar COM-001 e iniciar índice | CONCLUÍDO (documental) | NENHUM | `IA/regras/comunicacao.md` | Contrato publicado e verificado; bloqueio atômico e ensaios operacionais pendentes |
| M3-02 | Implementar registros de tarefa e handoff testados | PENDENTE | NENHUM | A criar com autorização | Não iniciar sem atribuição e TRUE aplicável |
| M5-01 | Implementar coordenação concorrente segura | PENDENTE | NENHUM | A criar com autorização | Sem lock/lease/fencing operacional |

**Protocolo de mensagens:** referências `TKC-REQ-XXXX` (pedido), `TKC-PAR-XXXX` (parecer), `TKC-AUT-XXXX` (proposta), `TKC-EXE-XXXX` (log) e `TKC-RET-XXXX` (resultado) são resolvidas pelos caminhos de [COM-002](../despachos/README.md). Sem ordem real publicada, nenhum desses exemplos é tarefa ou autorização vigente. `M1-REVISAO` não possui reivindicação individual confirmada neste índice, embora a etapa macro esteja em andamento.

## Como atualizar

1. Um novo trabalho recebe ID estável e registro próprio `IA/tarefas/<ID>.md` antes de começar sua execução.
2. Estado, responsável e referência Git do índice devem corresponder ao registro específico. **Discordância bloqueia execução modificadora até reconciliação.**
3. Sem confirmação de registro publicado, exibir `DESCONHECIDO` ou `NÃO ATRIBUÍDO`; nunca inferir que ninguém está trabalhando.
4. Não alterar este índice apenas para sugerir que uma tarefa está livre; consultar fonte remota e todas as tarefas que compartilhem recursos.
5. Histórico de alterações fica no Git e no log da tarefa. Correção de um evento é novo registro, sem apagar a ocorrência original.

**Aviso:** não existe serviço de monitoramento ou exclusão automática implementado. As linhas acima são inventário inicial, não locks.
