# TSSR-2409-P1-G2-Teleassistance

## Documentation générale

### 1. Présentation du projet, objectifs finaux  

**Objectifs finaux:**
- Objectif principal: Configurer un accès sécurisé pour faire de la téléassistance sur un serveur depuis un client en utilsant le logiciel TightVNC et la connexion Bureau à distance de Windows  
- Objectif secondaire: Script PowerShell pour faciliter la connexion initiale de la téléassistance  

### 2. Introduction : mise en contexte




### 3. Membres du groupe de projet (rôles par sprint)

Sprint 1ère semaine:   
Scrum master: Charles  
Product Owner: Igor  

Sprint 2ème semaine:
Scrum master:
Product Owner:

  
### 4. Choix techniques : quel OS, quelle version, etc.

- Server:  
Windows Server 2022  
Nom : SRVWIN01  
Compte : Administrator (dans le groupe des admins locaux)  
Mot de passe : Azerty1*  
Adresse IP fixe : 172.16.10.10/24  

- Client: 
Windows 10 Pro  
Nom : CLIWIN01  
Compte utilisateur : wilder (dans le groupe des admins locaux)  
Mot de passe : Azerty1*  
Adresse IP fixe : 172.16.10.20/24  

### 5. Difficultés rencontrées : problèmes techniques rencontrés
- Problème lors de la connexion de tightVNCviewer au serveur à distance:  
Message d'erreur au niveau du mot de passe



### 6. Solutions trouvées : Solutions et alternatives trouvées
 Dans le panneau de configuration de TightVNCserver: reconfiguration du mot de passe pour l'accès à distance

<img width="259" alt="Capture d'écran 2024-10-10 145844" src="https://github.com/user-attachments/assets/cfdefe11-2eab-4bb6-a26c-3b3195bb4846">


### 7. Améliorations possibles : suggestions d’améliorations futures

