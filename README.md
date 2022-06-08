# Tp_Kafka


1/ Kafka, les origines:
      En 2009, les équipes d'ingénieurs de LinkedIn ont eu pour mission d'entièrement réarchitecturer le système. Cela a commencé par un découpage en microservices de l'architecture monolithique historique, ce qui a d'abord permis une scalabilité plus aisée. Cette refonte a ensuite mené à la création d'un ensemble de services intermédiaires afin de fournir une API permettant d'accéder aux modèles de données et aux différentes bases de données.
      
      Afin de traquer les événements du site (pages vues, messages, etc.), ces équipes d'ingénieurs ont été amenées à développer un grand nombre de data pipelines maison pour leurs besoins, que ce soit en streaming, en queue ou en batch, ce qui leur a permis d'agréger les logs. Ces pipelines ont aussi été amenés à pouvoir supporter la montée en charge. Cependant, la maintenance d'un aussi grand nombre de systèmes différents rendait les pipelines difficiles à maintenir et à faire évoluer. Les équipes d'ingénieurs de LinkedIn ont donc fait le choix de créer une unique plateforme distribuée : Kafka est né.
      
2/ Concepts:
       Kafka a donc initialement été créé pour répondre aux importants besoins de LinkedIn et pour s'adapter au maximum à n'importe quel besoin. Kafka utilise le concept très connu du publish/subscribe, mais en s'appuyant sur le disque dur pour fonctionner. Il exploite également de nombreuses astuces de conceptions au plus bas niveau afin de devenir le broker le plus rapide du marché.

Afin d'introduire Kafka, nous commencerons par expliquer le principe du publish/subscribe pour ensuite nous intéresser à son implémentation dans Kafka en définissant les différentes briques du système. Nous verrons enfin quelles sont les optimisations internes permettant à ce message-broker d'aller aussi vite.

3/ Kafka:
  Dans le vocabulaire Kafka, on nomme :
     * Producer : tout système qui envoie des données dans un ou plusieurs topics Kafka. (Publisher dans pub-sub.) ;
     * Consumer : tout système qui lit des données dans un ou plusieurs topics Kafka. (Subscriber dans pub-sub.) ;
     * Broker : tout serveur Kafka ;
     * Cluster : ensemble de brokers.


Travaux Pratique:

Démarrage du Zookeper:

![image](https://user-images.githubusercontent.com/97621443/172690771-4f294966-fbe4-4441-a761-5c96e1737d1e.png)

Démarrage du Server Kafka:

![image](https://user-images.githubusercontent.com/97621443/172691136-913190c6-7272-4adb-8fcd-bdfdfc54ea88.png)

Démarrage (Kafka-Console-Producer & Kafka-Console-Consumer):

![image](https://user-images.githubusercontent.com/97621443/172691814-1863561a-fffb-4e08-9aff-059deb0a051b.png)


![image](https://user-images.githubusercontent.com/97621443/172692454-18356c6b-b2a1-49b5-8080-bd410778f672.png)










      
      
