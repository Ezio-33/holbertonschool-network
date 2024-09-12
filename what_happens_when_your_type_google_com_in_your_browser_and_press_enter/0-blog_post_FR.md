<h1 align="center">
  Le voyage d'une requête <br> De la barre d'adresse à la page Google
</h1>

## Introduction

Bonjour à tous ! Je suis actuellement en formation chez Holberton School, où j'apprends les fondamentaux du développement logiciel avec l'ambition de me spécialiser en machine learning. Cet article est rédigé dans le cadre d'un projet de ma formation et, conformément aux exigences, il sera publié en anglais.
Aujourd'hui, je vais vous emmener dans les coulisses d'une action que nous effectuons des dizaines de fois par jour : taper une URL dans notre navigateur. Plongeons dans le fascinant voyage d'une requête web, de votre clavier jusqu'aux serveurs de Google.

### 1. La résolution DNS : Le GPS d'Internet

Lorsque vous tapez "www.google.com" et appuyez sur Entrée, votre navigateur ne sait pas immédiatement où aller. Il a besoin de traduire ce nom de domaine en une adresse IP. C'est là qu'intervient le DNS (Domain Name System).

- Votre navigateur vérifie d'abord son cache local.
- Si l'adresse n'est pas en cache, il interroge le serveur DNS de votre FAI.
- Si nécessaire, la requête remonte jusqu'aux serveurs DNS racine.
- Une fois l'adresse IP obtenue, votre navigateur sait où envoyer sa requête.

### 2. Établissement de la connexion sécurisée : Le tunnel chiffré

Avec l'adresse IP en main, votre ordinateur établit une connexion sécurisée avec le serveur de Google en utilisant le protocole HTTPS.

- Votre navigateur envoie une requête au serveur pour établir une connexion sécurisée.
- Le serveur répond avec son certificat SSL contenant sa clé publique.
- Votre navigateur vérifie le certificat et génère une clé de session, qu'il crypte avec la clé publique du serveur.
- Le serveur décrypte la clé de session avec sa clé privée. Maintenant, le navigateur et le serveur peuvent échanger des données de manière sécurisée.

### 3. Le pare-feu : Le douanier du web

Une fois la connexion sécurisée établie, votre requête chiffrée passe par plusieurs pare-feu.

- Ces gardiens virtuels vérifient si votre demande est légitime.
- Ils analysent les paquets de données pour détecter toute activité suspecte.
- Si tout est en ordre, votre requête est autorisée à poursuivre son chemin.

### 4. L'équilibreur de charge : Le chef d'orchestre du trafic web

Google reçoit des millions de requêtes par seconde. Pour gérer ce trafic colossal, ils utilisent des équilibreurs de charge.

- Ces systèmes intelligents distribuent les requêtes entrantes sur plusieurs serveurs.
- Ils assurent une répartition équitable de la charge de travail.
- Ils vérifient également la santé des serveurs, redirigeant le trafic loin des serveurs défaillants.

### 5. Le serveur web : La vitrine de Google

Une fois votre requête attribuée à un serveur spécifique, le serveur web entre en jeu.

- Il interprète votre requête HTTP.
- Il prépare les ressources statiques (HTML, CSS, JavaScript) nécessaires.
- Pour les contenus dynamiques, il fait appel au serveur d'application.

### 6. Le serveur d'application : Le cerveau de l'opération

C'est ici que la magie opère vraiment. Le serveur d'application génère dynamiquement la page que vous allez voir.

- Il exécute des algorithmes complexes pour personnaliser votre expérience de recherche.
- Il prend en compte vos préférences, votre localisation, et de nombreux autres facteurs.
- Il orchestre la création de la page de résultats unique à votre requête.

### 7. La base de données : La mémoire de Google

Pour fournir les résultats les plus pertinents, le serveur d'application interroge d'énormes bases de données.

- Ces bases de données contiennent des index de milliards de pages web.
- Elles sont constamment mises à jour par les robots d'indexation de Google.
- Des algorithmes sophistiqués sont utilisés pour extraire les résultats les plus pertinents en une fraction de seconde.

## Conclusion

Ce voyage fascinant, de la frappe de l'URL à l'affichage de la page de résultats, se déroule en moins d'une seconde. C'est le fruit d'une infrastructure colossale et d'innovations technologiques constantes.

En tant qu'aspirant spécialiste en machine learning, je suis particulièrement intrigué par la façon dont l'IA et l'apprentissage automatique sont intégrés à chaque étape de ce processus, de l'optimisation des requêtes DNS à la personnalisation des résultats de recherche.

J'espère que cet article vous a aidé à mieux comprendre la complexité des requêtes lorsque vous allez sur vos sites préférés.

N'hésitez pas à me poser des questions ou à partager vos réflexions dans les commentaires.

Lien de l'article [Linkedin](https://www.linkedin.com/pulse/journey-query-from-address-bar-google-page-samuel-verschueren-xnque/)
