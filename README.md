# Machine learning soccer classification
 Using machine learning to classify soccer matches results
 
> ## About The Project

I am a soccer lover so I decided to start a project using programming to try to predic with classification the results of soccer matches of Campeonato Brasileiro de Futebol Série A, which is a running point championship with 38 rounds and 20 teams and a very hard one with 7 different winners in the past 18 years.
* This project was developed for the subject Introdução ao aprendizado de máquina e à mineração de dados (PO450) offered by the college Unicamp.
> ## Built With

Python in Jupyter Notebook

I decided to try different machine learning approaches to compare the results, so i used logistic regression, decision tree, random forest and MLP.
To get the data to train and to test my machine learning models I did web scraping from the site WorldFootball.net.

> ## Features and scores

![image](https://user-images.githubusercontent.com/88220952/128444457-9269b06a-1cf5-44bc-ac9c-fc7e35a218d9.png)

> ## Data for training and testing

train = 70% of data and test = 30%

> ## The weight of playing home

![image](https://user-images.githubusercontent.com/88220952/128444673-555d8b3a-d7ad-4c78-b4a9-52527ff2f742.png)

Total de jogos:  3040

Total de jogos ganhos em casa:  1507

Total de jogos ganhos pelo visitante:  728

Total de jogos empatados:  805

Percentual de jogos ganhos em casa: 49.57%

Percentual de jogos perdidos em casa: 23.95%

Percentual de jogos empatados: 26.48%

> ## The difficulty of the problem

There are three possible results for a soccer match in Campeonato Brasileiro: win, draw or defeat 

![image](https://user-images.githubusercontent.com/88220952/128444718-9abd5004-559e-4e5b-807d-5cdcfd95ed5f.png)

> ## Results

![image](https://user-images.githubusercontent.com/88220952/128444616-36be39cf-ec7c-4cd2-9729-5055690a6544.png)

For the year of 2020 the models predicted the final table of the championship as:

![image](https://user-images.githubusercontent.com/88220952/128445123-c8f578ab-be9d-4046-b41a-d29ff2ef729a.png)

Considering only win or defeat:

MLP -> Accuracy: 0.796

Logistic regression -> Accuracy: 0.773
