

## 1. Metodologia e Premissas da Análise

### 1.1. Método Escolhido: Fluxo de Caixa Descontado (FCD)

O método FCD é o mais adequado para o Hospfy. A projeção de fluxo de caixa fornecida (imagem) nos permite usar os próprios dados de crescimento da empresa, em vez de hipóteses externas, tornando a análise muito mais precisa e alinhada ao plano.

### 1.2. Aplicação do Valuation no Hospfy

Para aplicar o FCD, utilizamos as seguintes premissas, **agora baseadas nos dados da imagem**:

**1. Premissa de Receita (Baseada na Imagem):**
A projeção de Jan-Abr mostra um crescimento de receita acelerado:
* Janeiro: R$ 4.200
* Fevereiro: R$ 9.100
* Março: R$ 15.400
* Abril: R$ 23.100

A imagem também valida que o **ponto de equilíbrio (break-even)** operacional (onde a receita cobre os custos fixos + variáveis) ocorre muito próximo do Mês 4 (Saldo de -R$ 100,50).

Com base nisso, extrapolamos a receita para os 5 anos, assumindo que o break-even é atingido no Mês 5 e o crescimento continua em ritmo forte, porém desacelerando percentualmente à medida que a base aumenta:

* **Receita Ano 1:** R$ 337.694 (Total dos 12 meses, extrapolando a curva de crescimento da imagem)
* **Receita Ano 2:** R$ 844.235 (Crescimento de 150%)
* **Receita Ano 3:** R$ 1.519.623 (Crescimento de 80%)
* **Receita Ano 4:** R$ 2.279.434 (Crescimento de 50%)
* **Receita Ano 5:** R$ 3.191.208 (Crescimento de 40%)

**2. Premissa de Estrutura de Custos:**
Os custos estão alinhados entre a imagem e o plano detalhado. Usaremos os percentuais mais precisos do plano:

* **Custos Variáveis (CV): 35,5% sobre a Receita Bruta**
    * *Composição:* 10% (Impostos) + 15% (Marketing) + 7% (Servidor Escala) + 3,5% (Taxas Pagamento).
* **Custos Fixos (CF): R$ 180.000,00/ano**
    * *Composição:* R$ 15.000,00/mês (Salários, Encargos, Benefícios, Servidor Base, Licenças, Contabilidade, Depreciação).
    * *Correção:* Aplicamos um reajuste de **5% ao ano** sobre os custos fixos (inflação) para maior realismo na projeção.

**3. Premissa de Desconto e Perpetuidade:**

* **Taxa de Desconto (TMA): 25% ao ano.** Reflete o alto risco de uma startup de tecnologia no Brasil (competição, execução, mercado).
* **Crescimento na Perpetuidade (g): 6% ao ano.** Crescimento modesto e sustentável do negócio após o Ano 5.

---

## 2. Projeção de Fluxo de Caixa (Relatório Sintético Revisado)

Esta tabela simula o Fluxo de Caixa Livre (FCL) do Hospfy com base nas premissas revisadas (crescimento da imagem).

| Métrica | Ano 0 | Ano 1 | Ano 2 | Ano 3 | Ano 4 | Ano 5 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Receita Bruta (A)** | R$ 0 | R$ 337.694 | R$ 844.235 | R$ 1.519.623 | R$ 2.279.434 | R$ 3.191.208 |
| (-) Custos Variáveis (35.5% de A) | R$ 0 | (R$ 119.881) | (R$ 299.703) | (R$ 539.466) | (R$ 809.200) | (R$ 1.132.889) |
| (-) Custos Fixos (B) | R$ 0 | (R$ 180.000) | (R$ 189.000) | (R$ 198.450) | (R$ 208.373) | (R$ 218.791) |
| **Fluxo de Caixa Operacional (FCO)** | R$ 0 | **R$ 37.813** | **R$ 355.532** | **R$ 781.707** | **R$ 1.261.861** | **R$ 1.839.528** |
| | | | | | | |
| (-) Investimento Inicial (Capex) | (R$ 112.100) | - | - | - | - | - |
| (-) Reinvestimento (CAPEX) | - | (R$ 0) | (R$ 5.000) | (R$ 5.000) | (R$ 10.000) | (R$ 10.000) |
| **Fluxo de Caixa Livre (FCL)** | **(R$ 112.100)** | **R$ 37.813** | **R$ 350.532** | **R$ 776.707** | **R$ 1.251.861** | **R$ 1.829.528** |
| | | | | | | |
| **Valor Presente (VP) do FCL** (TMA=25%) | (R$ 112.100) | **R$ 30.250** | **R$ 224.340** | **R$ 397.683** | **R$ 512.658** | **R$ 599.467** |

---

## 3. Resultado Final: O Valor do Hospfy (Revisado)

O valor final é a soma dos Valores Presentes (VP) dos fluxos de caixa projetados (Anos 1-5) mais o Valor Presente da Perpetuidade (o valor da empresa do Ano 6 em diante).

#### 🔹 A. Cálculo da Perpetuidade
Valor da perpetuidade ao final do Ano 5 (FCL Ano 6 / (TMA - g)):
`R$ 1.829.528 * (1.06) / (0.25 - 0.06) = R$ 10.207.699`

#### 🔹 B. Valor Presente (VP) da Perpetuidade
Trazendo o valor da perpetuidade para o Ano 0 (descontando 5 anos a 25%):
`R$ 10.207.699 / (1.25)^5 = R$ 3.344.471`

#### 🔹 C. Valuation (Soma dos VPs)
Soma do VP do FCL (Anos 1-5) + VP da Perpetuidade:
`30.250 + 224.340 + 397.683 + 512.658 + 599.467 + 3.344.471`
**Valuation (Valor da Empresa) = R$ 5.108.869**

#### 🔹 D. VPL (Valor Presente Líquido)
O VPL subtrai o investimento inicial do valor total encontrado, indicando a viabilidade do projeto.
`VPL = R$ 5.108.869 (Valuation) - R$ 112.100 (Invest. Inicial)`
**VPL = R$ 4.996.769**

### Conclusão da Análise

Utilizando a projeção de receita acelerada fornecida na imagem (que indica um **break-even operacional já no Mês 5**), o projeto Hospfy demonstra um **Valuation estimado de R$ 5,1 milhões** e um VPL (Valor Presente Líquido) positivo de **R$ 4,99 milhões**.

**Observações Importantes:**

* **Validação da Reserva:** A projeção da imagem mostra um saldo acumulado negativo de R$ -26.889 em Abril. Isso valida a importância da **Reserva Financeira de R$ 90.000,00**, que cobre confortavelmente este período inicial de queima de caixa (runway).
* **Foco no Raciocínio:** Este valor é uma estimativa direta da projeção otimista de crescimento da equipe. A execução bem-sucedida desse crescimento é a premissa-chave para que este valor se realize.
