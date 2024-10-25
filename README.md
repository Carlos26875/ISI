# Trabalho Prático - Análise de Automoveis


- **Aluno:** Carlos Moreda
- **Número:** 26875
- **Unidade Curricular:** Integração de Sistemas de Informação
- **Curso:** Licenciatura em Engenharia de Sistemas Informáticos - Pós Laboral

## Descrição do Projeto

Este projeto utiliza a ferramenta KNIME para realizar processos de **ETL** com o objetivo de integrar e analisar dados relacionados a automóveis. O foco está na comparação entre veículos, permitindo uma análise  de características como marca, modelo, potência, tipo de combustível, consumo, entre outros fatores.

O projeto está inserido no contexto da unidade curricular de **Integração de Sistemas de Informação (ISI)**, sendo orientado para explorar o processo ETL.

## Objetivos

- **Extração** de dados provenientes de diferentes fontes, como ficheiros CSV e API JSON.
- **Transformação** de dados através de operações como categorização de combustível, normalização de valores e geração de logs.
- **Carregamento** dos dados transformados, prontos para visualização e análises futuras.
- Implementação de **Jobs automatizados** para otimizar o processo de análise e processamento.


## Ferramentas Utilizadas


- **KNIME**: Ferramenta principal para realizar os processos de ETL.
- **API JSON**: Utilizada para extração de dados de automóveis
- **JSON/CSV**: Formatos utilizados para importação e exportação de dados.


## Estrutura do Projeto

1. **Leitura de Dados**
   - Leitura de dados através de Get Request e JSON Path
   - Leitura de ficheiros CSV e integração com dados obtidos

2. **Processamento de Dados**
   - Conversão de JSON para Tabela
   - Agrupamento e junção de informações

3. **Tratamento e Normalização**
   - Manipulação de strings e cálculo de custos
   - Aplicação de regras para categorização de veículos
   - Geração de logs categorizados

4. **Carregamento de Dados**
   - Preparação de dados para utilização em relatórios e análises

## Conclusão

Este projeto demonstra como a integração de dados pode ser otimizada com processos ETL. A transformação e a normalização  permitem uma análise robusta e precisa. Em projetos futuros, a implementação eficaz de ETL será fundamental para garantir a integridade e qualidade dos dados.

git clone https://github.com/Carlos26875/ISI
