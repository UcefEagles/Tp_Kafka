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


Projet Sur Intellij:

![image](https://user-images.githubusercontent.com/97621443/172692807-a49ef5a4-1ee5-494b-9b2e-3d4b55ebc629.png)


Le fichier app.properties:

![image](https://user-images.githubusercontent.com/97621443/172692984-5494858c-a00a-46c9-931d-0013ee7b11c5.png)


Test  (Kafka -Console-Consumer:):

![image](https://user-images.githubusercontent.com/97621443/172693804-1824494f-d513-496a-8e41-af3b59691089.png)

![image](https://user-images.githubusercontent.com/97621443/172693975-071928fc-ba93-4276-be8b-c223482bc6b4.png)

![image](https://user-images.githubusercontent.com/97621443/172695068-cb8e75b0-0d32-4527-a347-655f20187e30.png)

Test  (Kafka -Console-Producer):

![image](https://user-images.githubusercontent.com/97621443/172695847-4f4873d4-8e4d-42ed-8af9-2ed76e0d59a9.png)



![image](https://user-images.githubusercontent.com/97621443/172696404-350589a3-1705-4949-80ed-b8e4384374e1.png)


![image](https://user-images.githubusercontent.com/97621443/172696703-5dea48b1-4bf7-4574-ba39-bfc9d841b9e1.png)


![image](https://user-images.githubusercontent.com/97621443/172696829-e98ba38c-f990-4ba8-8eb2-5e5533702733.png)





Real Time Data Analytics en mode Stream Processing  utilisant KAFKA Streams qui permet de traiter en temps réel les messages du Topic :

![image](https://user-images.githubusercontent.com/97621443/172965281-74f15288-516e-4aa3-92b4-27c5c3796079.png)




![image](https://user-images.githubusercontent.com/97621443/172965346-0d3e453c-8460-41cf-9219-b27fec5cf930.png)


![image](https://user-images.githubusercontent.com/97621443/172965653-508d980d-5a92-44cc-972b-4d2c69dfbc1f.png)

Presentation graphique avec Canvas et JS:


![image](https://user-images.githubusercontent.com/97621443/172966722-4d94fb58-5443-4609-8dda-390617fc59ca.png)














      
      
