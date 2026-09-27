# Perfil e programa em andamento — Bernardo

Dados puxados do artefato **Bloco de 12 Semanas** (app pessoal de treino) e da sessão em que ele foi construído. Serve de contexto para o `program-architect` e o resto do time quando forem analisar, ajustar ou continuar este bloco — não é um pedido de programa novo, é o programa **que já está rodando**.

> ⚠️ **Dado sensível.** Este arquivo tem peso corporal e histórico de treino. Mantenha este repositório privado.

## Correção — 27/09/2026

O início do bloco estava registrado como **24/08/2026**, deduzido numa sessão anterior a partir do número de semana que a tela mostrava naquele momento — e esse número em si já estava errado. O usuário confirmou o início real: **07/09/2026** (segunda-feira), batendo exatamente com os primeiros dados reais gravados no app (peso, diário e a carga de supino, todos de 09/09). O bloco começou **duas semanas mais tarde** do que eu tinha calculado.

Isso foi corrigido no banco de dados do artefato: `inicio` → `2026-09-07`; as chaves de `marcas` e `ajustes` (formato `semana:dia`) e o campo `semana` dentro de `extras` foram deslocados em −2 para continuar apontando para os mesmos dias reais da semana — nenhum dado histórico foi perdido, só a numeração da semana foi corrigida. `peso`, `diario`, `comidaLog` e `cargas` usam data absoluta e não precisaram de ajuste.

**Consequência prática**: o checkpoint anterior (abaixo, mantido como registro) analisou o bloco como se hoje fosse semana 5 — na verdade é **semana 3**. As cargas-alvo que eu tinha passado (agachamento 112,5 kg etc., da semana 5) estavam erradas para hoje; as corretas da semana 3 estão na tabela em "Estrutura do bloco".

## Perfil físico

| Item | Valor |
|---|---|
| Altura | 183 cm |
| Idade | 30 anos |
| Peso inicial do bloco (07/09) | 96 kg |
| Meta do bloco | 88 kg (~0,5–0,6%/semana) |
| Sexo | Masculino |

## Objetivo do bloco

**Barra fixa.** No início do bloco, 5 repetições no peso do corpo. Meta na semana 12: séries limpas de 5 com carga extra. Três exposições de puxada vertical por semana — a última coisa a cortar quando falta tempo ou energia.

Contexto: hipertrofia em déficit calórico, 6 treinos por semana (Empurrar A/B · Puxar A/B · Perna A/B, rotação Push-Pull-Legs dobrado), 1 dia de descanso.

## Estrutura do bloco (12 semanas)

| Semana | Fase | Foco |
|---|---|---|
| 1–2 | Base | Reaprender o movimento, calibrar RIR, sem correr atrás de carga |
| 3–6 | Acumulação | Volume sobe, RIR honesto — é aqui que o bloco é ganho |
| 7 | Deload 1 | Carga mantida, séries pela metade, comida na manutenção |
| 8–11 | Intensificação | Déficit mais fundo, carga protegida nos compostos, isolado cortado primeiro |
| 12 | Deload 2 | Recupera, reteste opcional de barra com carga e desenvolvimento, planeja o bloco 2 |

Regras fixas em déficit: proteger agachamento / terra romeno / supino / barra fixa / desenvolvimento militar sempre antes de cortar um isolado; terra romeno tem teto rígido de RIR 2 (nunca forçar); barra fixa nunca até a falha.

Cardio: LISS em Zona 2 todo dia de treino (20–45 min conforme a semana) + finalizadores em Zona 4 nos dois dias de Puxar.

### Cargas-alvo semana 3 e 4 (semana atual e a próxima)

| Semana | Agachamento | Supino | Terra romeno | Barra fixa | RIR (principal/isolado) |
|---|---|---|---|---|---|
| **3 (hoje)** | 105 kg | 75 kg | 100 kg | PC · 5×5-6 | 2 / 1-2 |
| 4 | 110 kg | 77,5 kg | 107,5 kg | PC · 5×6-7 | 2 / 1 |

Semana 3 é a "semana de referência" do bloco — começa a subida de volume da Acumulação, RIR honesto é o que mais importa aqui.

## Status atual — hoje é 27/09/2026

