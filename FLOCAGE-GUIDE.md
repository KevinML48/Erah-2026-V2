# 🎨 Guide du Flocage Personnalisé - Boutique ERAH

## ✅ Modifications effectuées

### 1. **Champs de personnalisation ajoutés**

Deux champs ont été ajoutés sur la page boutique.html :

- **Nom/Pseudo** : Champ texte obligatoire (max 15 caractères)
- **Numéro** : Champ optionnel (max 3 chiffres)

### 2. **Image du produit activée**

L'image du t-shirt s'affiche maintenant dans le widget Shopify au lieu du rectangle gris.

### 3. **Validation automatique**

Lorsqu'un client clique sur "Ajouter au panier" :

- ⚠️ Si le nom n'est pas renseigné → Message d'alerte
- ✅ Si le nom est renseigné → Ajout au panier avec les infos de flocage

### 4. **Affichage dans le panier**

Les informations de flocage apparaissent dans le panier :

- Badge visuel rouge avec les détails du flocage
- Champ de note automatiquement rempli avec les informations

---

## 📋 Comment ça fonctionne pour le client

1. **Sélectionner la taille** (XS à 4XL)
2. **Remplir le nom/pseudo** pour le flocage
3. **Ajouter un numéro** (optionnel)
4. **Cliquer sur "Ajouter au panier"**
5. **Voir les infos de flocage** dans le panier
6. **Passer la commande** → Les infos sont dans la note de commande

---

## 🛒 Où trouver les informations de flocage dans Shopify

Quand vous recevez une commande :

1. **Allez dans Commandes** dans votre admin Shopify
2. **Ouvrez la commande**
3. **Regardez la section "Notes"** → Vous verrez :

   ```
   🎨 FLOCAGE PERSONNALISÉ:
   Nom/Pseudo: [Le nom du client]
   Numéro: [Le numéro choisi]
   ```

4. **Ces informations sont aussi visibles** dans les détails de chaque article du panier

---

## 🎯 Prochaines étapes

### Dans Shopify Admin :

1. Assurez-vous d'avoir ajouté toutes les tailles (XS à 4XL) comme variantes
2. Ajoutez une belle image du t-shirt au produit (elle s'affichera automatiquement)
3. Vérifiez que le prix est bien à 48,00 € pour toutes les tailles

### Pour les commandes :

- Notez les informations de flocage de chaque commande
- Transmettez ces infos à Intersport pour le flocage
- Organisez la livraison (La Poste ou retrait Mende)

---

## 💡 Conseils

- **Testez la commande** : Faites un test d'achat pour voir comment les infos apparaissent
- **Vérifiez les notes** : Toutes les infos de flocage sont dans les notes de commande
- **Communication** : Envoyez un email de confirmation avec les détails du flocage

---

## 🔧 Support technique

Si vous avez besoin de modifier :

- **Longueur max du nom** : Ligne 1154 → `maxlength="15"`
- **Longueur max du numéro** : Ligne 1167 → `maxlength="3"`
- **Rendre le numéro obligatoire** : Modifiez la validation dans le JavaScript

---

**Date de mise à jour** : 6 décembre 2025
**Version** : 1.0
