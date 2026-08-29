# Aspect and Opinion Based Sentiment Analysis (AOBSA)
## Panoramica
Il progetto è stato sviluppato con l'obiettivo di studiare separatamente le principali componenti di una pipeline di analisi del sentiment basata sugli aspetti, confrontando più strategie per Aspect Term Extraction (ATE) e Opinion Term Extraction (OTE) prima di integrare i metodi migliori in una pipeline finale. Per l'ATE sono state confrontate architetture RNN, LSTM e BiLSTM, sia con embedding appresi casualmente sia con embedding GloVe pre-addestrati. Per l'OTE sono stati confrontati un metodo basato principalmente sul POS tagging ed un metodo basato sulle dipendenze sintattiche (Dependency Parsing). La pipeline finale è stata inizialmente valutata su un gold standard creato manualmente a partire da recensioni di ristoranti appartenenti al test set, di seguito è stata svolta una seconda valutazione su un gold standard creato, nuovamente, a mano di recensioni appartenenti al dominio dei laptop: in questa maniera si è potuta analizzare l’efficenza della pipeline su un dominio differente.
## Dataset
Il dataset è reperibile al seguente [link](https://www.kaggle.com/datasets/charitarth/semeval-2014-task-4-aspectbasedsentimentanalysis?select=Restaurants_Train_v2.csv)
## Relazione
Il progetto presentato è descritto nella seguente [relazione](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/Aspect%20and%20Opinion-Based%20Sentiment%20Analysis%20Pipeline.pdf)
<br>
The report is also available in English at the following [link](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/Aspect%20and%20Opinion-Based%20Sentiment%20Analysis%20Pipeline%20-%20English.pdf)
## Codice
- Codice Aspect Term Extraction (ATE): [Link](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/ATE_Restaurant.ipynb)
- Codice Opinion Term Extraction (OTE): [Link](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/OTE_Restaurant.ipynb)
- Codice della Pipeline finale: [Link](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/Final_ATE_OTE.ipynb)
## File CSV di supporto
- Gold Standard per il dataset dei ristoranti: [gold_standard_restaurants](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/gold_standard_restaurants.csv)
- Gold Standard per il dataset dei laptop: [gold_standard_laptops](https://github.com/DaniNar2/Aspect-Based-Sentiment-Analysis/blob/main/gold_standard_laptops.csv)
## Autore
- Daniela Nardone