- **Início do bloco**: 07/09/2026 (segunda-feira) → o calendário do app avança sozinho a partir daqui.
- **Semana calculada para hoje**: **semana 3 de 12** (fase Acumulação, semana de referência).
- **Fim previsto do bloco**: 29/11/2026.
- **Deload 1**: semana 7, a partir de 19/10/2026 — ainda a três semanas e meia de distância, não é urgência.

## Peso registrado

| Data | kg |
|---|---|
| 09/09 | 96,0 |
| 10/09 | 96,0 |
| 11/09 | 96,0 |
| 12/09 | 95,5 |
| 13/09 | 95,0 |
| 14/09 | 95,0 |

Queda de 1 kg em 5 dias — ritmo rápido para início de déficit; parte é água/glicogênio baixando, não gordura pura. Sem registro entre 14/09 e o checkpoint de 27/09 — ver "Diário do dia" abaixo: confirmado que o treino continuou, só o registro no app parou.

**20/09 a 27/09 (hoje)**: 20 dias sem álcool, fotos de progresso tiradas em três ângulos (costas / três-quartos / frente) — primeiro registro fotográfico do bloco, vira a referência para comparações futuras. Sem peso numérico registrado ainda hoje.

## Adesão ao treino (exercícios marcados como feitos)

| Semana:Dia (corrigido) | Data real | Exercícios marcados |
|---|---|---|
| 1:0 (segunda) | 07/09 | 5 |
| 1:2 (quarta) | 09/09 | 5 |
| 1:3 (quinta) | 10/09 | 6 |
| 1:4 (sexta) | 11/09 | 7 |
| 1:5 (sábado) | 12/09 | 8 (inclui 1 encaixe do Claude) |
| 2:0 (segunda) | 14/09 | 3 |
| 2:1 (terça) | 15/09 | 6 |
| 2:2 (quarta) | 16/09 | 1 |

Nada marcado no app entre 16/09 e o checkpoint de 27/09 — confirmado que o treino continuou, só o registro parou. Sob a numeração corrigida, essa adesão forte é da fase **Base** (semanas 1–2), não da Acumulação — ainda mais coerente: é justamente a fase de "aparecer e anotar números honestos".

## Cargas anotadas

Só um registro formal até agora: **Supino reto — 100 kg × 3 reps, RIR 0** (09/09, dia 1 do bloco). Sob a numeração corrigida isso foi feito num dia de **semana 1 (Base)**, que previa carga bem menor (~45–50 kg de referência) — ainda mais chamativo do que parecia antes. Vale confirmar: foi um teste pontual de força/1RM fora do treino do dia, ou uma sessão real de supino nesse peso? O registro de cargas no app existe para todos os principais mas quase não foi usado — a maior parte do acompanhamento aconteceu via as caixinhas de "exercício feito", não via este log formal.

## Exercícios fora do plano (analisados pelo time program-architect + biomecânica)

| Data | Semana real | O que fez | Decisão dos agentes |
|---|---|---|---|
| 10/09 | 1 | Pular corda, 15 min (dia de Perna A pesado) | **Não compensa** — soma fadiga que compromete a recuperação do dia de perna pesado |
| 11/09 | 1 | Desenvolvimento de ombro | **Extra** |
| 12/09 | 1 | Desenvolvimento de ombro em pé na barra de agachamento | **Troca** → virou "Desenvolvimento de ombro em pé na barra", RIR 1, 50 kg — mesmo padrão vertical, RIR mais baixo que o previsto, sem duplicar estímulo |
| 12/09 | 1 | "sss" (entrada sem detalhe) | **Extra** |
| 15/09 | 2 | Hack machine com os pés mais à frente | **Troca** |

## Nutrição

Metas por tipo de dia: **pesado** 2.800 kcal / 210 P / 320 C / 75 G · **leve** 2.550 / 210 / 245 / 80 · **descanso** 2.250 / 210 / 160 / 85.

O recurso de estimativa de macros por texto livre (Claude lê o que foi comido e compara com a meta) foi usado uma vez, em 13/09 — refeições daquele dia estimadas em torno de café preto + galinhada (arroz com frango) + salada, ~45 g de proteína só nessa refeição principal. Não foi usado de novo desde então.

## Diário do dia — única análise feita pelo Claude (13/09)

