#### Praktijkles Tekton ####

#### Voorbereiding ####

# Github
- Maak lokaal een folder tekton-praktijk aan
- Maak een account aan op github.com, indien je deze nog niet hebt
- Maak een fork van de github repo : https://github.com/jo8s/Breakout
- Genereer een SSH-key (indien nog nodig) met het commando: ssh-keygen -o -t rsa -C "ssh@github.com"
- Plaats de public key in je GitHub account onder Settings > SSH and GPG Keys
- Clone je repo lokaal in de tekton-praktijk folder

# OpenShift
- Maak een Sandbox aan voor OpenShift via: https://developers.redhat.com/developer-sandbox
    - Hiervoor is Developer account voor OpenShift nodig, maak deze aan indien je deze nog niet hebt
- Maak een Sandbox aan
- Login via je CLI 

# Deel 1 - voorbeeld Task: 
-  Zorg dat de GitOps Pipeline operator geïnstalleerd is (als deze niet geinstalleerd is)
- Maak de hello-task aan uit deel 1. Bekijk goed de configuratie van deze Task. Het is de bedoeling dat je deze straks zelf kan maken.
- Creëer de TaskRun uit deel 1 en zie het resultaat in OpenShift. Bekijk goed de configuratie van deze Taskrun. Het is de bedoeling dat je deze straks zelf kan maken.

# Deel 2 - Gebruik parameter: 
- Open de volgende website: https://tekton.dev/docs/pipelines/ . Deze documentatie kun je gebruiken als hulpmiddel bij alle opdrachten. 
- Maak een Task en TaskRun aan waarin “Hello World” uit deel 1 vervangen is voor een parameter (tip: zie documentatie ‘Tasks’ en ‘Taskruns’). 
- Maak een nieuwe Task en TaskRun aan waarbij de Walvis zegt “Goodbye Jenkins”. Maak hierbij ook gebruik van een parameter field. 
