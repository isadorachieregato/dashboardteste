# Pokémon Data Analysis Dashboard

![Dashboard Preview](./screenshot.png)

Um painel interativo para análise de dados de Pokémon a partir de arquivos CSV, com visualizações dinâmicas e filtros personalizáveis.

## ✨ Funcionalidades

### 📂 Processamento de arquivos CSV
- Carrega e analisa conjuntos de dados de Pokémon usando PapaParse
- Suporte para arquivos com colunas como Name, Type1, Type2 e Evolution

### 🔍 Filtros dinâmicos
- Filtra por tipo de Pokémon (primário ou secundário)
- Busca Pokémon por nome
- Interface intuitiva para aplicação de filtros

### 📊 Visualizações interativas
- Gráfico de barras da distribuição por tipos
- Gráfico de pizza dos estágios evolutivos
- Tooltips interativos com detalhes

### 📱 Design responsivo
- Layout adaptável para desktop e dispositivos móveis
- Experiência de usuário otimizada para todos os tamanhos de tela

### 🎨 Interface moderna
- Gradientes CSS atraentes
- Animações suaves e transições
- Layout limpo e intuitivo

## 🛠️ Tecnologias Utilizadas

**Frontend:**
- HTML5
- CSS3
- JavaScript Vanilla

**Bibliotecas:**
- [Chart.js](https://www.chartjs.org/) - para visualização de dados
- [PapaParse](https://www.papaparse.com/) - para análise de CSV

**Estilização:**
- Gradientes CSS
- Efeitos de sombra
- Layout responsivo com Flexbox/Grid
- Animações CSS

## 📊 Análise de Dados

O painel oferece duas visualizações principais:

### 1. Distribuição por Tipos
![Gráfico de Tipos](./types-chart.png)
- Mostra a frequência de todos os tipos de Pokémon
- Gráfico de barras interativo
- Atualização dinâmica com filtros

### 2. Estágios Evolutivos
![Gráfico de Evolução](./evolution-chart.png)
- Classificação em 4 categorias evolutivas
- Gráfico de pizza colorido
- Legenda interativa

## 🚀 Como Usar

### Pré-requisitos
- Navegador moderno (Chrome, Firefox, Edge)
- Arquivo CSV com dados de Pokémon

### Passo a Passo
1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/pokemon-dashboard.git
```html
Abra o arquivo index.html no seu navegador preferido
1. Clique no botão "Escolher arquivo"
2. Navegue até a pasta contendo seu arquivo pokemon.csv
3. Selecione o arquivo e clique em "Abrir"
