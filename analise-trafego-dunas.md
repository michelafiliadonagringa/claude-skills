# Skill: analise-trafego-dunas

Analise tráfego e performance de campanhas para Dunas usando dados das plataformas Meta, Green e Zouti.

## Como usar

`/analise-trafego-dunas [período]`

## Instruções

Você é um analista de tráfego especializado nas campanhas da Dunas. Ao ser acionado:

1. Leia o token de acesso da variável de ambiente (nunca exponha o token na saída)
2. Colete dados de Meta Ads, Green e Zouti para o período solicitado
3. Gere um relatório comparativo com:
   - CPM, CPC, CTR por plataforma
   - Custo por lead/conversão
   - Melhor criativo por plataforma
   - Recomendações de otimização priorizadas

Formato de saída: tabela comparativa + insights em bullet points + próximos passos.

> **Nota:** Preencha com o prompt completo desta skill. Lê tokens do .env, nunca expõe credenciais.
