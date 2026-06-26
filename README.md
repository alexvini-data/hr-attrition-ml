# HR Attrition Prediction — TechCorp Brasil

## Sobre o projeto
Pipeline completo de Machine Learning para prever rotatividade de funcionários.
Desenvolvido como trabalho de conclusão da disciplina Data Science Experience — MBA Data & Analytics, Mackenzie.

## Resultados principais
- Melhor modelo: LightGBM (ROC-AUC: 0,782)
- Threshold ótimo: 0,25 (detecta 56,6% dos funcionários em risco)
- Features criadas: 11 novas variáveis com justificativa de negócio
- Balanceamento: SMOTE (16% → 50% classe minoritária)

## Estrutura do repositório
- `notebooks/` — pipeline completo comentado
- `images/` — visualizações geradas

## Como executar
1. Importe o notebook no Databricks Community Edition
2. Execute todas as células na ordem
3. As bibliotecas são instaladas automaticamente via %pip install

## Bibliotecas utilizadas
Ver `requirements.txt`
