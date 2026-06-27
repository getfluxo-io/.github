## Contexto

Descreva o problema e ligue a Issue, Discussion ou RFC relacionada.

## Alteração

Explique comportamento, contratos e ficheiros afetados.

## Verificação

- [ ] Testes e builds relevantes passaram.
- [ ] Considerei segurança, tenant isolation e idempotência.
- [ ] Para mudanças financeiras, descrevi impacto em ledger, saldos, reconciliação e auditoria.
- [ ] Para pagamentos, desembolsos ou eventos, validei idempotência, retry/replay e chaves de deduplicação.
- [ ] Para dados multi-tenant, confirmei isolamento de tenant, autorização e ausência de vazamento entre instituições.
- [ ] Não incluí segredos, PII ou dados institucionais.
- [ ] Atualizei documentação e migração quando aplicável.
- [ ] Mudanças transversais seguiram o processo de RFC.

## Risco e rollback

Descreva riscos, compatibilidade, rollout e forma de reverter.
