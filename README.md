# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 05/01/2026 
**Empresa:** Abstergo Industries 
**Responsável:** Silvio Pinheiro

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Silvio Pinheiro. O objetivo do projeto foi elencar serviços AWS para otimização de infraestrutura na região de São Paulo, focando na redução de custos e eficiência operacional.

## Descrição do Projeto
O projeto de implementação foi baseado em uma estimativa detalhada de custos para serviços de armazenamento e computação. As etapas foram divididas conforme descrito abaixo:

**Etapa 1:**
- **Nome da ferramenta:** Amazon Simple Storage Service (S3).
- **Foco da ferramenta:** Armazenamento de objetos com gerenciamento inteligente de camadas.
- **Descrição de caso de uso:** Armazenamento de 500 GB por mês utilizando a classe S3 Intelligent-Tiering (INT). A configuração foca em objetos com tamanho médio de 16 MB para otimizar o custo de transição entre níveis de acesso.
- **Custo Mensal:** 20,33 USD

**Etapa 2:**
- **Nome da ferramenta:** Amazon EC2.
- **Foco da ferramenta:** Instâncias de computação de baixo custo e alta eficiência.
- **Descrição de caso de uso:** Utilização de instâncias t4g.nano (arquitetura baseada em ARM/Graviton) com sistema operacional Linux. A estratégia de preço adotada foi o "Compute Savings Plans" de 3 anos sem pagamento inicial, garantindo o menor custo possível para cargas de trabalho constantes.
- **Custo Mensal:** 3,86 USD.

**Etapa 3:**
- **Nome da ferramenta:** AWS Pricing Calculator (Consolidação).
- **Foco da ferramenta:** Planejamento financeiro e previsão de gastos.
- **Descrição de caso de uso:** Consolidação de todos os serviços na região South America (Sao Paulo) para garantir baixa latência e conformidade regional. O custo total mensal da operação foi calculado em 24,19 USD.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado um custo total de 290,28 USD ao final de 12 meses, o que aumentará a eficiência e a produtividade da empresa através de serviços gerenciados e instâncias otimizadas. A adoção do S3 Intelligent-Tiering e do Savings Plans no EC2 garante que a empresa pague apenas pelo que utiliza com o melhor desconto disponível.

## Anexos

* **URL da Estimativa:** https://calculator.aws/#/estimate?id=07f5cacf2d60d36d1740ca1bda23d1ebaab0f27d
* **Relatório de Exportação:** My Estimate - Calculadora de Preços da AWS.pdf

Assinatura do Responsável pelo Projeto:

**Silvio Pinheiro**
