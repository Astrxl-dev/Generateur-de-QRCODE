# 📱 Générateur de QR Code Permanent

Une petite application web minimaliste, ultra-rapide et sans dépendance serveur pour générer des QR codes permanents en quelques secondes.

*(Pense à glisser-déposer une capture d'écran de ton interface ici !)*

### ✨ Pourquoi ce projet ?

Beaucoup de générateurs en ligne créent des QR codes "dynamiques" qui finissent par expirer ou demander un abonnement. Ici, tout est généré **100 % côté client** dans ton navigateur : ton QR code pointe directement vers ton lien, sans intermédiaire et sans date d'expiration, gratuitement.

### 🚀 Fonctionnalités

* **Génération instantanée :** Saisis ton URL ou ton texte, appuie sur *Entrée* (ou clique sur *Générer*) et c'est prêt.
* **Taille personnalisable :** Ajuste la dimension de l'image de `100px` à `600px` selon tes besoins.
* **Niveau de correction d'erreur :** Choisis la résistance du QR code (`L` léger, `M` moyen, `H` max — idéal si tu veux l'imprimer ou qu'il risque d'être un peu abîmé).
* **Export direct :** Télécharge le résultat en un clic au format `.png` prêt à l'emploi.
* **Interface sombre & épurée :** Design minimaliste pensé pour être lisible aussi bien sur ordinateur que sur mobile.

### 🛠️ Technologies utilisées

* **HTML5 / CSS3 :** Structure en un seul fichier, thème sombre (`#0d0d0d` / `#6ee7b7`) et design responsive.
* **JavaScript (Vanilla) :** Gestion des interactions et export du `<canvas>` en image PNG.
* [**QRCode.js**](https://davidshimjs.github.io/qrcodejs/) : Bibliothèque légère chargée via CDN pour le rendu du QR code.

### 💻 Utilisation en local

Pas besoin d'installer Node.js, Python ou quoi que ce soit :

1. **Clone le dépôt :**
   ```bash
   git clone https://github.com/Astrxl-dev/Generateur-de-QRCODE.git
   ```

2. **Lance l'outil :** Ouvre simplement le fichier `QR_Code_Generator.html` dans ton navigateur web.

---

Développé par **Astrxl-dev**