> **Leitura**: Dia de descanso ativo cumprido dentro do plano — caminhada com trechos leves de corrida, 10 mil passos, sono 7h+ e proteína batida. Peso caiu de 96 para 95 kg em 5 dias, ritmo rápido para início de bloco em déficit; parte disso é retenção de água baixando.
>
> **Ajustes sugeridos**: manter RIR honesto na próxima sessão sem compensar a queda de peso com mais volume do que o planejado · monitorar o peso mais alguns dias antes de qualquer ajuste calórico, essa queda tende a estabilizar · manter os 10 mil passos e o cardio leve nesse padrão, sem aumentar enquanto o volume sobe na semana de acumulação.
>
> Cardio daquele dia: caminhada na rua com trechos leves de corrida, 6,14 km, 55 min.

## Checkpoint — 27/09/2026 (mantido como registro; ver "Correção" no topo)

Hiato de registro de 11–13 dias (14–16/09 até 27/09) investigado com o usuário: **treino continuou normalmente, só o registro no app parou; nenhum sinal de alerta** (sem dor nova, sono ok, disposição normal). Pelo checklist de indicadores de deload do `periodization-engine` (estagnação, fadiga crônica, distúrbio de sono, dor articular, evitar o treino) — nenhum bateu. Esse veredito continua válido; só a semana em que ele se aplica mudou (era semana 3, não semana 5 — ver correção acima).

**Em aberto**: o registro de Supino 100 kg × 3 RIR 0 (09/09) segue sem esclarecer — ver "Cargas anotadas" acima, agora com o contexto de que foi feito num dia de semana 1 (Base), o que torna a pergunta mais relevante ainda.

## O que foi construído nesta sessão (para contexto do time de agentes)

O artefato **Bloco de 12 Semanas** é um app pessoal (HTML/JS, três abas: Hoje / Treino / Comida) com sincronia entre celular e navegador. Nesta sessão:

1. **Arrumações gerais**: calendário de semana passou a andar sozinho a partir da data de início do bloco; registro de cargas mudou de aba; PR de barra fixa passou a contar o peso do corpo; projeção de gasto calórico do dia inteiro (não só o já realizado).
2. **Dois bugs reais de "não consigo marcar a caixinha"**, ambos achados por teste automatizado com toque real (não clique sintético) depois de reports repetidos do usuário:
   - A sincronia com a nuvem trazia de volta o **dia da semana** de uma sessão anterior, sobrescrevendo o dia de hoje — a aba Treino abria vazia (dia de descanso) mesmo em dia de treino real. Corrigido tirando `dia` da lista de campos sincronizados.
   - **Corrida entre eventos de toque**: o app escutava tanto `pointerup` quanto `click` com uma janela anti-duplicata de 450 ms; no celular, gravar o estado atrasava o `click` além dessa janela, e ele *desmarcava* o que acabara de ser marcado. Corrigido removendo o caminho duplo (o botão é nativo, `click` sempre chega).
3. **Recurso novo — "O que eu comi hoje"**: campo de texto livre na aba Comida, o Claude estima macros e compara com a meta do dia.
4. **Recurso novo — "Como foi o dia"**: campo de cardio + observações na aba Treino, disponível mesmo em dia de descanso, com análise do Claude (leitura do dia + até 3 ajustes + alerta quando há sinal real de risco).
5. **Este repositório** (`fitness-program`): a skill e o time de agentes (`program-architect`, `exercise-guide`, `nutrition-linker`, `template-builder` + as skills de apoio `periodization-engine` e `exercise-biomechanics`) que o app já citava nos botões "Analisar e encaixar no treino" e "Copiar para o Claude", buscados de `revfactory/harness-100` e limpos de um artefato de exportação que quebraria o frontmatter.
6. **Correção de data de início** (27/09): o `início` do bloco estava deduzido errado por duas semanas — corrigido no banco do artefato e neste arquivo (ver "Correção" no topo).

**Nota técnica**: anexar este repositório numa sessão do Claude Code já em andamento (via `add_repo` + `register_repo_root`) não carregou `.claude/skills` nem `.claude/agents` na ferramenta de skills daquela sessão — só o repositório primário da sessão recebe esse carregamento automático. Para usar `/fitness-program` de verdade (com Task/SendMessage entre os 4 agentes), abra uma sessão nova com este repositório como principal.
