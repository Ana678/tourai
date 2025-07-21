## RNF02 - Confiabilidade

O sistema deve estar disponível e operante ao menos 99,9% do tempo, minimizando falhas durante operações críticas.

---

## 📄 Metadados do Requisito

- **Autor do Requisito:** Ádisson
- **Justificativa:** Garantir que os usuários possam acessar e utilizar o sistema de forma contínua, especialmente durante o planejamento e execução de viagens, onde a interrupção pode causar grandes transtornos.
- **Prioridade:** Alta

---

## ✅ Critérios de Aceitação

1. O tempo de inatividade não planejado do sistema não deve exceder 0,1% do tempo total de operação em um mês.
2. O sistema deve ter um mecanismo de monitoramento contínuo para detectar e alertar sobre falhas em tempo real.
3. As operações críticas (ex: criação de roteiro, login, acesso a mapas) devem ser resilientes a falhas parciais do sistema.
4. O sistema deve possuir um plano de recuperação de desastres que permita a restauração completa em até 4 horas após um incidente grave.
