# TrueSole

Vérification d’authenticité de chaussures de seconde main via Intelligence Artificielle et Blockchain (Hedera).

TrueSole est une plateforme qui permet de vérifier l’authenticité de chaussures grâce à une combinaison de reconnaissance visuelle par intelligence artificielle (IA) et de certification immuable sur la blockchain Hedera. Notre solution vise à instaurer la confiance sur le marché du resale — sans dépendre des marques.

---

## 🎯 Problème

Le marché de la contrefaçon de sneakers représente plusieurs milliards de dollars de pertes chaque année. Sur le marché de seconde main :

- Il est difficile de prouver l’authenticité d’une paire.
- Les acheteurs sont vulnérables face aux arnaques.
- Les vendeurs honnêtes n’ont aucun moyen fiable de valoriser leur produit.

Il n’existe pas de système de certification simple, public et vérifiable à grande échelle.

---

## 💡 Solution TrueSole

TrueSole permet à un vendeur de générer un certificat d’authenticité numérique en suivant ces étapes :

### 1. Connexion du vendeur via un portefeuille Hedera
Permet d’associer chaque certificat à une identité vérifiable.

### 2. Soumission de 4 images de la chaussure
À partir d’angles définis pour normaliser la vérification.

### 3. Vérification via un modèle IA
Le modèle retourne un score de confiance en comparant les images à des références.
- Seules les paires dépassant un seuil (ex : 90 %) reçoivent un certificat.

### 4. Génération d’un certificat sur Hedera
Chaque certificat inclut :
- Un identifiant unique
- Les métadonnées (modèle, taille, couleur…)
- Le score IA
- L’adresse du portefeuille vendeur

Le tout est stocké de manière immuable sur la blockchain Hedera.

### 5. Vérification par l’acheteur
L’acheteur peut consulter le certificat via l’identifiant :
- Accès aux photos, score IA, identité du vendeur.

### 6. Transfert de propriété (future release)
Le nouveau propriétaire peut revendiquer la paire via son portefeuille Hedera.

### 7. Signalement communautaire (optionnel)
Les utilisateurs peuvent signaler les certificats suspects pour modération.

---

## 🔒 Pourquoi c’est solide

| Fonctionnalité                  | Bénéfice                                                 |
|--------------------------------|-----------------------------------------------------------|
| IA avec score visible          | Transparence et confiance                                 |
| Certificat sur Hedera          | Preuve immuable et publique                               |
| Lien avec portefeuille vendeur | Traçabilité de l’origine                                  |
| Recherche via ID unique        | Facilité d’usage pour l’acheteur                          |
| Prévu pour transfert de propriété | Favorise la circularité et la revente vérifiée       |
| Système sans fabricant requis  | Déploiement rapide et flexible                            |

---

## 🔭 Perspectives futures : intégration des fabricants

TrueSole fonctionne sans l’intervention des marques. Mais à long terme, les fabricants pourraient :

- Fournir des images officielles (pour entraîner l’IA)
- Émettre des certificats de niveau supérieur
- Suivre le cycle de vie de leurs produits

Cela ouvrirait la voie à un véritable "passeport numérique" pour les chaussures.

---

## ✅ En résumé

TrueSole combine :

- L’IA pour la reconnaissance d’authenticité
- La blockchain pour la certification et la traçabilité
- Une interface simple pour vendeurs et acheteurs

Notre solution répond à un vrai problème (contrefaçon, manque de confiance dans la seconde main) tout en restant techniquement faisable dans le cadre d’un hackathon Hedera x IA.

---

> Ce projet a été développé dans le cadre de l’Empower X-Hack 2.0 — un hackathon pluridisciplinaire axé sur les solutions durables à impact réel, utilisant Hedera DLT et l’intelligence artificielle.
