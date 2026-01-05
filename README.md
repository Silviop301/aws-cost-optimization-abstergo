# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

[cite_start]**Data:** 05/01/2026 [cite: 4]
[cite_start]**Empresa:** Abstergo Industries [cite: 1]
**Responsável:** Silvio Pinheiro

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Silvio Pinheiro. [cite_start]O objetivo do projeto foi elencar serviços AWS para otimização de infraestrutura na região de São Paulo[cite: 9], focando na redução de custos e eficiência operacional.

## Descrição do Projeto
[cite_start]O projeto de implementação foi baseado em uma estimativa detalhada de custos para serviços de armazenamento e computação[cite: 8]. As etapas foram divididas conforme descrito abaixo:

**Etapa 1:**
- [cite_start]**Nome da ferramenta:** Amazon Simple Storage Service (S3) [cite: 9]
- [cite_start]**Foco da ferramenta:** Armazenamento de objetos com gerenciamento inteligente de camadas[cite: 12].
- [cite_start]**Descrição de caso de uso:** Armazenamento de 500 GB por mês utilizando a classe S3 Intelligent-Tiering (INT)[cite: 12]. [cite_start]A configuração foca em objetos com tamanho médio de 16 MB para otimizar o custo de transição entre níveis de acesso[cite: 12].
- [cite_start]**Custo Mensal:** 20,33 USD[cite: 9].

**Etapa 2:**
- [cite_start]**Nome da ferramenta:** Amazon EC2 [cite: 13]
- **Foco da ferramenta:** Instâncias de computação de baixo custo e alta eficiência.
- [cite_start]**Descrição de caso de uso:** Utilização de instâncias t4g.nano (arquitetura baseada em ARM/Graviton) com sistema operacional Linux[cite: 21]. [cite_start]A estratégia de preço adotada foi o "Compute Savings Plans" de 3 anos sem pagamento inicial, garantindo o menor custo possível para cargas de trabalho constantes[cite: 21].
- [cite_start]**Custo Mensal:** 3,86 USD[cite: 17].

**Etapa 3:**
- [cite_start]**Nome da ferramenta:** AWS Pricing Calculator (Consolidação) [cite: 23]
- **Foco da ferramenta:** Planejamento financeiro e previsão de gastos.
- [cite_start]**Descrição de caso de uso:** Consolidação de todos os serviços na região South America (Sao Paulo) para garantir baixa latência e conformidade regional[cite: 9, 15, 18]. [cite_start]O custo total mensal da operação foi calculado em 24,19 USD[cite: 7].

## Conclusão
[cite_start]A implementação de ferramentas na empresa Abstergo Industries tem como esperado um custo total de 290,28 USD ao final de 12 meses[cite: 7], o que aumentará a eficiência e a produtividade da empresa através de serviços gerenciados e instâncias otimizadas. [cite_start]A adoção do S3 Intelligent-Tiering e do Savings Plans no EC2 garante que a empresa pague apenas pelo que utiliza com o melhor desconto disponível[cite: 12, 21].

## Anexos

* [cite_start]**URL da Estimativa:** https://calculator.aws/#/estimate?id=07f5cacf2d60d36d1740ca1bda23d1ebaab0f27d [cite: 5]
* [cite_start]**Relatório de Exportação:** My Estimate - Calculadora de Preços da AWS.pdf [cite: 4]

Assinatura do Responsável pelo Projeto:

**Silvio Pinheiro**
