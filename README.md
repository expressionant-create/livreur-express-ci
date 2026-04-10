# Livreur Express CI

**Micro SaaS pour vendeurs Instagram/Facebook à Abidjan**  
Outil ultra-simple qui transforme 15 minutes de copier-coller WhatsApp en 10 secondes.

### Problème résolu
Les vendeurs perdent 3-5 heures par jour à gérer les commandes et les livreurs manuellement.

### Ce que fait l’outil
- Formulaire mobile-first (nom, téléphone, commune, montant, frais)
- Bouton “Générer Bordereau”
- Bouton “Partager au Livreur” → ouvre WhatsApp avec message prêt
- Bouton “Envoyer Reçu Client”
- Stockage automatique dans Google Sheets
- Automatisation n8n (webhook + workflow)

### Stack technique
- Frontend : Zite (no-code mobile-first)
- Backend/Automation : n8n self-hosted
- Base de données : Google Sheets
- Intégration : WhatsApp (wa.me + Evolution API prêt à ajouter)

### Captures d’écran
![Formulaire](screenshot-formulaire.png)
![Bordereau](screenshot-bordereau.png)

### Démo live
→ [Accéder à l’application][(https://ton-lien-zite.app)](https://jprapport.zite.so/)  ← (mets ton vrai lien Zite ici)

### Workflow n8n
Le fichier JSON du workflow est dans le dossier `/n8n-workflow`.

### Résultat pour le client
Gain de 2 heures par jour + image professionnelle + suivi clair des commandes.
