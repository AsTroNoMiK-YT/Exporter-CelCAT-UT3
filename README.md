# ❓ Exporter-CelCAT-UT3
Ce post concerne les étudiants, étudiantes, enseignants et enseignantes de l'Université de Toulouse. Exportez facilement votre Emploi du Temps CelCAT en format iCalendar (.ics) pour le visualiser sur Google Agenda, Outlook, Excel... (ou n'importe quel autre logiciel de calendrier). 
*Remarque: Ce code-ci est une mise à jour et bugfixing d'un ancien script fait par [@kotomax24](https://github.com/kotomax24/CELCAT-to-.ics), mais son script est inactif et ne fonctionne plus. Par contre, ce script est actualisé à la version plus récente de CelCAT.*

# 📂 TÉLÉCHARGER LE SCRIPT: [> Cliquez ici <](https://github.com/AsTroNoMiK-YT/Exporter-CelCAT-UT3/blob/main/scriptCelCATExporter.js)

# 1️⃣ PRÉ-REQUIS:
- # 👉 Une compte UT3 active ([adhérée à votre emploi du temps CelCAT](https://edt.univ-tlse3.fr/calendar/))
- # 👉 Un appareil avec un navigateur capable d'installer des extensions (préférablement Google Chrome pour ordi ou app Tampermonkey depuis la Play Store pour téléphone)
- # 👉 L'extension [Tampermonkey](https://www.tampermonkey.net/)
  
# 2️⃣ INSTRUCTIONS:
- # 🔧 Mise en place de l'extension Tampermonkey:
  - Après avoir installé et activé l'extension [Tampermonkey](https://www.tampermonkey.net/), allez sur chrome://extensions (ou Chrome -> Paramètres -> Extensions).
  - Cherchez l'extension Tampermonkey que vous venez d'installer, assurez-vous qu'elle est activée (case bleue), puis cliquez sur **Détails**.
  - **Cochez toutes les cases** de l'extension (en particulier celle qui donne le permis aux usagers d'exécuter des codes).

- # 💾 Installation du Script (code):
  - [> Téléchargez le fichier <](https://github.com/AsTroNoMiK-YT/Exporter-CelCAT-UT3/blob/main/scriptCelCATExporter.js) du script si cela n'est déjà pas fait.
  - Dans une nouvelle fenêtre de votre navigateur, cliquez sur le symbole en forme de "puzzle", puis retrouver le logo noir qui correspond à Tampermonkey:
  - <img width="856" height="597" alt="image" src="https://github.com/user-attachments/assets/6d73ecc9-fd55-4938-a938-4c303c83acfd" />

  
  - Cliquez sur "Créer un nouveau script":
  - <img width="311" height="472" alt="image" src="https://github.com/user-attachments/assets/e8ee42d0-8331-47cc-931f-73726e934f8b" />

  
  - Une nouvelle fenêtre devrait s'ouvrir. Effacez tout le contenu du nouveau script et faites un copier-coller du contenu du fichier du script:
  - <img width="1919" height="861" alt="image" src="https://github.com/user-attachments/assets/a06b2992-2327-4bbc-8191-68738a51f48f" />

  
  - Cliquez sur **Fichier** -> **Sauvegarder** (en haut à gauche).

 
  - Assurez-vous que le script soit bien activé dans l'onglet **Userscripts installés**:
  - <img width="1530" height="192" alt="image" src="https://github.com/user-attachments/assets/83bfb443-661f-4b1a-96c2-d3bded049a4b" />

# 3️⃣ Tester sur CelCAT
  - Une fois l'extension est installée correctement, fermez votre navigateur (ceci est afin d'éviter des éventuels problèmes/bugs inattendus), puis réouvrez-le.
  - Ouvrez une onglet CelCAT et connectez-vous à votre emploi du temps.
  - Vous devriez maintenant voir apparaître une nouvelle option sur la barre d'en haut:
  - <img width="1271" height="366" alt="image" src="https://github.com/user-attachments/assets/9b0efddd-f64b-41e5-b9dd-57e5611cbf8a" />

  
  - Cliquez sur **Exporter**. Sélectionnez l'intervalle de dates désiré pour récupérer l'emploi du temps associé. Je vais choisir par exemple depuis le 22 septembre 2025 jusqu'au 16 juin 2026. Puis cliquez sur **Exporter**.
  - <img width="751" height="414" alt="image" src="https://github.com/user-attachments/assets/a1e8ef6f-ec79-4741-a416-a946139d727a" />

# 📂 TÉLÉCHARGER LE SCRIPT: [> Cliquez ici <](https://github.com/AsTroNoMiK-YT/Exporter-CelCAT-UT3/blob/main/scriptCelCATExporter.js)
# ✅ ET C'EST TOUT! ;) Un fichier .ics devrait se télécharger automatiquement sur votre navigateur.

# ➕ Quoi faire avec ce fichier?
- L'importation directe du fichier .ics sur Google Calendar semble donner une erreur. La solution que j'ai trouvé est d'importer le calendrier depuis une URL et non depuis le fichier.
- Vous pouvez utiliser Outlook pour créer le lien URL que vous utiliserez sur Google Calendar.
  **Comment obtenir un lien .ics depuis Outlook ?**

Pour obtenir un lien .ics depuis Outlook, procédez comme suit :
# (VOUS DEVEZ D'ABORD IMPORTER LE FICHIER .ics SUR OUTLOOK)
- <img width="1918" height="858" alt="image" src="https://github.com/user-attachments/assets/1095fe6b-f60a-4609-91b9-184dca33c14f" />
- <img width="1896" height="852" alt="image" src="https://github.com/user-attachments/assets/ec11471d-7df6-4d58-9446-b120b947fbc1" />

Ouvrez Outlook : Suivez ce lien : https://outlook.live.com/calendar/0/view/workweek. Connectez-vous.
<img width="3024" height="1712" alt="image" src="https://github.com/user-attachments/assets/c4bf2ce3-0426-4dc6-b41a-d22e4d03735b" />

Cliquez sur l'icône en forme d'engrenage en haut à droite de la page.
<img width="3024" height="1712" alt="image" src="https://github.com/user-attachments/assets/49baceaa-3276-44d2-bac3-7257b26ff030" />

Cliquez sur « Calendrier », puis sur « Calendriers partagés ».
<img width="3024" height="1712" alt="image" src="https://github.com/user-attachments/assets/ea78f341-e5d1-49cd-90b6-5c621e066108" />

Dans la section « Publier un calendrier », sélectionnez le calendrier pour lequel vous souhaitez ajouter un lien .ics.
<img width="3024" height="1712" alt="image" src="https://github.com/user-attachments/assets/05f8b09f-0456-4d5b-91bd-e9c943f98ac0" />

Après avoir sélectionné le calendrier, sélectionnez le permis  « Peut afficher tous les détails »:

Cliquez sur « Publier »
Après avoir cliqué sur le bouton Publier, le lien ICS pour ce calendrier est généré et vous pouvez le copier et l'utiliser immédiatement.

<img width="3024" height="1712" alt="image" src="https://github.com/user-attachments/assets/13f48716-e6fc-4355-a6b6-a25b82bef0af" />

- Importer l'URL sur Google Calendar:
  **Autres calendaires -> Depuis URL -> Collez le lien que vous avez copié depuis Outlook -> Cliquez sur "Ajouter un calendrier"**
<img width="1076" height="617" alt="image" src="https://github.com/user-attachments/assets/0daa26bd-ede0-440a-8a18-406a2ba6919e" />
