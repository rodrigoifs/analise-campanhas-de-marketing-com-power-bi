# 📊 Projeto: Análise de Campanhas de Marketing com Power BI

## 📋 Descrição do Projeto
Este projeto consiste no desenvolvimento de um dashboard interativo no Power BI focado na **Visão do Cliente** e na performance de **Campanhas de Marketing**. O objetivo principal é transformar dados brutos socioeconômicos e de consumo em insights estratégicos para apoiar tomadas de decisão rápidas da diretoria.

O painel foi desenvolvido como um estudo de caso prático (Mini-Projeto) durante a minha formação na **Data Science Academy (DSA)**, aplicando técnicas de Business Intelligence e engenharia de dados.

---

## 🎯 Desafio de Negócio
A equipe de marketing de uma empresa global precisava compreender profundamente o perfil do seu cliente ativo e como os hábitos de consumo impactam os diferentes canais de venda (Lojas Físicas, Web e Catálogo). 

O desafio era tratar uma base de dados complexa e criar um painel dinâmico que permitisse responder de forma rápida:
* Qual o perfil de escolaridade e estado civil do nosso maior volume de clientes?
* Qual a média salarial anual do público consumidor?
* Como as compras com desconto se comparam com as vendas regulares nos canais digitais e físicos?

---

## 🛠️ Tecnologias e Ferramentas (Stack)
* **Power BI Desktop:** Construção do layout, cartões de KPI, gráficos interativos e design.
* **Power Query (ETL):** Extração, limpeza, transformação e tipagem correta dos dados brutos.
* **Linguagem DAX:** Desenvolvimento de cálculos personalizados e métricas de performance corporativa.

---

## ⚙️ Processo de Desenvolvimento (Ações Executadas)

### 1. Extração e Tratamento de Dados (ETL)
Os dados originais passaram por um processo rigoroso de higienização dentro do **Power Query**, garantindo a integridade das análises:
* Eliminação de registros duplicados e tratamento de valores nulos.
* Padronização e tipagem de colunas (textos, números e valores monetários).
* Estruturação de variáveis socioeconômicas chaves, como Grau de Escolaridade (*Curso Superior, Mestrado, Doutorado*) e Estado Civil (*Solteiro, Casado, Divorciado*).

### 2. Criação de Métricas com Linguagem DAX
Para alimentar os cartões de performance de forma dinâmica, foram desenvolvidas medidas personalizadas utilizando as melhores práticas de **DAX**:
* **Volumetria Total:** Cálculo do número de clientes únicos ativos na base (`1.999` clientes).
* **Análise de Renda:** Média salarial anual do público consumidor (`51,98 Mil`).
* **Métricas de Canais:** Totalização de transações em Lojas Físicas (`12 Mil`), Web (`8.147`) e Catálogo (`5.270`).
* **Indicadores Promocionais:** Totalização de compras realizadas com cupons de desconto (`4.661`).

### 3. Design de Dashboard e Experiência do Usuário (UX)
O painel foi desenhado priorizando o conceito de *Data Storytelling* e a facilidade de leitura:
* **Filtros Segmentados por País:** Botões interativos que permitem filtrar instantaneamente os dados por mercados locais (*Brasil, Argentina, Alemanha, Chile, Espanha, Estados Unidos e Portugal*).
* **Gráficos de Barras Limpos:** Exibição clara e sem ruídos visuais da distribuição demográfica do público.
* **Navegação por Abas:** Estrutura modular organizada em páginas dedicadas (*Visão Cliente, Visão Comportamento, Visão Campanhas e Visão Pontos de Venda*).

---

## 📈 Insights e Resultados Obtidos
A análise visual trouxe dados cruciais para o direcionamento de verbas de marketing:
* **Foco no Público Universitário:** O relatório revelou que clientes com *Curso Superior* formam o maior grupo da base, seguidos por profissionais com *Doutorado*.
* **Perfil Familiar:** Clientes *Solteiros* lideram o volume de interações na base de dados analisada, seguidos de perto por pessoas *Casadas*.
* **Força das Lojas Físicas:** Embora o canal digital (Web) seja representativo, as lojas físicas ainda concentram o maior volume de transações (`12 Mil`), mostrando que estratégias *Omnichannel* (como comprar online e retirar na loja) possuem enorme potencial de conversão.

Com esses indicadores, a diretoria pode personalizar anúncios específicos para canais digitais focando no público de maior escolaridade, otimizando o Retorno sobre o Investimento (ROI) das campanhas.

---

## 📷 Visualização do Painel

Abaixo está o registro visual da página principal desenvolvida:

![Visão Cliente - Dashboard de Marketing]( https://raw.githubusercontent.com/rodrigoifs/analise-campanhas-de-marketing-com-power-bi/refs/heads/main/imagens/dashboard-analise-campanhas-de-marketing-visao-cliente.png)
