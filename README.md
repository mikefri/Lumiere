# 💡 Lumiere-Remote - Interface de Contrôle

**Lumeire X** est un tableau de bord domotique moderne et élégant conçu pour piloter tes ampoules connectées (Tuya/Calex). L'interface utilise le **Glassmorphism** pour un look futuriste et une ergonomie pensée pour le mobile.

![Status](https://img.shields.io/badge/Status-Stable-success?style=for-the-badge)
![UI](https://img.shields.io/badge/UI-Glassmorphism-sky?style=for-the-badge)

---

## ✨ Fonctionnalités incluses

* **⚡ Master Off** : Un bouton global pour éteindre toutes les lumières en un seul clic.
* **📡 Statut en Temps Réel** : Double badge indiquant si l'appareil est **En ligne** (Wi-Fi) et s'il est **Allumé** ou **Éteint**.
* **🌫️ Ergonomie Intelligente** : Les lampes hors-ligne sont automatiquement floutées et verrouillées pour éviter les erreurs.
* **🌈 Contrôle Total** :
    * Sélecteur de couleurs RGB via une roue chromatique.
    * Gestion de l'intensité (Luminosité).
    * Gestion de la chaleur du blanc (Chaud à Froid).
* **📝 Clarté Maximale** : Chaque commande possède une légende textuelle explicative.
* **🔒 Sécurité & Confidentialité** : Tes clés API sont stockées uniquement dans ton navigateur (`LocalStorage`).

---

## 🚀 Installation Rapide

1.  **Déploiement** : Déploie le projet sur Vercel.
2.  **Configuration** :
    * À la première ouverture, un panneau apparaîtra pour demander tes clés API Tuya.
    * Entre ton **Access ID** et ton **Access Secret** (obtenus sur le portail Tuya IoT).
3.  **Utilisation** : Clique sur "Enregistrer" et tes lampes apparaîtront automatiquement.

---

## 🛠️ Stack Technique

* **Frontend** : HTML5 / Tailwind CSS (Styling) / JavaScript (Vanilla)
* **Backend** : Next.js API Routes (Serverless)
* **Librairies** : 
    * `iro.js` (Roue chromatique RGB)
    * `tuya-connector-nodejs` (Communication Cloud)

---

## 📖 Guide des Icônes

* 🔄 : Rafraîchir l'état de toutes les lampes.
* ⚡ : Éteindre absolument toutes les lumières connectées.
* ⚪ : Passer instantanément en mode "Blanc Pur" (maximum de luminosité).
* 🌈 : Ouvrir ou fermer le sélecteur de couleurs.

---

## ⚠️ Notes Importantes

* **Interrupteurs Physiques** : Si une lampe est marquée "Hors-ligne", vérifie que l'interrupteur au mur n'est pas coupé.
* **Clés API** : Si plus rien ne répond après plusieurs mois, vérifie la validité de ton projet sur la plateforme Tuya Cloud (le service gratuit doit être renouvelé périodiquement).

---

**Développé avec ❤️ pour un contrôle total sur ton éclairage.**
