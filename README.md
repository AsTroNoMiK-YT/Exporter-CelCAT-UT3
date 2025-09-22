# ❓ Exporter-CelCAT-UT3
Ce post concerne les étudiants, étudiantes, enseignants et enseignantes de l'Université de Toulouse. Exportez facilement votre Emploi du Temps CelCAT en format iCalendar (.ics) pour le visualiser sur Google Agenda, Outlook, Excel... (ou n'importe quel autre logiciel de calendrier). 
*Remarque: Ce code-ci est une mise à jour et bugfixing d'un ancien script fait par [@kotomax24](https://github.com/kotomax24/CELCAT-to-.ics), mais ce script est inactif et ne fonctionne plus. Par contre, ce script est actualisé à 2025.*

# 📂 TÉLÉCHARGER LE SCRIPT: [Cliquez ici.](url)

# 1️⃣ PRÉ-REQUIS:
- # 👉 Une compte UT3 active ([adhérée à votre emploi du temps CelCAT](https://edt.univ-tlse3.fr/calendar/))
- # 👉 Un ordinateur avec un navigateur capable d'installer des extensions (préférablement Google Chrome)
- # 👉 L'extension [Tampermonkey](https://www.tampermonkey.net/)
  
# 2️⃣ INSTRUCTIONS:
- # 🔧 Mise en place de l'extension Tampermonkey:
  - Après avoir installé et activé l'extension [Tampermonkey](https://www.tampermonkey.net/), allez sur chrome://extensions (ou Chrome -> Paramètres -> Extensions).
  - Cherchez l'extension Tampermonkey que vous venez d'installer, assurez-vous qu'elle est activée (case bleue), puis cliquez sur **Détails**.
  - **Cochez toutes les cases** de l'extension (en particulier celle qui donne le permis aux usagers d'exécuter des codes).

- # 💾 Installation du Script (code):
  - Téléchargez le fichier du script si cela n'est déjà pas fait.
  - Dans une nouvelle fenêtre de votre navigateur, cliquez sur le symbole en forme de "puzzle", puis retrouver le logo noir qui correspond à Tampermonkey:
  - <img width="856" height="597" alt="image" src="https://github.com/user-attachments/assets/6d73ecc9-fd55-4938-a938-4c303c83acfd" />

  
  - Cliquez sur "Créer un nouveau script":
  - <img width="311" height="472" alt="image" src="https://github.com/user-attachments/assets/e8ee42d0-8331-47cc-931f-73726e934f8b" />

  
  - Une nouvelle fenêtre devrait s'ouvrir. Effacez tout le contenu du nouveau script et faites un copier-coller du contenu du fichier du script:
  - <img width="1919" height="861" alt="image" src="https://github.com/user-attachments/assets/a06b2992-2327-4bbc-8191-68738a51f48f" />

  
  - Cliquez sur **Fichier** -> **Sauvegarder** (en haut à gauche).

 
  - Assurez-vous que le script soit bien activé dans l'onglet **Userscripts installés**:
  - <img width="1530" height="192" alt="image" src="https://github.com/user-attachments/assets/83bfb443-661f-4b1a-96c2-d3bded049a4b" />

- # 3️⃣ Tester sur CelCAT
  - Une fois l'extension est installée correctement, fermez votre navigateur (ceci est afin d'éviter des éventuels problèmes/bugs inattendus), puis réouvrez-le.
  - Ouvrez une onglet CelCAT et connectez-vous à votre emploi du temps.
  - Vous devriez maintenant voir apparaître une nouvelle option sur la barre d'en haut:
  - <img width="1271" height="366" alt="image" src="https://github.com/user-attachments/assets/9b0efddd-f64b-41e5-b9dd-57e5611cbf8a" />

  
  - Cliquez sur **Exporter**. Sélectionnez l'intervalle de dates désiré pour récupérer l'emploi du temps associé. Je vais choisir par exemple depuis le 22 septembre 2025 jusqu'au 16 juin 2026. Puis cliquez sur **Exporter**.
  - <img width="751" height="414" alt="image" src="https://github.com/user-attachments/assets/a1e8ef6f-ec79-4741-a416-a946139d727a" />

- # ✅ ET C'EST TOUT! ;) Un fichier .ics devrait se télécharger automatiquement sur votre navigateur.

- # ➕ Quoi faire avec ce fichier?
