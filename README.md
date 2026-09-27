# fitness-program

Skill + time de agentes do Claude Code para desenhar programas de treino: objetivo → periodização → cronograma semanal → guia de exercícios → plano de nutrição → templates de acompanhamento, tudo num pipeline colaborativo.

Buscado de [revfactory/harness-100](https://github.com/revfactory/harness-100/tree/main/en/74-fitness-program) (episódio 74) e instalado aqui para ficar reutilizável em qualquer sessão do Claude Code, sem misturar com outros projetos.

## Por que este repo existe

O app **Bloco de 12 Semanas** (artefato pessoal de treino) já referencia esse time de agentes nos botões "Analisar e encaixar no treino" e "Copiar para o Claude" — a ideia é copiar o que foi registrado no app, colar numa sessão do Claude Code aberta *neste* repositório, e deixar os agentes decidirem como encaixar no plano.

## Estrutura

```
.claude/
├── CLAUDE.md
├── agents/
│   ├── program-architect.md    — desenho de programa, periodização, cronograma
│   ├── exercise-guide.md       — execução, dicas de forma, substituições
│   ├── nutrition-linker.md     — nutrição casada com o treino, timing, suplementos
│   └── template-builder.md     — logs, planilhas de acompanhamento, formulários
└── skills/
    ├── fitness-program/        — orquestrador (aciona o time de 4 agentes)
    ├── periodization-engine/   — modelos de periodização, cálculo de volume/intensidade, deload
    └── exercise-biomechanics/  — biomecânica, ativação muscular, exercícios substitutos
```

## Uso

Numa sessão do Claude Code aberta neste repositório, peça em linguagem natural ("monta um programa de hipertrofia, 4x por semana, academia completa") ou acione a skill diretamente com `/fitness-program`. Veja `.claude/skills/fitness-program/skill.md` para os modos de execução (pipeline completo, só cronograma, só guia de exercício, etc.) e o protocolo de comunicação entre os agentes.

## Nota sobre o texto original

Os arquivos-fonte no repositório de origem tinham marcas de bloco de código e trechos duplicados sobrando (artefato de como foram exportados) — removidos aqui para o frontmatter YAML ser lido corretamente e o conteúdo não vir com lixo. Nenhum conteúdo substantivo foi alterado.
