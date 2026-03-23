# Caso 5 — Sistema de Licenciamento Público
Aqui está um resumo estruturado do **Caso 5**, focado nos pontos que geram regras de negócio para o seu modelo de domínio:

---

## 📋 Resumo: Caso 5 — Sistema de Licenciamento Público

O sistema gerencia o ciclo de vida de **licenças digitais** para atividades comerciais em uma prefeitura. O domínio é marcado por um fluxo processual rígido, prazos legais e normas que mudam com o tempo.

### 1. O Fluxo do Processo
Um licenciamento não é um evento único, mas uma sequência de etapas que determinam o estado do pedido:
* **Entrada:** Protocolo inicial e análise de documentos.
* **Interação:** Possibilidade de exigências complementares e vistorias.
* **Decisão:** Emissão de parecer técnico culminando em uma decisão administrativa (**Deferido, Indeferido, Arquivado ou Anulado**).

### 2. A Dinâmica do Requerente (Cidadão)
O requerente tem papel ativo e pode intervir no fluxo para defender seus interesses através de:
* Cumprimento de exigências.
* Solicitação de prorrogação de prazos.
* Apresentação de defesa ou interposição de recursos contra decisões.

### 3. Regras de Prazos (Complexidade do Domínio)
Este é um dos pontos mais ricos do caso. Os prazos não são datas simples; eles possuem comportamento:
* **Contagem:** Feita estritamente em **dias úteis**.
* **Estados:** Podem ser **suspensos** ou **prorrogados**.
* **Natureza:** Podem ser **decadenciais** (perda do direito se não exercido no tempo).

### 4. Normatividade e Temporalidade
As leis (normas) mudam, e o sistema deve respeitar o princípio da anterioridade:
* Uma **norma possui vigência**. Se uma lei mudar hoje, ela só afeta novos pedidos. O processo em andamento segue a norma vigente na data do seu protocolo.

### 5. Pós-Licenciamento (Fiscalização)
O domínio se estende após a entrega da licença. A prefeitura mantém o poder de polícia, o que pode resultar em:
* Autos de infração e multas.
* Interdição da atividade.
* **Cassação da licença** (extinção do direito concedido anteriormente).
 seu diagrama, essas regras devem aparecer como métodos e associações claras.

**Gostaria que eu resumisse também as possíveis "dores" ou problemas que esse caso tenta resolver para você usar na introdução do seu trabalho?**
