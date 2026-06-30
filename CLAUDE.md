# claude-skills

Repositório de skills do Claude Code web para Michela Filiadona Gringa.

## Skills disponíveis

### Skills externas (importadas)

| Skill | Fonte | Comando |
|-------|-------|---------|
| `ads` | AgriciDaniel/claude-ads | `/ads` |
| `adversarial-reviewer` | alirezarezvani/claude-skills | `/adversarial-reviewer` |
| `ai-seo` | coreyhaines31/marketingskills | `/ai-seo` |
| `brainstorming` | obra/superpowers | `/brainstorming` |
| `copywriting` | coreyhaines31/marketingskills | `/copywriting` |
| `frontend-design` | anthropics/skills (oficial) | `/frontend-design` |
| `landing-page-generator` | alirezarezvani/claude-skills | `/landing-page-generator` |

### Skills locais (criadas aqui)

| Skill | Descrição | Atenção |
|-------|-----------|---------|
| `analise-trafego-dunas` | Analisa tráfego Meta/Green/Zouti | Lê token do .env, nunca expõe |
| `clickup-clonar-modelo` | Clona modelo ClickUp (só leitura) | Seguro |
| `clickup-replicar-cliente` | Replica estrutura para novo cliente | Escreve no ClickUp — sempre dry-run + confirmação |
| `comentario-dm-ratos` | Comentários/DMs para Ratos de Academia | Integração Instagram — revisar antes de produção |

## Localização dos arquivos

Todas as skills estão em `.claude/skills/`.

## Como atualizar uma skill local

Edite o arquivo correspondente em `.claude/skills/nome-da-skill.md` e faça commit.
