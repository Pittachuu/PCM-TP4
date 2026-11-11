# Dashboard das Eleições Legislativas 2025

Site: https://pittachuu.github.io/PCM-TP4/elections_dashboard_53912_53797/dashboard.html

## Autores

* **Eduardo Navalho** - 53797**

* **Gabriel Siopa - 53912**

## Instruções de Execução:

### Pré-requisitos

Para visualizar e compilar este dashboard, certifica-te de que tens instalado:

* [Quarto CLI](https://quarto.org/)

* Um navegador web (Chrome, Firefox, Edge, Safari)

### Como Compilar e Executar:

1. **Clonar/Transferir o repositório:**
   Garante que todos os ficheiros do projeto (incluindo o `.qmd` e a pasta `dados/`) estão na mesma diretoria.

2. **Renderizar o Dashboard:**
   Abre o terminal na pasta do projeto e executa o seguinte comando:

   ```
   quarto render dashboard.qmd
   
   ```

   *Alternativamente, se estiveres a utilizar o **RStudio** ou **VS Code**, basta clicar no botão **Render**.*

3. **Visualizar no Navegador:**
   Após a compilação, será gerado o ficheiro `dashboard.html`. Abre este ficheiro diretamente no teu navegador ou utiliza o comando preview do Quarto:

   ```
   quarto preview dashboard.qmd
   
   ```

## Descrição das Funcionalidades Implementadas:

### 1. Métricas Gerais (Coluna Esquerda)

* **Taxa de Abstenção:** 

* **Total de Inscritos:** 

* **Destaques Regionais:** 

### 2. Visualizações Cartográficas (Coluna Central)

* **Mapa Geral de Resultados:** 

* **Filtro Dinâmico por Partido:** 

### 3. Tabelas de Dados e Estatísticas (Coluna Direita)

* **Tabela de Votação por Partido:**

* **Tabela de Distribuição por Distrito:**
