#  Rendu projet docker 09/11/2023 
#### Lecornet Killian 
##### Crespo Matthias 
#### M2 Info 
```bash
# Aller dans chaque dossier pour creer un dockerfile et coller les exemples données 
cd worker
nano Dockerfile

cd vote
nano Dockerfile

cd seed-data
nano Dockerfile

cd result
nano Dockerfile
```
#### Création du docker-compose.build.yml

![image](https://github.com/crespo742/docker_test/assets/56248842/313313f9-dee1-4c0f-8637-26fabe01901c)

#### executer la commande : 

```bash

docker compose -f docker-compose.build.yml build

```

#### nous avons ceci comme résultat

![image](https://github.com/crespo742/docker_test/assets/56248842/2b73f358-9809-45a5-91cd-8e1c59e0512d)

#### on tag les images dans le registre

![image](https://github.com/crespo742/docker_test/assets/56248842/b6ccd38c-b7d8-45e9-a670-84916ae4f86b)
![image](https://github.com/crespo742/docker_test/assets/56248842/4e0ae80c-3dae-4794-a3fe-6aaceabe580c)
![image](https://github.com/crespo742/docker_test/assets/56248842/f51dc227-057f-44f5-86dc-815960d471f0)
![image](https://github.com/crespo742/docker_test/assets/56248842/40a7023a-de06-4d60-b907-0b83f44635e4)

#### Pour voir les images : 

![image](https://github.com/crespo742/docker_test/assets/56248842/af75751b-5754-45b3-8f44-a37900783685)

#### On creer un compose.yml a la racine du projet

![image](https://github.com/crespo742/docker_test/assets/56248842/2b9cfc3a-1741-43db-b355-561fa917046c)

#### on execute cette commande : 

```bash

docker compose up -d

```

#### On retourne ce résultat :

![image](https://github.com/crespo742/docker_test/assets/56248842/e64fa98b-ca30-4652-aba2-6b6b7b74cd03)

#### Voici le site avec le vote : 

![image](https://github.com/crespo742/docker_test/assets/56248842/ba140413-5ee2-4031-b269-5a7fecd94639)


#### et ici le resultat du vote : 

![image](https://github.com/crespo742/docker_test/assets/56248842/5d8d6737-df43-44ba-b424-9b114c0e1421)













