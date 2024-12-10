# Q1 : Quels sont  les avantages de Gitpod ?
Réponse: 
Environnements prêts à l'emploi
Automatisation des tâches
Intégration facile avec GitHub

# Q2 : Quels sont les défauts de Gitpod ?
Réponse:
Avoir connexion internet stable
Version gratuite limitée

# Q3 : Quelle est la taille du fichier jar `api-springboot-0.0.1-SNAPSHOT.jar` ?
Réponse: 19M

# Q4 : Qu'est ce que  la RSS ?
Réponse: RSS = mémoire physique utilisée par un processus en temps réel

# Q5 : Quelle est la valeur de la RSS utilisée par l'api SpringBoot (Préciser l'unité)?
Réponse: RSS = 313 220 KB
gitpod /workspace/miage-numres-step1 (main) $ ps -e -o pid,rss,args | grep api-springboo
  22462 313220 java -jar api-springboot/target/api-springboot-0.0.1-SNAPSHOT.jar
  22646  2308 grep --color=auto api-springboo

# Q6 : Quel est le temps de démarrage l'api SpringBoot ?
Réponse: 1.791
Started ApiSpringbootApplication in 1.791 seconds (process running for 2.157)

# Q7 : Quelle est la taille du fichier jar `quarkus-run.jar` ?
Réponse: 694KB
-rw-r--r-- 1 gitpod gitpod 694 Dec 10 21:47 api-quarkus/target/quarkus-app/quarkus-run.jar


# Q8 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode JVM (Préciser l'unité)?
Réponse: RSS = 109 892 KB
ps -e -o pid,rss,args | grep quarkus-run
  36459 109892 java -jar api-quarkus/target/quarkus-app/quarkus-run.jar
  37968  2296 grep --color=auto quarkus-run


# Q9 : Quel est le temps de démarrage l'api Quarkus en mode JVM ?
Réponse: 0.791s
api-quarkus 1.0.0-SNAPSHOT on JVM (powered by Quarkus 3.16.3) started in 0.791s. Listening on: http://0.0.0.0:8080


# Q10 : Quelle est la valeur de la RSS utilisée par l'api quarkus en mode natif (Préciser l'unité)?
Réponse: RSS = 36 636 KB
ps -e -o pid,rss,args | grep runner
  43445 38636 ./api-quarkus/target/api-quarkus-1.0.0-SNAPSHOT-runner
  43632  2220 grep --color=auto runner


# Q11 : Quel est le temps de démarrage l'api Quarkus en mode natif ?
Réponse: 0.016s
api-quarkus 1.0.0-SNAPSHOT native (powered by Quarkus 3.16.3) started in 0.016s. Listening on: http://0.0.0.0:8080