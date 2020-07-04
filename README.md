# Systeme_dynamique
Mise en ligne sur jupyter notebook de systeme dynamique

Dans ce programme python sous jupyter notebook, on essaye d'analyser et automatiser un jeu simple de données. Cela consiste à
1) extraire des données, les grandeurs physiques importantes
qui pilotent la dynamique du sillage: notamment, il faut récupérer les gradients de pressions adimensionnées verticaux et horizontaux, car ils sont directement reliés aux 
coefficients de portance et de traînée.

2) effectuer une analyse spectrale des signaux d'intérêts pour récupérer les fréquences à l'origine du sillage: Notamment, il faudra se baser sur le facteur de forme qui 
permettra d'identifier les fréquences à l'origine des allées de Von Karmann. 

3) réaliser un portrait de phase pour caractériser le système dynamique (états stables, instables, cycles limites, etc.). Dans cette dernière étape, l'identification 
des fréquences est cruciale pour tracer (Cb(t), Cb(t-retard), Cf(t))

L'identification des fréquences ou encore, la compréhension de la topologie du système se fait de manière "manuelle". Le but consistera ensuite à voir comment, à partir du 
learning, faire pour que ça soit non pas l'homme mais la machine qui fasse ce travail. 


