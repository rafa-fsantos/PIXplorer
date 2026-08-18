# PIXplorer - Data Wrangling e Análise Exploratória de Transações PIX de 2025.

## 📝 Descrição do Projeto

O **PIX** é um sistema de pagamentos instantâneos do Banco Central do Brasil que viabiliza **transferências e liquidações em tempo real**, 24/7, por meio de chaves associadas a CPF, CNPJ, telefone, e‑mail, QR Code ou chave aleatória.

O projeto tem como foco a **análise exploratória** e o **Data Wrangling** de um dataset oficial do Banco Central contendo estatísticas operacionais do PIX, visando compreender padrões de uso, volume transacional e comportamento dos usuários.

## 🔍 Definição do Problema

### 🎯 Objetivo

Aplicar técnicas de **Data Wrangling** com o objetivo de **preparar, organizar e manipular** os dados do dataset afim de realizar uma análise exploratória que permita identificar e responder questões como:

1. **Distribuição regional** — Como variam o volume e o valor das transações PIX entre as regiões do pagador e do recebedor ao longo de 2025, e quais regiões concentram maior fluxo financeiro?

2. **Perfil etário** — Quais faixas de idade apresentam maior participação nas transações PIX, tanto em quantidade quanto em valor, e como isso muda mês a mês?

3. **Formas de iniciação** — Quais formas de iniciação (ex.: chave, QR Code, iniciação por instituição) são mais utilizadas e como elas influenciam o valor médio das transações?

4. **Natureza e finalidade** — Como diferentes naturezas e finalidades de transação se relacionam com o valor total movimentado e com o comportamento dos tipos de pessoa (PF vs PJ)?

5. **Comportamento temporal** — Quais padrões mensais surgem ao observar a evolução do valor e da quantidade de transações ao longo de 2025, e quais fatores podem explicar picos ou quedas?

### 🚀 Motivação

Compreender a dinâmica de uso do PIX — incluindo o volume e o valor das transações por região, bem como o perfil etário dos usuários — permite às instituições financeiras identificar **padrões comportamentais, lacunas de adoção e oportunidades de expansão** do sistema.

A análise das variações mensais de uso contribui para o **planejamento e a otimização de recursos tecnológicos**, garantindo maior eficiência operacional. Além disso, avaliar as formas predominantes de iniciação das transações possibilita entender **preferências dos usuários** e verificar se esses métodos influenciam o valor médio movimentado, apoiando decisões estratégicas sobre melhorias e incentivos ao uso.

### 🧩 Desafios
* **Compreensão inicial dos dados** — Examinar a estrutura, os tipos de variáveis, o contexto dos campos e identificar padrões gerais para familiarizar-se com o dataset.

* **Estruturação dos dados brutos** — Ajustar formatos, padronizar colunas, converter tipos (datas, categorias, numéricos) e preparar o dataset para operações posteriores.

* **Limpeza e tratamento** — Eliminar duplicidades, lidar com valores ausentes, corrigir inconsistências e garantir integridade básica dos dados.

* **Enriquecimento dos dados** — Criar novas variáveis úteis (ex.: faixas etárias, valores médios, indicadores regionais) ou integrar dados externos que ampliem o potencial analítico.

* **Validação da qualidade** — Avaliar coerência, detectar outliers, verificar relações esperadas entre variáveis e assegurar que o dataset esteja confiável para análise.

* **Disponibilização para análise** — Gerar a versão final do dataset tratada, documentada e pronta para ser utilizada em análises exploratórias, visualizações e modelagens.

### 🏁 Resultado Esperado

A análise exploratória deve gerar um panorama sobre o uso do PIX que possibilite a compreensão de:

* **Padrões regionais de uso** — Identificação das regiões com maior volume e valor de transações, revelando concentrações geográficas, assimetrias e oportunidades de expansão.

* **Perfil etário dos usuários** — Mapeamento das faixas etárias que mais utilizam o PIX, tanto em quantidade quanto em valor, destacando grupos com maior engajamento e segmentos com potencial de incentivo.

* **Comportamento temporal** — Detecção de padrões mensais, sazonalidades e variações significativas que auxiliem no planejamento de capacidade tecnológica e na gestão de recursos operacionais.

* **Preferências de iniciação** — Avaliação das formas mais utilizadas para iniciar transações (chave, QR Code, iniciação por instituição etc.) e análise de como essas escolhas influenciam o valor médio movimentado.

* **Relações entre variáveis* — Identificação de correlações relevantes entre tipo de pessoa, região, idade, finalidade e natureza da transação, revelando padrões comportamentais e operacionais.

* **Oportunidades estratégicas** — Síntese dos achados em recomendações que indiquem lacunas de adoção, segmentos subutilizados e caminhos para otimização do sistema e incentivo ao uso.

## ⚙️ Tecnologias e Ferramentas Utilizadas

* **Linguagem de Programação**: Python
* **Bibliotecas**:
  * Pandas (manipulação de dados);
  * Matplolib (visualização de dados)
* **Base de Dados**: Uso de dataset do Banco Central do Brasil sobre estatísticas de transações PIX do ano de 2025.

## 🔧 Como Funciona

### 1. Coleta de Dados:  
Os dados são extraídos da página de Dados Abertos do Banco Central do Brasil - Estatísticas PIX no endereço: [Banco Central - Estatísticas PIX](https://dadosabertos.bcb.gov.br/dataset/pix/resource/402d52fe-b37e-4483-80e4-eec3493f9b1d).

Os dados selecionados correspondem a 10.000 mil observações referente ao ano de 2025, amostra máxima possível de extrair do dataset.

### 2. Data Wrangling:
Preparação, organização e manipulação dos dados visando uma nova e mais adequada estruturação do dataset para extração de informações.

### 3. Análise Exploratória dos Dados:
Investigação dos dados para resumo das principais características pelo uso de estatística descritiva e gráficos para identificação de padrões, erros, outliers e entender relações entre as variáveis e responder as perguntas listadas nos objetivos.

### 4. Relatório:
Relatório analítico com os principais insigths e respostas as perguntas.

## 📂 Estrutura do projeto:
* dados/ : Contém os datasets utilizados no projeto.
* notebooks/ : Contém o notebook do projeto (Data Wrangling e Análise Exploratória).

## 📋 Como contribuir
1. Faça um fork do repositório.
2. Crie uma branch para a sua feature: git checkout -b minha-feature.
3. Commit suas alterações: git commit -m 'Adicionar nova feature'.
4. Submeta um pull request.

## 📜 Licença
Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar sugestões.