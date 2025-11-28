# Gaelion 🛡️
Gaelion protects the language model from malicious prompts

## Sistema de Detecção Preventiva de Prompts Maliciosos
### Objetivo
- Detectar e bloquear prompts maliciosos antes que cheguem ao modelo de linguagem.
- Reduzir riscos de jailbreak, vazamento de conteúdo sensível e manipulação intencional.
- Aumentar a segurança de sistemas de IA usando uma arquitetura híbrida eficiente.

### Contribuições
- Arquitetura que combina detectores leves locais + classificadores robustos sob demanda.
- Redução de falsos positivos/negativos via ensemble de modelos avaliadores.
- Menor custo computacional graças à ativação seletiva de modelos maiores.
- Foco em detectar intenção maliciosa, não apenas filtrar conteúdo gerado.
- Uso de treinamento adversarial e análise contextual para identificar ataques sutis.
- Saídas estruturadas: escores de risco, motivos interpretáveis, tokens suspeitos.

## Como executar o projeto
...

## Roadmap de Implementação
- 28/11 — 30/11: Definição da arquitetura e organização do repositório.
- 01/12 — 03/12: Implementação do detector leve e calibração inicial.
- 04/12 — 05/12: Criação do medidor de risco e definição dos limiares.
- 06/12 — 07/12: Integração do classificador robusto + ensemble.
- 08/12: Construção da API e integração completa do pipeline.
- 09/12: Testes adversariais, ajustes e validação.
- 10/12: Documentação final e preparação para entrega.
