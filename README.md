# tests_ia_agentique

## 01_wtht_frmwrk.ipynb 
- Pas d’utilisation de framework -> python pur
- Les outils sont des fonctions - pas d’appels à des API externes
- Chat avec utilisation de gradio 

## 02_wtht_frmwrk.ipynb
- Pas d’utilisation de framework -> python pur
- Outil avec appel d’APIs – pas possible depuis InnoLab 
- Chat avec utilisation de gradio 

## 03_wth_openai_frmwrk.ipynb
- Utilisation du framework OpenAI SDK - pas possible depuis InnoLab
- Remarque : dans Colab installer le OpenAI SDK (!pip install openai-agents)
- Les outils sont des fonctions (pas d'appels API) transformées en outils grâce au décorateur @function_tool
- Chat en ligne de commande ou avec utilisation de gradio 

