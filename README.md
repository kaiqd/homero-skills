# Homero Skills

Skills para agentes de código que trabalham no projeto iOS Homero. As instruções são escritas em Markdown, sem depender de um harness específico.

## Skills disponíveis

| Skill | Finalidade |
| --- | --- |
| [review-homero](review-homero/SKILL.md) | Revisar uma branch contra `dev`, considerando as regras arquiteturais do Homero, Flow, Volt, HDesignSystem e testes. |

## Como usar

Disponibilize a pasta da skill no local de descoberta de skills do seu agente, conforme a documentação da ferramenta. Se o agente não oferecer descoberta automática, peça que leia o `SKILL.md` e siga suas instruções.

Para uma revisão, informe a branch e, quando disponível, o contexto da PR ou issue:

```text
Leia review-homero/SKILL.md e revise a branch <branch> do repositório Homero.
Contexto: <descrição da PR e critérios da issue>
```

A skill produz um parecer na conversa, preserva o checkout e não publica alterações ou comentários remotos.
