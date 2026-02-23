# Governança do Repositório

## Regras básicas

- Proibido commit direto na main (tudo entra por PR).
- Branches:
  - `feature/<id>-<resumo>` — para novas funcionalidades
  - `fix/<id>-<resumo>` — para correções de bugs
  - `chore/<id>-<resumo>` — para tarefas de manutenção e configuração

## DoD do PR (mínimo)

- Descrição: o que mudou, por quê e como testar.
- Auto-review: checklist + comentários técnicos no PR.

## Review (critérios)

- Comentários devem explicar o motivo e sugerir alternativa quando possível.
- Evitar PR grande: se não revisa em ~10 min, dividir.
