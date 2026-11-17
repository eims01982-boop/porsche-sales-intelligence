# porsche-sales-intelligence
Dashboard interativa de análise de vendas Porsche, com indicadores estratégicos, gráficos dinâmicos e insights por modelo, estado e cidade, desenvolvida em HTML, CSS e JavaScript.
# Porsche Sales Intelligence 🚗

### Dashboard Interativa de Análise de Vendas

Este projeto foi desenvolvido com o objetivo de analisar dados de vendas de veículos Porsche por meio de uma dashboard interativa, utilizando HTML, CSS e JavaScript, com auxílio do ChatGPT.

A interface foi inspirada no site oficial da Porsche Brasil, combinando uma identidade visual elegante com gráficos e indicadores semelhantes aos utilizados no Power BI.

O projeto é acadêmico e independente, sem vínculo oficial com a Porsche.

## 1. Objetivo do projeto

Transformar dados de uma planilha Excel em informações visuais que facilitem a compreensão do desempenho comercial, permitindo identificar tendências de vendas, preferências dos consumidores e diferenças entre regiões.

A dashboard foi organizada em três painéis:

- **Estratégico:** indicadores gerais de desempenho e resultados comerciais.
- **Analítico:** análise detalhada por modelo, ano, cidade, estado e pagamento.
- **Popularidade:** identificação dos modelos mais vendidos e das preferências por cidade.

## 2. Perguntas de negócio

**Quais estados apresentam o maior número de vendas?**

Essa pergunta foi escolhida para identificar as regiões com maior concentração de vendas e compreender a distribuição geográfica dos resultados.

**Qual modelo Porsche foi o mais vendido?**

O objetivo é identificar os modelos com maior procura, contribuindo para a análise de preferências e desempenho comercial.

**Quais modelos são mais populares em cada cidade?**

Essa análise permite observar diferenças entre os mercados locais e identificar oportunidades comerciais específicas.

**Como variam o faturamento, a quantidade de vendas e o ticket médio?**

Esses indicadores permitem avaliar o desempenho das vendas e comparar os resultados utilizando diferentes filtros.

## 3. Desenvolvimento com Inteligência Artificial

O ChatGPT foi utilizado para auxiliar na criação da dashboard, organização dos indicadores, desenvolvimento do código e melhoria da interface.

### Prompt inicial

"Utilizando os recursos de Canvas, renderize uma dashboard em HTML com filtros de modelo Porsche, model year, city, states e pay method.

A dashboard deverá responder quais estados possuem mais vendas, qual modelo Porsche foi mais vendido e quais veículos são mais populares em cada cidade.

Crie três painéis: analítico, estratégico e popular.

A interface deverá ser inspirada no site oficial da Porsche Brasil, com aparência elegante, organizada, inovadora e gráficos semelhantes aos utilizados no Power BI."

### Alteração solicitada

Após a primeira versão, foi solicitado:

"Quero gráficos redondos mostrando os estados com mais vendas."

### Resultado da alteração

Foi incluído um gráfico de rosca (donut), permitindo visualizar a participação dos estados no total de vendas, com valores e percentuais.

Essa melhoria tornou a comparação entre os estados mais visual e intuitiva.

## 4. Tratamento e preparação dos dados

A base original foi disponibilizada em uma planilha Excel e precisou ser preparada para sua utilização na dashboard.

Foram realizados os seguintes procedimentos:

- Seleção de 100 registros da aba `Sanitized`.
- Organização dos campos utilizados nas análises.
- Padronização das informações para utilização no código.
- Conversão dos dados para uma estrutura compatível com JavaScript.
- Exclusão de informações pessoais de clientes e vendedores do HTML público.
- Preservação de um valor de data inválido, sem substituí-lo por uma informação fictícia.

A base utilizada contém informações de vendas nos Estados Unidos, com valores expressos em dólares americanos (USD).

## 5. Ferramentas utilizadas

- **ChatGPT:** apoio na geração do código, desenvolvimento da dashboard e melhorias visuais.
- **HTML:** estrutura da página.
- **CSS:** identidade visual e organização dos elementos.
- **JavaScript:** interatividade, filtros e atualização dos indicadores.
- **Excel:** origem e organização dos dados.
- **GitHub:** armazenamento público do projeto.
- **GitHub Pages:** publicação gratuita da dashboard.

O projeto foi desenvolvido com auxílio do ChatGPT, sem utilização do editor Canvas como ambiente de edição e sem um agente externo com skill específica.

A escolha do HTML, CSS e JavaScript permitiu criar uma página que pode ser acessada diretamente pelo navegador, sem necessidade de instalar o Power BI.

## 6. Funcionalidades

A dashboard possui cinco filtros interativos:

1. Modelo Porsche
2. Ano do modelo
3. Cidade
4. Estado
5. Forma de pagamento

Os filtros permitem explorar os resultados e comparar diferentes grupos de vendas.

Também foram desenvolvidos indicadores de faturamento, quantidade de vendas, ticket médio e modelo líder, além de gráficos de distribuição e rankings.

## 7. Principais resultados

Na base acadêmica de 100 registros, os estados com maior quantidade de vendas foram:

- Califórnia (CA): 16 vendas.
- Texas (TX): 14 vendas.
- Arizona (AZ): 7 vendas.

O modelo mais frequente foi o Cayenne Coupe, com 4 vendas.

Esses resultados representam exclusivamente os dados utilizados no projeto, não correspondendo às estatísticas oficiais da Porsche.

## 8. Acesso ao projeto

**Dashboard publicada:**

https://eims01982-boop.github.io/porsche-sales-intelligence/

**Repositório GitHub:**

https://github.com/eims01982-boop/porsche-sales-intelligence

## 9. Evidências de funcionamento

Nesta seção serão adicionadas capturas de tela reais da dashboard publicada, incluindo:

- Visão geral dos indicadores e gráficos.
- Exemplo de filtro aplicado, demonstrando a atualização dos resultados.

## 10. Considerações finais

O desenvolvimento deste projeto permitiu aplicar conhecimentos relacionados à análise de dados, indicadores de desempenho e visualização de informações.

A utilização da inteligência artificial contribuiu para transformar uma base de dados em uma ferramenta interativa, permitindo explorar informações comerciais de maneira mais clara e organizada.

Além da criação dos gráficos, o projeto demonstrou a importância de selecionar perguntas de negócio relevantes, preparar os dados e realizar melhorias na apresentação dos resultados.

A publicação no GitHub Pages também possibilitou disponibilizar o projeto de forma pública, contribuindo para a construção de um portfólio de análise de dados.
