---
lab:
  title: "Exercice\_1\_: personnaliser le processus de vente"
---

# Exercice 1 : personnaliser le processus de vente

## Scénario : Contoso Home Security 
Contoso Home Security est une entreprise de vente directe d’équipements de sécurité domestique et de services de surveillance. Elle propose des sonnettes connectées, des thermostats connectés, des produits de sécurité, des capteurs d’humidité, etc. Étant donné qu’elle offre un service de vente directe aux consommateurs, ses produits sont vendus en ligne ou dans ses magasins de détail présents dans 11 grandes villes américaines. Les clients en ligne sont affectés à un représentant de compte. Son rôle est d’effectuer le suivi du client et de tenter de lui fournir des produits et services supplémentaires. 

### Le processus de vente Contoso
Les représentants de compte sont affectés à tous les comptes d’entreprise qui recherchent des solutions de sécurité. Les ventes d’entreprise prennent généralement plus de temps et incluent plusieurs étapes et tâches différentes.

Un exemple de processus de vente peut inclure les étapes suivantes :

-   **Qualification :** le responsable de compte tente de déterminer si nos solutions conviendraient bien à un client.
-   **Développement :** le responsable de compte collabore avec d’autres membres de l’équipe commerciale pour créer une solution à même de satisfaire le client. Au cours de cette phase, les cadres doivent inclure des produits pertinents issus du catalogue de produits Contoso.
-   **Devis :** le cadre prépare et soumet un devis au client. Un devis peut passer par plusieurs itérations avant que le client ne soit convaincu.
-   **Vérification technique :** cette étape s’applique uniquement aux transactions évaluées à plus de 20 000 dollars. La solution doit être vérifiée par un consultant technique avant d’être validée.
-   **Validation :** le responsable de compte passe la transaction en revue une dernière fois et s’assure que le client est satisfait.

### Renforcement des liens avec les prospects 
Contoso dispose également d’un programme de renforcement des liens avec les prospects servant à maximiser les chances de validation d’une transaction. Le programme de renforcement des liens avec les prospects se compose des éléments suivants :

1.  **Appel téléphonique d’introduction :** le responsable de compte appelle le client pour présenter Contoso et ses produits.
2.  **E-mail d’information :** un jour après l’appel téléphonique initial, le responsable de compte envoie un e-mail au client. L’e-mail inclut des détails sur Contoso Home Security et les produits proposés.
3.  **E-mail de suivi :** trois jours après l’e-mail d’information, un second e-mail est envoyé au client afin de répondre à ses questions éventuelles.
4.  **Appel téléphonique pour planifier un rendez-vous :** deux jours après l’e-mail de suivi, le responsable de compte appelle le client à nouveau afin de décrocher un rendez-vous avec lui, pour déterminer si nos solutions lui conviendraient.

### Détails importants
-   Le processus de renforcement des liens avec les prospects ne doit être appliqué qu’aux clients de type comptes d’entreprise.
-   Contoso Home Security n’emploie pas le terme « Opportunités », mais plutôt **Transactions**.
-   Les transactions estimées à plus de 20 000 \$ nécessitent des vérifications techniques. Cette étape est nécessaire et la transaction ne peut pas être validée en son absence.
    -   La vérification technique et ses détails doivent être notés et fournis avec la transaction. Les détails doivent comporter le nom de la personne qui a procédé à la vérification, la date à laquelle elle a été effectuée et autres détails pertinents. Si le résultat est positif, cela doit également être précisé.
-   Les ventes de Contoso ne sont pas toutes enregistrées dans leur système CRM.
    -   Les transactions de leurs magasins de détail sont stockées dans un système de point de vente distinct.
    -   Les transactions en ligne sont stockées dans un site de commerce électronique distinct.
-   Contoso dispose également d’un programme de fidélité auquel les clients peuvent s’inscrire. Ces informations sont également stockées dans un site distinct.

Étant donné que Contoso dispose d’informations client dans plusieurs endroits, il est difficile de disposer d’une vue globale des clients recouvrant l’ensemble des organisations. La compagnie souhaite pouvoir consulter toutes ces données en même temps.

Les sources de données se trouvent dans les fichiers CSV suivants :
- **Clients :**https://aka.ms/CI-ILT/Contacts
- **Transactions des PDV de détail :**https://aka.ms/CI-ILT/POSPurchases
- **Transactions en ligne :**https://aka.ms/CI-ILT/OnlinePurchases
- **Clients membres du programme de fidélité :**https://aka.ms/CI-ILT/LoyaltySchemeCustomers

