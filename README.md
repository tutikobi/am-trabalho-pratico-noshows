# am-trabalho-pratico-noshows
Este repositório contém o desenvolvimento do trabalho prático da disciplina de Aprendizado de Máquina, focado na predição e prescrição de absenteísmo em consultas médicas (no-shows).

🚀 Sobre o Projeto
O objetivo deste trabalho é ir além da classificação binária convencional. Desenvolvemos um motor analítico híbrido que combina:

Engenharia de Atributos: Criação da variável de latência WaitTime.

Aprendizado Não-Supervisionado: Utilização de K-Means para segmentação de fenótipos de pacientes.

Modelo Preditivo: XGBoost configurado com pesos para lidar com o desbalanceamento da base (80% comparecimento / 20% falta).

IA Explicável (XAI): Aplicação de valores SHAP para interpretação das decisões do modelo.

Analítica Prescritiva: Motor de regras para automatização de intervenções (alertas de risco para fluxos de comunicação via n8n ou call center).

📂 Estrutura do Repositório
/notebooks: Contém o ficheiro 02_modelagem_avancada.ipynb, com todo o pipeline de treino e avaliação.

/assets: Contém as evidências visuais (gráficos de perfis e de impacto SHAP) utilizadas no artigo.

/Artigos_PubMed: Base bibliográfica selecionada para fundamentação teórica.

🛠️ Como Reproduzir
Carregue o arquivo 02_modelagem_avancada.ipynb no Google Colab.

Certifique-se de que o ficheiro de dados archive.zip (Kaggle) está no ambiente (/content/archive.zip).

Execute todas as células sequencialmente. O código tratará automaticamente a extração, limpeza, modelagem e geração das visualizações em /assets.
