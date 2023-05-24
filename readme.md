# Ansible 
Ansible est un outil populaire de gestion de la configuration, de déploiement d'applications et d'automatisation des tâches informatiques. Il est utilisé pour orchestrer et gérer des systèmes informatiques, des réseaux et des infrastructures de cloud computing.

## Ce qu'il faut savoir sur Ansible
-Architecture client-serveur : Ansible suit une architecture client-serveur avec un contrôleur et des nœuds gérés.

-Inventaire : L'inventaire est un fichier qui répertorie les machines distantes sur lesquelles vous souhaitez exécuter des actions.

-Playbooks : Les playbooks sont des fichiers YAML qui décrivent les tâches à exécuter sur les nœuds gérés.

-Modules : Ansible utilise des modules pour effectuer des actions spécifiques sur les nœuds gérés.

-Tâches : Les tâches sont des actions à effectuer sur les nœuds gérés et sont associées à des modules.

-Commandes ad-hoc : Ansible permet d'exécuter des commandes ponctuelles sans créer de playbook.

## Travail à faire avant d'utiliser Ansible
Tous d'abord il faut l'installer sur linux

Puis tapez les commnades suivants :

sudo apt update
sudo apt upgrade

Et enfin installer Ansible à l'aide des commandes suivantes :

sudo apt install ansible